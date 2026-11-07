# EduGPT:  Autonomous Multi-Agent Cognitive Tutoring Research 📖🤖

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)](https://python.org)
[![LangChain](https://img.shields.io/badge/LangChain-State%20Orchestration-1C3C3C?style=for-the-badge)](https://langchain.com)
[![CAMEL Architecture](https://img.shields.io/badge/Architecture-CAMEL%20Role--Playing-red?style=for-the-badge)](#multi-agent-cooperative-architecture)
[![Research Archive](https://img.shields.io/badge/Status-Foundational%20Research%20Archive-brightgreen?style=for-the-badge)](#research-context--evolution)

**Pioneering 2025 research investigating cooperative multi-agent role-playing loops (CAMEL) and LangChain state graphs for autonomous pedagogical curriculum synthesis.**

[Abstract](#abstract) • [Multi-Agent Architecture](#multi-agent-cooperative-architecture) • [Evolution to Astra Edu](#research-context--evolution) • [Setup](#local-development)

</div>

---

## 🔬 Abstract

Can two autonomous AI agents cooperatively educate each other without continuous human prompting? **EduGPT** addresses this challenge through an autonomous multi-agent simulation where an **Instructor Agent** and a **Student Agent** engage in iterative communicative problem-solving loops.

Inspired by the **CAMEL framework** (Communicative Agents for "Mind" Exploration) and powered by **LangChain**, the system autonomously generates task specifications, formulates progressive diagnostic inquiries, diagnoses student misconceptions, and iterates until conceptual mastery is mathematically verified.

---

## 🏛️ Multi-Agent Cooperative Architecture

```
                                  ┌────────────────────────┐
                                  │   TASK SPECIFIER AGENT │
                                  │   (Generates Domain)   │
                                  └───────────┬────────────┘
                                              │ Inception Prompting
                         ┌────────────────────┴────────────────────┐
                         ▼                                         ▼
            ┌────────────────────────┐                ┌────────────────────────┐
            │    INSTRUCTOR AGENT    │                │     STUDENT AGENT      │
            │  (Pedagogical Lead)    │                │  (Target Learner)      │
            │                        │                │                        │
            │ • Decomposes Syllabus  │                │ • Proposes Solutions   │
            │ • Socratic Challenges  │◀──────────────▶│ • Identifies Gaps      │
            │ • Verifies Mastery     │                │ • Tests Hypotheses     │
            └────────────────────────┘                └────────────────────────┘
```

---

## 🧬 Research Context & Evolution

```
[November 2025: EduGPT / VirtualTeacher]
   Explored autonomous CAMEL multi-agent role-playing dialogue for education.
   Core Finding: Purely stochastic agent interactions generate creative explanations
   but lack deterministic curriculum guarantees, auditability, and state persistence.
                     │
                     ▼ 
[October 2026: Astra Edu / Techgram Kernel]
   Engineered the Student Intelligence Kernel: a deterministic, zero-LLM belief
   state engine providing mathematically provable mastery progression.
```

This foundational research codebase provided the architectural justification for separating deterministic state estimation from generative synthesis in [`astra-edu-techgram`](https://github.com/mdroushanalam-astra/astra-edu-techgram).

---

## 🛠️ Tech Stack

- **Core Engine:** Python 3.10+
- **Agent Orchestration:** LangChain (`langchain`)
- **LLM Backbone:** OpenAI API (`gpt-4`)
- **Telemetry UI:** Gradio (`gradio`)

---

## 💻 Local Development

```bash
# 1. Clone repository
git clone https://github.com/mdroushanalam-astra/edugpt.git
cd edugpt

# 2. Setup virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate

# 3. Install requirements
pip install -r requirements.txt

# 4. Set OpenAI API key
export OPENAI_API_KEY="your-api-key"
```

---

<div align="center">
  <sub>Research conducted by <a href="https://github.com/mdroushanalam-astra">Md. Roushan Alam</a></sub>
</div>
