# Kavosh Monfared

**Senior Software Engineer | AI Automation & Healthcare Systems**

I build AI systems that work inside clinical workflows -- where wrong outputs have real
consequences, evaluation is a safety mechanism, and "it usually works" is not good enough.

15 years in software engineering. The last year spent deep in LLM pipelines, automated
evaluation, and agentic systems for healthcare. Before that: hospital information systems,
FHIR interoperability, and clinical data platforms.

---

### Live Demo

**[Clinical Note Classifier](https://huggingface.co/spaces/kavoshm/clinical-note-classifier)** -- Try it now. Paste a clinical note and get structured triage output: urgency level, ICD-10 code, chain-of-thought reasoning, and recommended actions. 100% urgency accuracy on 20 test cases, 85% ICD-10 exact match. Runs in demo mode with pre-computed results (no API key needed).

---

### What I Work On

**AI Evaluation & Quality** -- Automated evaluation frameworks for LLM-generated clinical
outputs using G-Eval, LLM-as-judge, and domain-specific rubrics. If you are building AI
for healthcare and not measuring output quality systematically, we should talk.

**Agentic Clinical Pipelines** -- Multi-step LLM chains that extract structured data from
unstructured clinical notes, validate against medical terminologies, and write FHIR R4
resources back to the EHR. LangGraph for orchestration, human-in-the-loop for safety.

**LLMOps for Healthcare** -- CI/CD pipelines that treat prompt changes like code changes:
versioned, tested, evaluated, and blocked on regression. Prompt management systems that
give teams the same confidence in AI changes that they have in code changes.

---

### Featured Projects

| Project | What It Does | Key Tech |
|---------|-------------|----------|
| [Clinical Note Classifier](https://github.com/kavoshm/clinical-note-classifier) | LLM-powered triage with chain-of-thought reasoning — **[Live Demo](https://huggingface.co/spaces/kavoshm/clinical-note-classifier)** | Few-shot prompting, Gradio, Pydantic |
| [Clinical Eval Framework](https://github.com/kavoshm/clinical-eval-framework) | Automated quality scoring for LLM clinical outputs with 4 rubrics and regression detection | G-Eval, GPT-4-as-judge, baseline management |
| [Clinical Intake Pipeline](https://github.com/kavoshm/clinical-intake-pipeline) | Multi-agent extraction from clinical notes to FHIR R4 resources with human-in-the-loop | LangGraph, FHIR R4, function calling |
| [Mental Health RAG](https://github.com/kavoshm/mental-health-rag) | RAG system for querying clinical treatment protocols with citation-backed answers | ChromaDB, MMR retrieval, FastAPI |
| [Clinical AI CI/CD](https://github.com/kavoshm/clinical-ai-cicd) | CI/CD pipeline for LLM apps with automated evaluation and PR-level quality gates | GitHub Actions, eval automation |

---

### Writing

**[Why LLM-as-Judge Works Differently in Healthcare](https://kavoshm.github.io/blog/)** -- Lessons from building clinical evaluation pipelines. Covers why BLEU/ROUGE fail for clinical text, how safety-weighted rubrics change evaluation design, and what chain-of-thought scoring reveals about LLM reliability in healthcare.

---

### Tech Stack

```
AI/LLM:        LangChain  |  LangGraph  |  OpenAI API  |  Azure OpenAI  |  Ollama
                RAG  |  G-Eval  |  LLM-as-Judge  |  Prompt Engineering

Healthcare:    FHIR R4  |  HL7 v2  |  ICD-10  |  SNOMED CT  |  LOINC
                Clinical NLP  |  EHR Integration  |  PHI/HIPAA

Engineering:   Python  |  C# / .NET  |  FastAPI  |  React  |  Docker
                Azure  |  GitHub Actions  |  PostgreSQL  |  SQL Server
```

---

### Get in Touch

- **LinkedIn:** [Kavosh Monfared](https://www.linkedin.com/in/kavosh-m-5479063ba/)
- **Email:** monfaredkavosh@gmail.com
- **Portfolio:** [kavoshm.github.io](https://kavoshm.github.io)
- **Location:** Tehran, Iran (open to relocation)
