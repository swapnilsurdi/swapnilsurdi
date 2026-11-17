# Hi, I'm Swapnil Surdi 👋

**I build production AI systems — RAG pipelines, agentic fleets, and the backend infrastructure that keeps them fast, cheap, and reliable.**

[![Portfolio](https://img.shields.io/badge/Portfolio-surdi.in-brightgreen?style=flat-square&logo=google-chrome)](https://surdi.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-surdi-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/surdi/)
[![Google Scholar](https://img.shields.io/badge/Scholar-publications-4285F4?style=flat-square&logo=googlescholar)](https://scholar.google.com/citations?hl=en&user=66E21KUAAAAJ)
[![Email](https://img.shields.io/badge/Email-swapnil.surdi@icloud.com-red?style=flat-square&logo=maildotru)](mailto:types.belief-0c@icloud.com)

Ten years of building software (8+ professional), most recently 4 years of AI systems in
regulated healthcare — HIPAA / ISO 13485 — where "it usually works" isn't an option.

### What I've shipped

- **Agentic RAG in production** — MCP tool orchestration with multi-hop reasoning across docs,
  code, Confluence, and Jira; compliance retrieval cut from **30s to sub-second**, verification
  workflows **60% faster** (Qdrant, 768-dim embeddings, BM25 hybrid retrieval, NDCG/MRR evals).
- **LLM evaluation & inference at scale** — production benchmarking across OpenAI, Anthropic,
  Google, Meta, and Alibaba models; FastAPI async inference with rate-limit handling and
  **cross-provider failover**; multi-tenant single-deployment platform serving **100K+ daily
  requests at 99.9% uptime** with **60% lower infra cost**.
- **An autonomous agent fleet I sleep through** — *LaunchLab Fleet*: three recycled laptops, each
  operated by its own headless Claude Code agent. Private Matrix room as the agent bus, a
  self-written Go + SQLite status hub (one query went **4.18s → 18ms** with the right index), a
  zero-token watchdog that runs 288×/day without invoking a model, and a nightly triage pass
  that fixes incidents from a strict safe-allowlist — *the model is the exception, not the loop*.
  (Infra is private; build story coming to [surdi.in](https://surdi.in).)

### Featured repositories

| Project | What it is |
|---|---|
| [**mcp-cache**](https://github.com/swapnilsurdi/mcp-cache) | Transparent proxy cache for any MCP server — breaks the 25K-token tool-response wall, cuts LLM API cost 30–50%. Published as [`@hapus/mcp-cache`](https://www.npmjs.com/package/@hapus/mcp-cache) |
| [**email_mcp**](https://github.com/swapnilsurdi/email_mcp) | Multi-account email MCP server with a real security model: scoped per-agent keys, idempotent sends, allow/block-lists as the last line against a compromised agent, auth delegation with audit/pause/revoke |
| [**claudeskills**](https://github.com/swapnilsurdi/claudeskills) | Claude Code skills, starting with SMAC — Stochastic Multi-Agent Consensus for decision-making |
| [**mcp-pa**](https://github.com/swapnilsurdi/mcp-pa) | Personal-assistant MCP server (projects, status, calendar, documents) |
| [**jobscanner**](https://github.com/swapnilsurdi/jobscanner) | Cron-based job-posting scanner feeding the career-ops pipeline |

Also live: [stroller-lab.com](https://stroller-lab.com) — a stroller & car-seat comparison
product (React + Cloudflare Workers + Anthropic + Supabase), built and operated end to end.

### Patent & research

- **US20240129000A1** *(patent pending)* — fixed base-station antenna system (MIMO) for
  disaster-resilient mesh networks.
- *Space Situational Awareness Through Blockchain Technology* — Journal of Space Safety
  Engineering, 2020.
- Decentralized search for data marketplaces using IPFS — M.S. research, USC.

### Toolbox

**Python · Go · TypeScript** — FastAPI, Node.js, Django · **AI:** Claude, GPT, Gemini, Llama,
Qwen · MCP, RAG, embeddings, eval frameworks, LangChain/LlamaIndex · **Data:** PostgreSQL,
DynamoDB, Redis, Kafka, Qdrant · **Infra:** AWS, GCP, Docker, Terraform, Cloudflare, Tailscale ·
**Compliance:** HIPAA, ISO 13485, GDPR

---

📍 San Jose, CA · Open to Senior Software / AI Engineering roles · [surdi.in](https://surdi.in)
