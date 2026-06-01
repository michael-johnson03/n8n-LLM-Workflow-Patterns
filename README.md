# n8n-llm-workflow-patterns

Six progressive **low-code LLM workflow patterns** built in n8n — from basic single-LLM chains through full RAG and agentic patterns. Companion to the equivalent Python implementations: argues *which tool fits which problem*.

> 🚧 **Repository under preparation.** Workflow JSON exports and walkthrough documentation are being prepared for public release.

---

## What this project will contain

Six workflow exports, each with its own README explaining the pattern:

1. **Basic LLM chain** — single-call prompt with system message
2. **In-memory RAG** — embedding lookup against a local vector store
3. **Qdrant RAG (Gemini variant)** — production-style vector RAG with managed Qdrant
4. **Qdrant RAG (Ollama variant)** — same pattern with local model substitution
5. **Snowflake-tool agent** — multi-tool agent calling Snowflake for live data retrieval
6. **News-to-Telegram pipeline** — scheduled RSS aggregation with LLM summarization and Telegram bot delivery

## What this shows

- Tool selection: when low-code wins over full code (rapid prototyping, integration-heavy workflows, non-engineers can read it)
- The same RAG and agent patterns expressed across paradigms (Python, n8n, Snowflake Cortex)
- Visual workflow design as a different cognitive model from imperative code

## Tech stack

n8n · Qdrant · Ollama · Gemini · Snowflake · Telegram Bot API · RSS

## Cross-references

- The Python equivalents of these patterns live in [`reddit-fraud-intelligence`](https://github.com/michael-johnson03/reddit-fraud-intelligence) (production pipeline) and [`it-helpdesk-rag-chatbot`](https://github.com/michael-johnson03/it-helpdesk-rag-chatbot) (RAG application)

---

For early discussion or questions about the work, reach out via [LinkedIn](https://www.linkedin.com/in/michael-d-johnson3/).
