# Syllabus: AI-Augmented Full-Stack Blitz (Java & Angular)

## Program Overview

This program uses AI as a **Context Bridge**. Developers will focus on **Spec-Driven Development (SDD)** to describe system intent in natural language, allowing AI agents (GitHub Copilot, Google ADK, and Google Antigravity) to handle the syntax-heavy implementation across the unfamiliar stack.

---

## Week 1 – Foundations of Generative AI (Intro to ADK)

* **Learning Focus**: GenAI basics, LLMs, agents  
* **Google Cloud Skills Boost**: [Introduction to Generative AI](https://www.cloudskillsboost.google/paths/118)  
* **Microsoft Learn**: [Introduction to Generative AI and Agents](https://learn.microsoft.com/en-us/training/modules/introduction-to-generative-ai/)

---

## Week 2 – LLMs and Prompt Engineering (LLM Agent usage)

* **Learning Focus**: LLM architecture, prompt tuning  
* **Google Cloud Skills Boost**: [Introduction to Large Language Models](https://www.cloudskillsboost.google/paths/119)  
* **Microsoft Learn**: [Prompt Engineering Fundamentals](https://learn.microsoft.com/en-us/training/modules/introduction-to-prompt-engineering/)

---

## 6-Week Curriculum

### Week 1: AI Foundations & Mental Models

* **Topics:** Prompt engineering for architects, crafting System Instructions, and the CRAFT (Context, Role, Action, Format, Target) prompting method.
* **Core Skills:** Establishing a project `constitution.md` to define non-negotiable architectural standards.
* **Resource:** *(Link validation in progress or replace with official course if unavailable.)*

---

### Week 2: GitHub Copilot & Agentic TDD

* **Topics:** Red-Green-Refactor with AI, using `@workspace` for global repository context, and generating tests for legacy code.
* **Core Skills:** Prompting Copilot to generate 100% test coverage for logic that hasn't been written yet.
* **Resource:** [Develop Unit Tests with GitHub Copilot](https://learn.microsoft.com/en-us/training/modules/develop-unit-tests-with-github-copilot/)

---

### Week 3: Spec-Driven Development (SDD)

* **Topics:** Writing `SPEC.md` and `PLAN.md` files, using the GitHub Spec Kit, and scaffolding modules via intent.
* **Core Skills:** Converting high-level business requirements into agent-executable implementation tasks.
* **Resource:** [Spec-Driven Development with GitHub Spec Kit](https://learn.microsoft.com/en-us/training/modules/spec-driven-development-github-spec-kit-enterprise-developers/)

---

### Week 4: The Cross-Stack Bridge

* **Topics:** Generating Angular Services from Spring Boot Controllers; generating Spring Entities from UI data models.
* **Core Skills:** Automating DTO-to-Interface mapping and ensuring API contract parity across stacks.
* **Resource:** [Agentic Barista – Google Developer Solutions](https://developers.google.com/solutions/learn/agentic-barista)

---

### Week 5: Agentic Refactoring with Antigravity

* **Topics:** Refactoring monolithic Java to modular services, updating Angular versions (e.g., to Signals/Standalone), and autonomous "missions".
* **Core Skills:** Using Antigravity's integrated browser for real-time UI verification of refactored code.
* **Resource:** [Optimizing Angular Development with Google Antigravity](https://medium.com/@davidepassafaro/optimizing-angular-development-with-google-antigravity-3585495ce120)

---

### Week 6: Multi-Agent Systems (Google ADK)

* **Topics:** Orchestrating `SequentialAgent` and `ParallelAgent` workflows in Java.
* **Core Skills:** Building an assembly-line pipeline where one agent updates the Java backend and a sub-agent synchronizes the Angular frontend.
* **Resource:** [Google ADK Java Codelab](https://codelabs.developers.google.com/adk-java-getting-started)

---

## Graduation Capstone Projects

### 1. The AI-Powered Barista System

* **Objective:** Build a multimodal coffee ordering app where users can upload photos for recommendations.
* **Stack:** Angular + Genkit + Vertex AI (Gemini)
* **Key Feature:** Implement a "Human-in-the-loop" order submission where the agent pauses for a manual confirmation button in the UI before executing a Java tool call.

---

### 2. The Legacy "Refactor Mission"

* **Objective:** Modernize a legacy Java codebase (e.g., EJB/Struts) into a Spring Boot API and Angular frontend.
* **Stack:** Java Spring Boot, Angular Signals, Google Antigravity
* **Key Feature:** Use Antigravity to assign a "Refactor Mission" that updates legacy UI components to modern Angular patterns while maintaining 100% functional parity verified by browser recordings.

---

### 3. Self-Healing Multi-Agent Dashboard

* **Objective:** Create a dashboard where backend schema changes automatically trigger frontend interface updates.
* **Stack:** Google ADK (Java), Angular, GitHub Copilot Agent Mode
* **Key Feature:** Build a `SequentialAgent` in Java that:
  1. Extracts a new field requirement from a `SPEC.md`.
  2. Updates the Java Entity and Controller.
  3. Triggers a sub-agent to update the Angular Service and Interface with the new types.

---

Let me know if you'd like a downloadable version or if you’d like me to convert this into a `.pptx` or `.zip` for Agent Mode.
