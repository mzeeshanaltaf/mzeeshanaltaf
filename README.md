<div align="center">

# Zeeshan Altaf

### AI Transformation Leader & Agentic AI Architect

Building autonomous AI systems, agentic workflows & intelligent automation at **[92labs.ai](https://zeeshanai.cloud)**

[![Portfolio](https://img.shields.io/badge/Portfolio-zeeshanai.cloud-d97757?style=for-the-badge&logo=googlechrome&logoColor=white)](https://zeeshanai.cloud)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zeeshan-altaf-4386a99)
[![X](https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Zeeshan3107)
[![Email](https://img.shields.io/badge/Email-hello%40zeeshanai.cloud-d97757?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@zeeshanai.cloud)

</div>

## About Me

I'm the founder of **[92labs.ai](https://zeeshanai.cloud)**, an Agentic AI & Automation Lab where I build AI-powered SaaS products, multi-agent workflows, RAG systems, and the runtime "harnesses" that make production AI agents reliable. Before that, I spent 20+ years in engineering leadership — most recently as **Director, Engineering Operations at Siemens Industry Software**, and before that across engineering management and operations roles at **Mentor Graphics Pakistan**. I'm a two-time **President of Pakistan IT Award** recipient (2020 & 2021) for contributions to software export and innovation.

Today I spend my time designing multi-agent systems, agent orchestration layers, and retrieval-augmented generation pipelines — and shipping them as real, live products.

## What I Do

| | |
|---|---|
| **Agentic AI Workflows** | Multi-agent systems that collaborate, reason, and execute complex tasks autonomously — orchestration, tool-use, memory & context management, human-in-the-loop patterns. |
| **Agent Harness Development** | The runtime infrastructure beneath AI agents — streaming tool-calling loops, multi-provider model registries, session persistence, auth & usage-based billing. |
| **Agentic RAG Systems** | Retrieval-augmented generation that intelligently searches, reasons over, and synthesizes knowledge bases — hybrid search, multi-document reasoning, citation tracking. |
| **AI-Powered SaaS Applications** | End-to-end LLM-powered products, from intelligent document processing to lead-generation funnels. |
| **Automation Workflows** | Event-driven automation pipelines connecting tools, APIs, and data sources to eliminate manual work. |

## Tech Stack

**AI & Orchestration**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral%20AI-FA520F?style=flat-square&logo=mistralai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Runtime**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Data & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=neon&logoColor=black)
![Upstash](https://img.shields.io/badge/Upstash-00E9A3?style=flat-square&logo=upstash&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Auth**
![Better Auth](https://img.shields.io/badge/Better%20Auth-000000?style=flat-square)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

## Flagship Agentic AI Projects

### ForgeCode — Terminal-Native AI Coding Agent
A full agent harness for a CLI coding assistant: a streaming tool-calling loop, a 7-tool toolbox (read/write/edit files, list directory, glob, grep, run shell), and runtime switching between OpenAI, Anthropic, and Google models. The server is stateless by design — it rebuilds context from persisted conversation history every turn, while the terminal client owns the filesystem and executes every tool locally. Includes a read-only "Plan" mode for safe research before code changes, persistent auto-titled sessions, and usage-based billing.

`TypeScript` `Bun` `Hono` `Prisma` `PostgreSQL` `Clerk` `Polar` `AI SDK`

[Repository →](https://github.com/mzeeshanaltaf/forgecode)

### Multi-Agent Slackbot — Cooperating Specialist Agents
Three specialized agents working in concert inside Slack: a Channel Bootstrap Agent, an Onboarding Agent, and a Knowledge Retrieval Agent — handling channel setup, automated new-hire onboarding, and project-specific knowledge lookups without manual intervention.

`LangChain` `n8n` `Vector DB` `Python` `Slack API`

### Qanoon — Agentic RAG Over Pakistan's Federal Statutes
Answers questions about 525 Pakistani federal statutes (6,487 pages) in plain language, grounded strictly in statute text. Hybrid retrieval fuses pgvector cosine search with Postgres full-text search via Reciprocal Rank Fusion; every answer cites the exact page of the source PDF. Includes precomputed per-act summaries, a per-user credit system, and an admin dashboard for in-app document ingestion.

`Next.js` `TypeScript` `pgvector` `PostgreSQL` `Better Auth` `Vercel AI SDK` `OpenAI`

[Live →](https://qanoon.zeeshanai.cloud/) · [Repository →](https://github.com/mzeeshanaltaf/pakistan-federal-laws)

### DocGenie — Multi-Format Document Q&A
Upload a PDF, DOCX, TXT, or CSV and chat with it. Eight n8n workflows handle ingestion, retrieval, chat, auto-titling, and credit metering across persistent, multi-session conversations, reasoning over documents with Claude.

`Next.js` `n8n` `Claude` `Better Auth`

[Live →](https://docgenie.zeeshanai.cloud/) · [Repository →](https://github.com/mzeeshanaltaf/docgenie-ai)

### SolarQuote — Bill-to-Solar Estimate Lead Funnel
Upload an electricity bill (any country, layout, or language) and get back a satellite-sized solar system estimate with a 25-year ROI projection. Mistral OCR extracts consumption and address data, an LLM structures it, and PVGIS/NASA POWER irradiance data drives the sizing — turning every visitor into a qualified lead.

`Next.js` `Prisma` `Neon` `Mistral OCR` `OpenAI` `Google Maps API`

[Live →](https://solarquote.zeeshanai.cloud/) · [Repository →](https://github.com/mzeeshanaltaf/solar-quote)

## More Projects

Beyond the agentic work above, I've shipped a range of AI-powered SaaS products — document processing, RAG, fitness planning, generative design, and more. Full case studies at **[zeeshanai.cloud/projects](https://zeeshanai.cloud/projects)**.

| Project | Description | Link |
|---|---|---|
| InvoiceExtract | Automated invoice data extraction (OCR + LLM) | [Live](https://invoicextract.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/invoice-extract) |
| ResuMatchAI | AI resume-to-job-description evaluator | [Live](https://resumatch.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/resume-match-ai) |
| FitFusion | Personalized AI fitness & nutrition planner | [Live](https://fitfusion.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/fit-fusion) |
| Greetify | AI-generated personalized greeting cards | [Live](https://greetify.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/greetify-ai) |
| TypeSprint | Adaptive AI-powered typing tutor | [Live](https://typesprint.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/typesprint) |
| ChargeMap PK | Pakistan's EV charging station discovery platform | [Live](https://chargemap-pk.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/ev-chargers-pk) |
| YouTube Analytics | No-signup analytics for YouTube creators | [Live](https://yt-analytics.zeeshanai.cloud/) · [Repo](https://github.com/mzeeshanaltaf/youtube-analytics) |

## Developer Utilities

Standalone tools I built to stop depending on third-party providers for everyday tasks — free, open source, and privacy-first where it matters.

| Tool | Description |
|---|---|
| **[Tokenizer](https://github.com/mzeeshanaltaf/tokenizer)** | LLM token counter |
| **[Markdown2PDF](https://github.com/mzeeshanaltaf/markdown2pdf)** | Markdown → PDF/HTML converter, runs entirely in-browser |
| **[DiffLab](https://github.com/mzeeshanaltaf/DiffLab)** | Web-based diff & comparison tool |
| **[Keyforge](https://github.com/mzeeshanaltaf/keyforge)** | UUID/GUID/password/API-key generator, entirely client-side via the Web Crypto API |

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mzeeshanaltaf&show_icons=true&count_private=true&hide_border=true&bg_color=1c1410&title_color=d97757&text_color=f5ede1&icon_color=d97757" alt="Zeeshan's GitHub stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mzeeshanaltaf&layout=compact&hide_border=true&bg_color=1c1410&title_color=d97757&text_color=f5ede1" alt="Top languages" width="38%" />

<img src="https://streak-stats.demolab.com/?user=mzeeshanaltaf&hide_border=true&background=1c1410&stroke=1c1410&ring=d97757&fire=d97757&currStreakLabel=f5ede1&sideNums=f5ede1&sideLabels=f5ede1&dates=8a7a68" alt="GitHub streak stats" width="90%" />

</div>

## Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-zeeshanai.cloud-d97757?style=for-the-badge&logo=googlechrome&logoColor=white)](https://zeeshanai.cloud)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zeeshan-altaf-4386a99)
[![X](https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Zeeshan3107)
[![Email](https://img.shields.io/badge/Email-hello%40zeeshanai.cloud-d97757?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@zeeshanai.cloud)

Open to conversations about agentic AI architecture, automation, and AI transformation.

</div>
