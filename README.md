# Ivana Plechacova

**Technical Product & Project Manager · Agentic / Python Developer**  
London, UK &nbsp;·&nbsp; [ivple@pm.me](mailto:ivple@pm.me) &nbsp;·&nbsp; [ivple.com](https://ivple.com)

---

I'm a technical product and project leader with 10+ years delivering complex technology programmes across infrastructure, telecom, and software. I pair that delivery track record with hands-on Python and Go development — I care about writing code that lasts, systems that fail gracefully, and teams that own their work.

Linux has been my primary environment since my early teens. I'm drawn to open source because the quality pressure is real: code that anyone can read is code that has to be good.

---

## What I build

| Project | Stack | Live |
|---|---|---|
| [**cloud-image-diff**](https://github.com/iv-ivple/cloud-image-diff) — CLI tool that fetches Ubuntu cloud image metadata from AWS, Azure, and GCP and compares them side by side; reports images missing on one provider and highlights differences in kernel version or build date across regions; uses concurrent SDK calls via `errgroup` and integrates the AWS EC2 SDK, Azure Compute SDK, and GCP Compute API | Go · Cobra · errgroup · AWS EC2 SDK · Azure Compute SDK · GCP Compute API | — |
| [**Wallet Watcher API**](https://github.com/iv-ivple/wallet-watcher-api) — Ethereum wallet monitoring REST API with analytics endpoints, Redis caching, PostgreSQL, background workers | Python · Flask · Redis · PostgreSQL · Docker | [↗](https://walletwatcher.ivple.com) |
| [**DEX Monitor**](https://github.com/iv-ivple/dex-monitor) — Real-time decentralised exchange price aggregator across multiple DEXs, with spread detection and arbitrage opportunity identification | Python · Flask · web3.py · Redis | [↗](https://dexmonitor.ivple.com) |
| [**Web3 Telegram Bot**](https://github.com/iv-ivple/web3-telegram-bot) — Blockchain analytics bot: wallet tracking, token analytics with auto-generated charts, GraphQL via The Graph, hybrid RPC/Subgraph data fetching | Python · web3.py · matplotlib · The Graph | — |
| [**PDF Label Extractor**](https://github.com/iv-ivple/pdf-label-extractor) — Production automation tool that extracts label and object counts from engineering drawings to automate procurement quantity take-offs; deployed and used daily by non-technical colleagues at MultiCAD | Python · Flask · pdfplumber | [↗](https://pdflabel.ivple.com) |
| [**Ethereum Dev Lab**](https://github.com/iv-ivple/ethereum-dev-lab) — 40-week documented learning journey from RPC basics through wallets, ERC-20, event indexing, SQL, testing, and production APIs; recent weeks cover async keeper bots, gas oracles, and an Aave V3 liquidation watcher with PostgreSQL persistence, APScheduler polling, and Discord webhook alerting | Python · web3.py · asyncio · pytest · SQLAlchemy · asyncpg · APScheduler | — |

---

## Self-hosted infrastructure

All the live apps above run on infrastructure I own and operate end to end. They were originally deployed on **Render** (managed hosting); in 2026 I migrated the portfolio onto a self-managed stack for cost optimisation and fuller control — a **Raspberry Pi 5** running **Docker** and **Coolify** (self-hosted PaaS), exposed to the internet through a **Cloudflare Tunnel** with no open ports, and administered remotely over a **Tailscale** mesh VPN. CI/CD auto-deploys on push via a GitHub App; daily integrity-verified backups and UptimeRobot monitoring run across every service — monitoring has already caught and logged a real incident.

Everything lives behind **[ivple.com](https://ivple.com)** — a static landing page served from Cloudflare's edge, so the front door stays up independently of the Pi, linking through to each app on its own subdomain.

---

## Stack

```
Languages    Python (primary) · Go · SQL · JavaScript
Backend      Flask · SQLAlchemy · REST APIs · web3.py · Cobra
Data         PostgreSQL · Redis · SQLite · pandas
Infra        Docker · Coolify · Cloudflare Tunnel · Tailscale · Raspberry Pi 5 · Render · Linux · GitHub Actions
AI/Agentic   Claude Code · Cursor · Hermes (NousResearch) · Ollama · local LLM inference
Tools        Git · pytest · Jira · Confluence
Learning     Kubernetes · agentic AI tooling · local LLM inference
```

---

## Background

My path into software engineering is unconventional — I started as an architect, which taught me something software teams often learn the hard way: **documentation is the product**. In BIM environments, every design decision has to survive handover to contractors and maintenance teams working on a system for decades. That shapes how I write READMEs, architecture notes, and runbooks.

Before that I led delivery of a £77M technology programme for the London Underground Piccadilly Line — a safety-critical OPO CCTV system with a hard 200ms glass-to-glass latency constraint across 55 live stations. That context — no tolerance for silent failures, no "we'll fix it later" — is what I carry into software.

My Python systems, Web3 integrations, and DevOps practices were all self-taught alongside full-time work. I'm a fast learner because I'm genuinely curious, and I build things that are actually deployed and used — not just committed.

---

## Currently

- 🚀 Building a **stealth SaaS product** — full-stack, solo, MVP shipping July
- 📚 Building in **Go** — interfaces, goroutines, multi-cloud SDK integrations
- 🔐 Working towards **CompTIA Security+**
- 🤖 Deepening **agentic AI and local LLM tooling** — Claude Code, Ollama, agent workflows
- 🌍 Interested in contributing to open source in the **Python / Go ecosystem**

---

## Principles I work by

- Observability from day one — if you can't measure it, you can't debug it
- Graceful degradation at every boundary — external dependencies will fail
- Documentation versioned with code — stale docs are worse than no docs
- Quality is a culture, not a phase

---

*Certified Scrum Master & Product Owner (Scrum Alliance) · AWS Cloud Technical Essentials · Kubernetes Fundamentals · MSc Architecture, Czech Technical University Prague*
