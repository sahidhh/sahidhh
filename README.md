<h1 align="center">Sahidh</h1>
<p align="center"><b>AI-oriented full-stack developer · TypeScript / React / Node / Python · Chennai, India</b></p>
<p align="center">
  <a href="https://linkedin.com/in/sahidh-h">LinkedIn</a> ·
  <a href="mailto:sahidhullah@gmail.com">Email</a> ·
  <a href="https://freelance-radar-five.vercel.app">Freelance Radar</a> ·
  <a href="https://job-scraper-liart.vercel.app">Job Scraper</a>
</p>

I build full-stack products where an LLM is a component, not the product — and I'm careful about *where* it earns its place. Recent work:

- **Agentic harness tooling** — a zero-LLM prompt classifier that routes model, thinking level, tool-set and rules per profile inside the Pi/OMP coding agent, plus a benchmark that measures whether a profile actually changes engineering behaviour (cost, scope, quality).
- **AI scoring pipelines** — scheduled scrapers that pull structured data from job boards, gate it with cheap keyword filters, then hand only the survivors to an LLM scorer and deliver a Telegram digest.
- **Scheduled agent runs** — web-search/scrape agents that return structured data on a cron, feeding keyless job feeds into a local-first CRM.
- **Document-AI POC** — OCR-backed word-level PDF diff with a text-layer fast path and Tesseract fallback for scanned pages.

Bias toward local-first, keyless, and cheap-to-run. If it can be a keyword match instead of an API call, it is.

---

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[Job Scraper](https://github.com/sahidhh/job-scraper)** · [live](https://job-scraper-liart.vercel.app) | Self-hosted job discovery engine. Scrapes Greenhouse, Lever, Ashby, Wellfound, RemoteOK & MyCareersFuture on a GitHub Actions cron, filters by geography, runs a two-stage keyword → LLM scoring pipeline, and pushes a Telegram digest with inline Apply buttons. Dashboard shows skill gaps and demand analytics. | TypeScript, Next.js, Postgres (Supabase), GitHub Actions, OpenRouter, Telegram Bot API |
| **[Freelance Radar](https://github.com/sahidhh/freelance-radar)** · [live](https://freelance-radar-five.vercel.app) | Local-first freelance lead CRM. Discover page aggregates keyless job feeds; leads, notes and pipeline live entirely in IndexedDB — no backend, no account. Mobile-first UI. | React, TypeScript, Vite, IndexedDB |
| **[LinkedIn AI Reply](https://github.com/sahidhh/LinkedIn-AI-Reply-Extension)** | Chrome extension that adds an AI reply button to LinkedIn messaging. Describe the reply, insert it. Bring-your-own-key (OpenRouter / Gemini). | TypeScript, Plasmo, Chrome Extensions API |
| **[profile-router](https://github.com/sahidhh/profile-router)** | Extension for the OMP coding agent that classifies every prompt with zero-LLM keyword scoring, then routes model, thinking level, tool-set and system-prompt rules per profile. | TypeScript |
| **[claudehat](https://github.com/sahidhh/claudehat)** | Cross-platform CLI to manage multiple Claude Code profiles (settings, MCP servers, skills) and switch between them. | CLI |
| **[pdf-diff-tool](https://github.com/sahidhh/pdf-diff-tool)** | Side-by-side word-level PDF diff in the browser. PyMuPDF for text layers, Tesseract OCR fallback for scanned pages. Runs in memory, nothing written to disk. | Python, FastAPI, PyMuPDF, Tesseract |
| **[benchmark](https://github.com/sahidhh/benchmark)** | Workflow benchmark for AI engineering profiles — same model, same task, different profile; records tokens, cost, latency and scope adherence. | Python, OpenRouter |
| **[Hub / Learning Cards](https://github.com/sahidhh/learning-card-generator)** · [live](https://learning-card-generator.vercel.app) | Mobile-first Next.js control center hosting mini-apps; Learning Cards turns a JSON feed into swipeable cards with PNG/PDF/MD export and Supabase persistence. | Next.js, Supabase |

---

## Stack

**Languages** — TypeScript, JavaScript, Python, SQL
**Frontend** — React, Next.js, Vite, Tailwind, IndexedDB / local-first patterns
**Backend** — Node, Express, FastAPI, Postgres / Supabase, MongoDB
**AI engineering** — LLM scoring pipelines, two-stage (heuristic → LLM) gating, agent routing & tool-set control (Pi/OMP), MCP, Claude Code, OpenRouter / Gemini, eval harnesses, OCR (Tesseract, PyMuPDF)
**Infra** — GitHub Actions, Vercel, Docker, Chrome Extensions (Plasmo)

---

## How I work

- Ship the smallest thing that works, then measure. Several repos carry written adversarial reviews of my own plans before building.
- LLM calls are the expensive last stage, never the first. Heuristics gate; the model decides only what heuristics can't.
- Prefer keyless / free-tier / local-first designs so tools keep running at zero cost.
- Automate the boring loop: cron scrapers, scheduled agent runs, Telegram digests, CLI profile switching.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sahidhh&show_icons=true&hide_border=true&hide_title=true&include_all_commits=true&count_private=true" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahidhh&layout=compact&hide_border=true" height="150" alt="languages" />
</p>

<p align="center">Open to AI-oriented full-stack / AI engineering / developer-tooling roles — remote or Chennai. <a href="mailto:sahidhullah@gmail.com">Let's talk.</a></p>
