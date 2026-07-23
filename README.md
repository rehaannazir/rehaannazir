<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  REHAN NAZIR · AI Production Systems Engineer                  ║
  ║  Profile README — animated SVGs live in /assets (self-hosted). ║
  ║  Live-stat cards use standard community services (see note in  ║
  ║  the "Signals" section). Everything else is self-contained.    ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="assets/hero.svg" alt="Rehan Nazir — AI Production Systems Engineer" width="100%" />

<br/>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-0A0A0F?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0A0A0F)](https://rehan-portfolio-eight.vercel.app/)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A0A0F?style=for-the-badge&logo=linkedin&logoColor=5B8CFF&labelColor=0A0A0F)](https://www.linkedin.com/in/rehan-nazir-530597332)
&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-0A0A0F?style=for-the-badge&logo=gmail&logoColor=B96BFF&labelColor=0A0A0F)](mailto:rehaan689nazir@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GITHUB-0A0A0F?style=for-the-badge&logo=github&logoColor=white&labelColor=0A0A0F)](https://github.com/rehaannazir)

</div>

<img src="assets/divider.svg" width="100%" />

## `01` — Live Status

<div align="center">
<img src="assets/terminal.svg" alt="Live status" width="100%" />
</div>

<img src="assets/divider.svg" width="100%" />

## `02` — Engineering Philosophy

> **I build systems that run without me in the loop.**
>
> Models are commodities — reliability is not. My work lives at the boundary
> where an LLM stops being a demo and starts being infrastructure: typed
> outputs, retries, observability, and orchestration that survives real traffic.
>
> **Ship products, not certificates. Optimize for what reaches production.**

<img src="assets/divider.svg" width="100%" />

## `03` — What I Build

<table>
<tr>
<td width="33%" valign="top">

### 🤖 AI Agents
Autonomous, tool-using agents that plan, call APIs, and act — not chatbots.

</td>
<td width="33%" valign="top">

### 📚 RAG Systems
Retrieval pipelines over vector stores with grounded, cited answers.

</td>
<td width="33%" valign="top">

### ⚙️ Automation
End-to-end business workflows in n8n that remove repetitive human work.

</td>
</tr>
<tr>
<td valign="top">

### 🧠 LLM Applications
Structured-output apps with validation, batching, and cost control.

</td>
<td valign="top">

### 🚀 FastAPI Backends
Typed, authenticated, tested REST services built for scale.

</td>
<td valign="top">

### 🔁 AI Workflows
Multi-step agentic graphs orchestrated with LangGraph and tools.

</td>
</tr>
<tr>
<td valign="top" colspan="3">

### 🛰️ Production APIs
Instrumented services with logging, background tasks, and clean layered architecture.

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" />

## `04` — Featured Systems

<table>
<tr><td width="50%" valign="top">

### 🧩 AI Content Automation
`TypeScript` · `LLM APIs` · `Automation`

An automated content-generation pipeline that turns briefs into publish-ready
output with AI in the loop.

**Why it matters** — content ops is one of the highest-volume manual tasks in
any business; this replaces it with a repeatable system.

**Architecture** — brief → LLM generation → validation → structured export.

[**→ Repository**](https://github.com/rehaannazir/AI-Content-Automation)

</td><td width="50%" valign="top">

### 🔗 Lead Enrichment Automation
`n8n` · `Hunter API` · `Google Workspace` · `Slack`

End-to-end B2B lead pipeline: validation, enrichment, CRM dedup, 0–100
scoring, PDF generation, and automated sales follow-up.

**Why it matters** — collapses a multi-department sales process into one
autonomous workflow.

**Architecture** — intake → email verify → enrich → CRM check → score →
route → PDF → schedule + email.

[**→ Repository**](https://github.com/rehaannazir/Lead_Enrichment-Automation-n8n-)

</td></tr>
<tr><td valign="top">

### 💸 AI Finance Expense Categorizer
`Python` · `Gemini` · `Pydantic` · `pandas`

Categorizes bank transactions with Gemini, validates every result against a
Pydantic schema, and exports charted Excel reports.

**Why it matters** — demonstrates *reliable* LLM output: schema-enforced,
retried, and batch-safe.

**Architecture** — CSV → clean → Gemini categorize → validate → DataFrame →
Excel + charts.

[**→ Repository**](https://github.com/rehaannazir/AI-Finance-Expense-Categorizer)

</td><td valign="top">

### 🔐 FastAPI JWT Book Store
`FastAPI` · `SQLModel` · `JWT` · `Pytest`

Production-oriented REST API: JWT auth, ownership-scoped orders, file uploads,
middleware, logging, and a full test suite.

**Why it matters** — the backend blueprint every AI product needs underneath it.

**Architecture** — layered API / auth / business logic / data, with protected
routes and background tasks.

[**→ Repository**](https://github.com/rehaannazir/FastAPI-JWT-Book-Store)

</td></tr>
<tr><td valign="top">

### 🛠️ Gemini API Deep Dive
`Python` · `Google GenAI SDK` · `Pydantic`

A production-track reference for the Gemini API — structured output, function
calling, streaming, token control, and prompt engineering.

**Why it matters** — the foundation layer behind every agent and RAG system I ship.

**Architecture** — SDK → structured output → function calling → multi-tool workflows.

[**→ Repository**](https://github.com/rehaannazir/Gemini-API-Deep-Dive)

</td><td valign="top">

### 🧪 AI System Engineering
`Python` · `AI Systems`

A working sandbox for agentic patterns and production-AI system design —
where new orchestration ideas get prototyped before they ship.

**Why it matters** — the R&D bench that feeds the production work.

**Architecture** — modular Python components for agent and pipeline experiments.

[**→ Repository**](https://github.com/rehaannazir/AI-System-Engineering)

</td></tr>
</table>

<img src="assets/divider.svg" width="100%" />

## `05` — Tech Stack

<table>
<tr><td width="140"><b>AI / LLM</b></td><td>LangChain · LangGraph · RAG · Prompt Engineering · Function Calling · Gemini · OpenAI APIs</td></tr>
<tr><td><b>Backend</b></td><td>Python · FastAPI · SQLModel · Pydantic · REST · JWT Auth</td></tr>
<tr><td><b>Automation</b></td><td>n8n · Webhooks · Event Pipelines · API Orchestration</td></tr>
<tr><td><b>Data</b></td><td>pandas · NumPy · Matplotlib · Jupyter · openpyxl</td></tr>
<tr><td><b>Vector DB</b></td><td>Embeddings · Semantic Retrieval · Vector Search</td></tr>
<tr><td><b>Databases</b></td><td>SQL · SQLite · Airtable</td></tr>
<tr><td><b>Frontend</b></td><td>TypeScript · JavaScript · HTML · CSS</td></tr>
<tr><td><b>Deployment</b></td><td>Vercel · Git · GitHub Actions · Docker (learning)</td></tr>
<tr><td><b>Tools</b></td><td>Git · VS Code · Postman · Google Workspace</td></tr>
</table>

<img src="assets/divider.svg" width="100%" />

## `06` — System Architecture

<div align="center">
<img src="assets/architecture.svg" alt="AI system architecture" width="100%" />
</div>

<img src="assets/divider.svg" width="100%" />

## `07` — Signals

<!--
  These stat cards render live data and therefore depend on community
  services (github-readme-stats, streak-stats, komarev). They are the
  standard tools used across GitHub. If you prefer zero external
  dependencies, delete this section — everything else is self-hosted.
-->

<div align="center">

![Views](https://komarev.com/ghpvc/?username=rehaannazir&style=for-the-badge&color=B96BFF&label=PROFILE+VIEWS)
&nbsp;
![Followers](https://img.shields.io/github/followers/rehaannazir?style=for-the-badge&logo=github&color=5B8CFF&labelColor=0A0A0F&label=FOLLOWERS)

<br/><br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=rehaannazir&show_icons=true&hide_border=true&bg_color=0A0A0F&title_color=B96BFF&icon_color=5B8CFF&text_color=C8C8DA&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rehaannazir&layout=compact&hide_border=true&bg_color=0A0A0F&title_color=B96BFF&text_color=C8C8DA&langs_count=8" />

<br/><br/>

<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=rehaannazir&hide_border=true&background=0A0A0F&ring=B96BFF&fire=5B8CFF&currStreakNum=C8C8DA&sideNums=C8C8DA&currStreakLabel=B96BFF&sideLabels=8A8AA0&dates=5A5A72" />

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=rehaannazir&bg_color=0A0A0F&color=C8C8DA&line=B96BFF&point=5B8CFF&area=true&hide_border=true" />

</div>

<img src="assets/divider.svg" width="100%" />

## `08` — How I Ship

<div align="center">
<img src="assets/workflow.svg" alt="Development workflow" width="100%" />
</div>

<img src="assets/divider.svg" width="100%" />

## `09` — Roadmap

<div align="center">
<img src="assets/roadmap.svg" alt="Current roadmap" width="100%" />
</div>

<img src="assets/divider.svg" width="100%" />

## `10` — Open Source

- **Build in public.** Every system above ships with documentation and a clear architecture.
- **Reusable primitives.** Structured-output, agent, and RAG patterns extracted for reuse.
- **Goal.** Grow a set of production-grade AI building blocks under the **Nexara** banner.

<img src="assets/divider.svg" width="100%" />

## `11` — Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-5B8CFF?style=flat-square&logo=vercel&logoColor=white)](https://rehan-portfolio-eight.vercel.app/)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rehan-nazir-530597332)
&nbsp;
[![Email](https://img.shields.io/badge/Email-B96BFF?style=flat-square&logo=gmail&logoColor=white)](mailto:rehaan689nazir@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rehaannazir)
<!-- Calendly: add your booking link, then uncomment ↓
&nbsp;
[![Calendly](https://img.shields.io/badge/Book_a_call-22D3EE?style=flat-square&logo=calendly&logoColor=white)](https://calendly.com/YOUR-HANDLE)
-->

</div>

<img src="assets/footer.svg" width="100%" />
