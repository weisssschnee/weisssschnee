# Yahao Li

**AI Engineer — Agent Systems & Evaluation**

Production Agent Platforms · Multi-Agent Systems · Agent Harness & Evaluation · Context & Runtime · MCP

I build production Agent systems that can execute across real tools, machines, browsers, accounts, and long-running workflows — with explicit authority boundaries, durable recovery, and verifiable external actions.

I currently work at **Shenzhen Chengbo Technology Co., Ltd.** as an **AI Agent / Applied AI Systems Engineer with technical-lead responsibilities**. My work spans the Agent execution foundation, Multi-Agent coordination, evaluation / Harness systems, context-runtime infrastructure, and production Applied AI.

## What I build

### Production Agent Platforms

- Cross-node execution across cloud services, Windows workstations, and dedicated compute nodes.
- Capability, identity, and authority boundaries around MCP and tool execution.
- Durable jobs, browser/account state, file verification, recovery, and auditable handoff.
- External actions accepted through platform readback / receipts rather than UI-click assumptions.

### Multi-Agent Systems

- Mission Control for task requests, commitments, ownership, and responsibility state.
- Human → Coordinating Agent → Messaging Agent → Execution Agent workflows.
- Shared MCP capabilities instead of duplicating a second mandatory planning layer.
- Formal acceptance on the current collaboration layer reached **346 tests passed / 1 skipped**.

### Agent Evaluation & Self-Improvement

I care about a distinction that is easy to lose in Agent engineering:

> **Run completed ≠ outcome accepted ≠ capability improved.**

My current Harness work turns real failures into replayable evidence and separates execution success from actual capability gains. The evaluation corpus spans **16 experiment classes** and **41 real or sanitizable failure fixtures**, covering false completion, recoverable execution, external side effects, handoff, coverage gaps, blocking decisions, and regression behavior.

The production self-improvement loop is deliberately controlled:

**failure evidence → typed diagnosis → focused patch → independent replay → regression / held-out evaluation → capability promotion**

### Context & Runtime

- Task-scoped project retrieval and capability routing.
- Deferred tool / skill disclosure to reduce fixed context cost.
- Long-running recovery so computation can survive model or connector interruption.
- Browser, file, remote-node, and runtime state treated as first-class execution state.

## Applied AI Systems

The same Agent infrastructure is used in production workflows including customer service, advertising operations, business data, employee AI, content production, and controlled external publishing.

My focus is not “an LLM that can click buttons.” It is building the execution, evidence, recovery, and authority layers that make Agent behavior usable in real systems.

## Quantitative Research — Separate Track

I also maintain an independent quantitative-research track focused on point-in-time research infrastructure, reproducibility, evidence boundaries, Alpha search, and leakage-safe evaluation.

I keep this track conceptually separate from my primary **Agent Systems / Applied AI** professional identity.

## Stack

**Agent Systems:** Multi-Agent Systems, Mission Control, MCP, Agent Harness / Evaluation, Context & Runtime, Identity / Authority / Recovery

**Backend / Infra:** Python, FastAPI, Asyncio, WebSocket, OAuth, SSH / Reverse SSH, Windows, Linux

**Automation / Data:** Playwright / CDP, Windows UIAutomation, SQLite, PostgreSQL / MySQL, Pandas, NumPy

**AI / ML:** LLM, RAG, PyTorch, LoRA / QLoRA, hybrid retrieval / reranking

## Selected Public Work

- [openapi-to-skills](https://github.com/weisssschnee/openapi-to-skills) — OpenAPI → Agent Skill tooling for context-efficient agents.
- [FinRAG-Agent-Docker](https://github.com/weisssschnee/FinRAG-Agent-Docker) — Dockerized financial RAG Agent.
- [QuantFactorLab](https://github.com/weisssschnee/QuantFactorLab) — quantitative research / AlphaGPT import.
- [alpha-pit-engine-v2](https://github.com/weisssschnee/alpha-pit-engine-v2) — point-in-time Alpha research infrastructure.

## Education

**M.Sc. in Computer Science**, Hong Kong Metropolitan University  
**B.Sc. in Marine Technology**, Guangdong Ocean University

## Contact

- [LinkedIn](https://www.linkedin.com/in/%E4%BA%9A%E8%B1%AA-%E6%9D%8E-328814341/)

