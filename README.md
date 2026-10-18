# izzzi · AI Growth Operator

I build AI systems, automations and agents that run real marketing, operations and support work: memory for agents, routines that watch themselves, and tools that keep a human in the loop wherever money or customers are involved. Most of what I build is private client or employer work, so this page describes the projects and links to what can be shown publicly. All results are stated as relative changes, never as company figures.

## Featured: Growth OS

**Growth OS** is my main project. It is the marketing memory and operating rhythm of an AI operator: per brand, agents read and update avatars, angles, concepts, winning ads and learnings. The core is packaged as an anonymised framework that installs in two commands, with a knowledge base, 22 agent skills, four business models (D2C, B2B SaaS, B2B services, solo), a weekly rhythm, a Notion blueprint and a privacy layer that runs on local models.

It grew out of **Cockpit**, its predecessor: an operations system for my own creative and performance agency, with a Next.js dashboard, n8n workflows, five Telegram bots and two cooperating AI agents (one local, one on a VPS). Cockpit taught me what breaks in production. Growth OS is the cleaner, portable answer.

Every project in clusters 1 to 3 was built with this method and is documented in a dated evidence log (65 entries since September 2026), including the failures.

## Clusters

### 1. AI customer support and a custom ticketing system
- **Custom AI ticketing system** for a D2C support team: a local model classifies requests, drafts answers from order facts, and a review tool hands every draft to a human before anything is sent. Roughly doubled the share of first level requests that are fully resolved, measured by replaying stored runs. Currently in shadow mode.
- **Read-only MCP server for an in-house order system**: replaced three separate, partly unprotected access paths with one logged, read-only route used by every AI tool. Around seventy attack attempts, no breach.
- **Support and returns analysis**: showed that follow-ups hurt satisfaction far more than waiting time, and traced return spikes and recurring tickets back to fixable causes.

### 2. Routines and operations
- **Operations OS**: registry, run logs and a dashboard for every routine, a cost counter for AI calls, self-diagnosis and a documentation watchdog.
- **Mail assistant** on a local model: pre-sorts about nine in ten emails, writes replies only as drafts and refuses to forward suspicious invoices.
- **Meeting commitments from transcripts** instead of AI summaries.
- **Atlas**: a weekly planning agent on Telegram with calendar sync and voice notes.

### 3. Performance marketing and data
- **Ad account audits** with fixed definitions, plus a creative test database with decision rules set before launch.
- **Tracking and attribution**: cross-checked four tracking sources and measured click ID coverage, which moved tracking ahead of support automation on the roadmap.
- **Unit economics**: derived customer value and a verifiable cost cap per order from raw data.
- **Content Mate Autoresearch**: a shorts pipeline that rewrites its own script prompt every day from real view data.
- **n8n workflows** for Meta Ads sync and AI ad analysis.

### 4. Creative production and video
- **Creative Engine**: a Python toolchain for AI ad creatives, plus a pipeline dashboard built in three days.
- **Creator App** (MVP): upload takes, transcribe, let the model propose a cut, render on a serverless worker.
- **OpenCut and OpenReel forks**: browser video editors I integrated into my dashboard, with a caption editor, word level Whisper timing, colour grading, EDL based auto assembly and an MCP server so agents can edit the timeline. Live: [opencut-zeko.vercel.app](https://opencut-zeko.vercel.app), [openreel-zeko.vercel.app](https://openreel-zeko.vercel.app)
- **CaptionWipe**: serverless GPU worker (built on ProPainter and RunPod) that removes burned-in captions from video. Open source: [propainter-runpod-worker](https://github.com/izzzi43/propainter-runpod-worker)

### 5. E-commerce, product tests and sourcing
- **Product test app for Shopify**: replaces loose survey links with questionnaires tied to product and order, an EU backend, GDPR deletion and per product scores. Built, pilot pending.
- **Shopify theme work**: localisation and branding for D2C stores.
- **SourcePilot and ThriftPilot**: early agents for sourcing on 1688 and reselling on Vinted (prototypes).

### 6. Agent infrastructure and team enablement
- **AI Vault OS**: a memory system for coding agents in plain Markdown. Open source: [ai-vault-os](https://github.com/izzzi43/ai-vault-os)
- **Skills**: my working methods as Claude skills, with backups, weekly upkeep and security checks for third party skills.
- **AI onboarding for a team**: a cloneable workspace and onboarding that starts with a guided first real task.
- **QuickWhisper**: push to talk dictation for macOS.

### Learning curve
I keep failures in the same log as wins. One example: an AI routine reported work it had not done, so I replaced it with a plain script and now let code collect facts while the model only writes. Another: an invoice forwarder passed every test and still had a fraud gap, found by an independent review and closed the same day.

## How I work
Shadow mode before going live. Regression tests on real runs. A human approves anything that touches money or customers. Sensitive text stays on local models. Results get measured honestly, and when a number is not measured yet, I say so.

## Stack
Claude Code and MCP, Anthropic, OpenAI and Gemini APIs, Ollama, n8n, TypeScript, Next.js, React, Supabase, Python, Shopify, Docker, RunPod, Modal, Vercel, GitHub Actions.

*Detailed evidence for each project is available on request.*
