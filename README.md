### Hi, I'm Josh 👋

I'm an **AI Solutions Architect** — an enterprise systems specialist (12 years in mission-critical SAP & data operations) who turns hard problems into shipped, AI-powered systems by designing rigorously and orchestrating AI agents to build them, under a disciplined, documented workflow.

In the past year I independently designed and shipped **three production-grade systems** across three very different domains — using the same multi-agent methodology each time. Two of them put **production AI to work where most enterprises are still stuck at the demo stage** — with real, governed ROI.

---

#### 🚀 What I've built

**MonLite — Enterprise Observability Platform**
A full-stack platform monitoring SAP, six database engines, hosts, and web services — engineered to replace a seven-figure commercial monitoring contract. Python/FastAPI control plane, distributed collector agents, a React 19 UI, SSO/RBAC, and ~5s HA failover. Scale-tested to handle 3,000+ systems and 200+ concurrent users.
> 🌙 **Luna** — its embedded AI diagnostic assistant — runs **fully air-gapped on a local LLM** so telemetry never leaves the firewall (with optional cloud fallback). RAG pipeline, 100+ diagnostic tools, live database querying, and anti-hallucination validation turn raw infrastructure telemetry into natural-language root-cause analysis. This is enterprise AI that ships *and* satisfies security.

**Pathfinder — AI-Augmented SAP Migration Engine**
A decision-support platform that turns static migration playbooks into tailored, interactive SAP-to-cloud (AWS / Azure / GCP / RISE) plans — driven by a multi-LLM authoring engine and a cumulative-intelligence loop that gets smarter with every migration.

**Disaster Scenario — Cross-Platform Game** *(independent project)*
A comedic multiplayer deckbuilder for Steam & mobile, built in Godot 4 — ~39k lines of GDScript, a deterministic unit-tested core, and online multiplayer over ENet. Proof the method travels well beyond enterprise software.

---

#### 🤖 The method: a multi-agent "Conductor" workflow

The thing I'm most known for isn't any single app — it's *how* I build. I developed a repeatable methodology for production engineering with AI agents: a **Conductor** orchestrates parallel sub-agents in isolated git worktrees with bounded file scopes and manifest-driven task state, all governed by **living documentation** (architecture decision records, engineering standards, dependency maps, durable "memory" of gotchas, and per-session handoffs — 330+ on MonLite alone) and **human-approved quality gates** (no partial fixes, pre-merge verification, automated test/lint/security checks).

It's deliberately **tool-agnostic** — I direct Claude, OpenAI Codex, Gemini, and Grok, plus generative pipelines (Meshy, Scenario) and a persistent ops agent (OpenClaw), assigning each to the work it does best:
- *In Disaster Scenario:* Claude writes asset briefs that Codex executes, then Claude renders them into game-ready 3D/2D through Meshy and Scenario — covering the image/video generation that a single model can't.
- *In MonLite:* a lab-resident OpenClaw agent runs alongside live SAP systems and databases (WSL home server), executing diagnostics and commands across systems, DBs, and collectors and coordinating with Claude on R&D.

→ **[The full methodology + templates: agentic-dev-kit](https://github.com/josh-lans/agentic-dev-kit)**

---

#### 🔗 Explore the work

- **[Portfolio](https://github.com/josh-lans/portfolio)** — all three projects, with MonLite architecture & screenshots
- **[agentic-dev-kit](https://github.com/josh-lans/agentic-dev-kit)** — the methodology and drop-in `.claude-docs` templates
- **[Disaster Scenario](https://github.com/josh-lans/disaster-scenario-game)** — the game showcase & gallery (real screenshots)

---

#### 🛠 Stacks I deliver on *(via AI-assisted development)*

`Python` `FastAPI` `React 19` `TypeScript` `PostgreSQL` `Elasticsearch` `LLM / RAG` `Multi-provider AI` `Docker` `GitHub Actions` `SAP NetWeaver / HANA` `Oracle` `SQL Server` `Godot`

---

#### 📫 Get in touch

**joshlans@me.com** · **[LinkedIn](https://www.linkedin.com/in/joshualans/)**
