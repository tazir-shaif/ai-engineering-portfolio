# AI Engineering Portfolio
This repository contains hands-on practicals built while learning
AI Engineering for FAANG interviews.

## Modules
- ✅ Module 0 — Environment Setup
- ✅ Module 1 — Prompt Engineering
- ✅ Module 2 — Data Pipelines
- ✅ Module 3 — RAG Pipelines
- ✅ Module 4 — Fine-Tuning LLMs
- ✅ Module 5 — AI Agents & Tool Use
- ✅ Module 6 — Evaluation & Monitoring
- 🔄 Module 7 — Capstone Projects (in progress)
  - ✅ Project 1 — Swiggy AI Support Agent
  - ✅ Project 2 — AI News Research Agent
  - ⏳ Project 3 — Flipkart Product Intelligence
  - ⏳ Project 4 — AI Interview Coach

## Capstone Highlights

**Project 1 — Swiggy AI Support Agent**
Full agent combining long-term memory (Mem0), order lookup (Supabase), policy retrieval (FAISS RAG), and response generation (Groq), with LangSmith tracing and golden-set evaluation (V1 0.75 avg → V2 0.92 avg after fixes).

**Project 2 — AI News Research Agent**
Sequential multi-agent pipeline (Researcher → Summariser → Fact-checker) with live web search (Tavily), source-quality filtering (allowlist + relevance scoring), and Mem0 long-term memory. Surfaced and resolved real production issues: stale/ambiguous search results, untrustworthy sources slipping past filters, async memory-indexing delays, transient network failures, and a confirmed platform-level tool-calling bug in Groq's `openai/gpt-oss-20b` model — handled via graceful fallback rather than prompt engineering.

## Tools Used
Groq, LangChain, LangGraph, DSPy, Tavily, Mem0, Supabase, FAISS, sentence-transformers,
HuggingFace (PEFT/LoRA, TRL, Datasets), LangSmith, Opik, pandas, Python, Google Colab

## Repository Structure
See individual module/session folders for notebooks. Each notebook is self-contained
with markdown explanations and inline code comments.
