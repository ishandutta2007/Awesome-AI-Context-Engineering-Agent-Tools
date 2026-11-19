# Awesome-AI-Context-Engineering-Agent-Tools

## Top AI Context Engineering & Agent Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Context Engineering, Prompt & Repository Packing, Agent Tracing & Evaluation, RAG Context Pipelines & LLM Observability*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Context Engineering & Agent Tools**. These tools assemble, compress, and optimize context windows for AI agents, trace multi-step context retrieval and tool executions, manage versioned prompts and datasets, and evaluate agent reliability in production.



**Examples** include Langfuse, Helicone, LangSmith, Arize Phoenix, OpenLIT, Traceloop, HoneyHive, Lunary, Braintrust, Weights & Biases Weave, and bowenliang123/dsh-context (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for repository/codebase context packing (`Repomix`, `Gitingest`, `Code2Prompt`, `dsh-context`), self-hosted agent tracing and context evaluation (`Langfuse`, `Arize Phoenix`, `Opik`, `OpenLIT`), context compression (`LLMLingua`), and MCP context servers — ideal for AI engineers, context architects, and agent builders crafting deterministic, high-signal LLM pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The AI observability, context management, and evaluation market is currently estimated at approximately **$1.8B to $4.1B** and is projected to expand rapidly at a **~23% to 35% CAGR** through 2030 (driven in tandem by the explosive growth of RAG and agentic context platforms). 

The sector is currently **moderately fragmented at the tooling and evaluation application layer**—with intense competition among specialized developer-tool startups—while undergoing **rapid consolidation and concentration** toward dominant enterprise platforms and cloud hyperscalers acquiring pure-play observability leaders.



## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Starting Price (Paid Tier) | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Weights & Biases Weave](https://wandb.ai)** | $1.7B acquisition valuation (by CoreWeave); ~$50M ARR (2024) | $60 / month (Pro plan; 1.5 GB data ingestion included) | Free forever plan: 1 GB/month Weave data ingestion (traces, evaluations, prompt calls); 30-day Pro trial available | Cloud developer toolkit from W&B for logging, tracing, visualizing, and evaluating LLM calls, retrieved context chunks, and multi-agent trajectories. |
| **[LangSmith (LangChain)](https://langchain.com)** | $1.25B–$1.3B valuation (Series B, 2025); ~$15M ARR | $39 / seat / month (Plus plan; 10,000 shared base traces/month included) | Free forever plan (Developer): 1 seat, 5,000 base traces/month, 14-day retention | All-in-one cloud platform for tracing, debugging, testing, and evaluating context flows, prompt templates, and stateful LangGraph agent runs. |
| **[Arize AX / Arize Phoenix Cloud](https://arize.com)** | $915M acquisition valuation (by Dynatrace, 2025); ~$10M–$50M ARR | $50 / month (AX Pro plan; ~50,000+ span volume) | Free forever plan (AX Free): 25,000 spans/month, 15-day data retention; unlimited for self-hosted OSS Phoenix | Enterprise AI observability and evaluation platform delivering OpenTelemetry span tracing, RAG context relevance diagnostics, and drift detection. |
| **[Braintrust](https://braintrust.dev)** | Venture-backed (Raised $80M Series B in 2026; backed by a16z / ICONIQ) | $249 / month (Pro plan; 5 GB data, 50k scores, $100 model credits) | Free forever plan (Starter): 1 GB processed data/month, 10,000 evaluation scores/month, 14-day retention, $10 model credits | Enterprise AI evaluation, prompt playground, and logging platform designed to benchmark context-engineering changes and prevent quality regressions. |
| **[Traceloop](https://traceloop.com)** | $60M–$80M acquisition valuation (by ServiceNow, 2026); $6.6M total funding raised | Custom / Enterprise quote (starting at volume scale >50k spans) | Free forever plan: 50,000 spans/month, up to 5 user seats, 24-hour data retention; 100% free unlimited OSS SDK (OpenLLMetry) | Managed OpenTelemetry-native LLM observability platform built on OpenLLMetry for real-time agent context tracing and hallucination guardrails. |
| **[Helicone](https://helicone.ai)** | $25M valuation (Y Combinator W23, $5M Seed round) | $79 / month (Pro plan; unlimited seats, 1,000 logs/min) | Free forever plan (Hobby): 10,000 requests/month, 1 GB storage, 1 seat, 7-day data retention | Proxy-based AI gateway and observability platform providing request logging, prompt caching, token/context cost attribution, and multi-provider routing. |
| **[HoneyHive](https://honeyhive.ai)** | Seed-stage ($7.4M total funding raised; Insight Partners Seed lead) | Custom / Usage-based Enterprise tiers (startup program discounts available) | Free forever plan (Developer): 10,000 events/month, up to 5 seats, 1 workspace, 30-day retention | AI observability and evaluation suite built for compounding agent reliability via production context curation, human feedback loops, and CI/CD regression gates. |
| **[Langfuse Cloud](https://langfuse.com)** | Seed-stage ($4.5M total funding raised; Lightspeed Seed lead / YC W23) | $29 / month (Core plan; 100,000 units/month included, unlimited users) | Free forever plan (Hobby): 50,000 usage units/month, up to 2 users, 30-day data access; 100% free unlimited self-hosted OSS | Managed cloud deployment of the open-source LLM engineering platform offering trace analytics, decoupled prompt/context management, datasets, and online agent evaluations. |
| **[Lunary](https://lunary.ai)** | Early-stage startup (accelerator-backed via Xpreneurs; private bootstrapped/seed scale) | $20 / user / month (Team plan; 50,000 events/month and 300 playground queries included) | No free forever plan & no free trial for new cloud workspaces (upfront paid subscription required; self-hosted community edition free) | Production LLM observability, prompt management, and user analytics platform tailored for multi-step AI agent workflows and B2B AI applications. |
| **[OpenLIT Cloud](https://openlit.io)** | Open-source community & bootstrapping scale (no institutional funding raised) | Custom / Enterprise quote (Cloud hosted preview; contact for details) | Open-source self-hosted edition: Free forever with unlimited spans, traces, and metrics under Apache 2.0 (managed cloud tier in preview) | Hosted OpenTelemetry-native observability and GPU/LLM monitoring platform tracking token consumption, vector DB retrieval latency, and agent spans. |





## Open-Source GitHub Projects



- **[bowenliang123/dsh-context](https://github.com)**  

  Open-source developer shell and context-engineering utility designed for assembling, formatting, and managing structured project and task context for AI coding agents and LLMs.



- **[Repomix (`yamadashy/repomix`)](https://github.com)**  

  Popular open-source (`MIT`) CLI and MCP tool that packs entire Git repositories into single, AI-friendly XML, Markdown, or JSON files with Tree-sitter compression and token counting.



- **[Gitingest (`coderamp-labs/gitingest`)](https://github.com)**  

  Open-source (`MIT`) tool and web service that converts any Git repository into a clean, structured prompt-ready text digest optimized for LLM context windows.



- **[Code2Prompt (`mufeedvh/code2prompt`)](https://github.com)**  

  Fast open-source (`MIT`) Rust CLI and SDK that transforms codebases into structured LLM prompts using Handlebars templates, `.gitignore` rules, and tokenizers.



- **[Langfuse (`langfuse/langfuse`)](https://github.com)**  

  Leading self-hostable open-source LLM engineering platform for full-stack agent tracing, prompt/context versioning, session replays, and automated evaluations.



- **[Arize Phoenix (`Arize-ai/phoenix`)](https://github.com)**  

  Open-source (`ELv2`) OpenTelemetry-based AI observability and evaluation tool featuring interactive trace waterfalls, retrieval context inspection, and experimentation notebooks.



- **[OpenLIT (`openlit/openlit`)](https://github.com)**  

  Open-source (`Apache-2.0`) OpenTelemetry-native AI engineering platform providing zero-code instrumentation for 50+ LLM providers, agent frameworks, and vector databases.



- **[OpenLLMetry (`traceloop/openllmetry`)](https://github.com)**  

  Open-source (`Apache-2.0`) set of extensions built on standard OpenTelemetry to capture and export non-intrusive traces of prompts, retrieved context, and tool calls.



- **[Helicone (`Helicone/helicone`)](https://github.com)**  

  Open-source (`Apache-2.0`) AI gateway and observability proxy enabling self-hosted request logging, context caching, token metrics, and rate limiting.



- **[Lunary (`lunary-ai/lunary`)](https://github.com)**  

  Self-hostable open-source (`Apache-2.0`) toolkit for LLM observability, agent run visualization, prompt templates, and PII masking.



- **[Opik (`comet-ml/opik`)](https://github.com)**  

  Open-source (`Apache-2.0`) end-to-end LLM evaluation and tracing platform from Comet built for logging high-volume agent traces and running LLM-as-a-judge context checks.



- **[Weights & Biases Weave (`wandb/weave`)](https://github.com)**  

  Open-source (`Apache-2.0`) lightweight Python/TypeScript toolkit for tracking inputs, retrieved context, nested tool calls, and evaluation scores across agent workflows.



- **[LLMLingua (`microsoft/LLMLingua`)](https://github.com)**  

  Open-source (`MIT`) prompt and context compression library from Microsoft Research achieving up to 20x token reduction with minimal performance loss on RAG and agent trajectories.



- **[Context7 MCP (`upstash/context7`)](https://github.com)**  

  Widely adopted open-source (`MIT`) Model Context Protocol (MCP) server that injects up-to-date, version-specific library documentation and code examples directly into coding agent prompts.



- **[Model Context Protocol (MCP) Servers (`modelcontextprotocol/servers`)](https://github.com)**  

  Official open-source (`MIT`) reference server ecosystem enabling AI agents to dynamically pull structured context from filesystems, Git, databases, and external APIs.



- **[DSPy (`stanfordnlp/dspy`)](https://github.com)**  

  Open-source (`MIT`) declarative framework from Stanford NLP for programmatically optimizing prompts, few-shot context examples, and retrieval pipelines via algorithmic compilers.



- **[Ragas (`explodinggradients/ragas`)](https://github.com)**  

  Open-source (`Apache-2.0`) evaluation framework specialized in measuring context precision, context recall, faithfulness, and answer relevance in RAG and agent pipelines.



- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)**  

  Open-source (`MIT`) CLI and library for testing prompt/context variations, comparing models side by side, and automating CI/CD regression checks.



### Additional Strong Open-Source Options



- **[Mem0 (`mem0ai/mem0`)](https://github.com)** and **[Graphiti (`getzep/graphiti`)](https://github.com)** for dynamic long-term memory and temporal knowledge-graph context engineering across agent sessions.

- **[Basic Memory (`basicmachines-co/basic-memory`)](https://github.com)** and **[thedotmack/claude-mem](https://github.com)** for local-first Markdown knowledge graphs and automated coding-agent session context persistence.

- **[Docling (`docling-project/docling`)](https://github.com)** and **[MarkItDown (`microsoft/markitdown`)](https://github.com)** for converting PDFs, Office docs, and HTML into clean, LLM-ready Markdown context.

- **[Chonkie (`chonkie-inc/chonkie`)](https://github.com)** and **[Tree-sitter (`tree-sitter/tree-sitter`)](https://github.com)** for fast semantic text chunking and AST-aware code context extraction.

- **[Agenta (`Agenta-AI/agenta`)](https://github.com)** for an open-source LLMOps playground and prompt/context management suite with human annotation workflows.



**Frameworks for building custom systems**: Combine **bowenliang123/dsh-context** or **Repomix + Context7 MCP** (for codebase & documentation context packing) with **LLMLingua** (context compression), **DSPy** (prompt/context optimization), and **Langfuse / Arize Phoenix + Ragas** (observability & context evaluation) for sovereign, high-signal AI context engineering pipelines.



## How to Contribute



1. Fork the repo.
