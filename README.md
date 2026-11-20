<div align="center">

<p>
  <a href="https://nouraldeentofi.com"><img src="./assets/web.svg" height="38" alt="Website"/></a>
  <a href="https://www.linkedin.com/in/nouraldeentofi"><img src="./assets/linkedin.svg" height="38" alt="LinkedIn"/></a>
  <a href="https://www.youtube.com/@nouraldeentofi"><img src="./assets/youtube.svg" height="38" alt="YouTube"/></a>
  <a href="mailto:nouraldeentofi@gmail.com"><img src="./assets/email.svg" height="38" alt="Email"/></a>
</p>

<img src="./assets/rule.svg" width="100%" alt=""/>

</div>

I'm a frontend and AI engineer in Al Khobar, Saudi Arabia: I build the interface people use and the AI behind it, in Arabic and English. The interfaces are React and TypeScript; the AI is agents that act through tools under strict rules, and document extraction that is checked before anything is saved, mostly on n8n.

My edge is **Arabic document AI**. Smart Scanner turns a photo of an invoice into 70+ checked fields in about 10 seconds, handwritten Arabic included, and CV Screener only counts an AI score once the server has found its quote in the CV.

My last full-time role was almost two years at DFS in Al Khobar, as a **frontend developer and project coordinator**: I built the React frontend of the company's CRM and quotation platform, and coordinated requirements and API contracts between frontend, backend and design.

### What I've built

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[Smart Scanner](https://nouraldeentofi.com/en/projects/smart-scanner)** | Arabic-first AI invoice product, in private beta. I built the AI extraction engine in n8n and the complete frontend (3 role-based apps, 494 tests); a teammate built the Laravel backend. A file that isn't a genuine invoice is rejected before anything is saved, every file is checked for duplicates and signs of fraud (SHA-256, perceptual hashing, EXIF), and reading text PDFs with a text model first cut the AI cost per document by about 75%. | `n8n` `GPT-4.1 Vision` `React 19` `TypeScript` |
| **[CV Screener](https://cv-screener.nouraldeentofi.com)** | Built alone, live. Every AI score must quote the CV, and the server verifies the quote before the score counts; weighted totals and must-have caps are computed in code. CV text is fenced, so instructions hidden in a CV are read as data. 1,189 tests, performance-tested on 5,000 CVs. | `Next.js` `n8n` `OpenAI` `Prisma` `MySQL` |
| **[Gambit Tournaments](https://gambit.nouraldeentofi.com/en)** | Tournament platform of a chess club in Dammam: live seats, guest registration in Arabic, English and Urdu, an admin dashboard, and an n8n payment check in which a vision model reads each bank-transfer receipt, so no one opens one by hand. | `Next.js` `React` `Prisma` `MySQL` `n8n` |
| **[Teacher Assistant AI Bot](https://nouraldeentofi.com/en/automation/teacher-assistant-bot)** | Arabic Telegram agent, live for a private tutor since June 2026: students, schedules, recurring lessons, cancellations and dues, all through chat. The model acts only through custom tools under strict business rules, with MySQL stored procedures as tools. | `n8n` `OpenAI` `MySQL` `Telegram` |
| **[MCP servers](https://nouraldeentofi.com/en/projects/mcp-search-server)** | An MCP server with custom tools over real data, connected to Claude, and the [MCP server](https://nouraldeentofi.com/mcp/README.md) that ships with my website. | `MCP` `Node.js` `JSON Schema` |
| **[Universal Web Scraper](https://nouraldeentofi.com/en/projects/universal-web-scraper)** | One link in, the whole site out: every page found, the data sorted into 7 categories, one Excel tab each. It reads JSON-LD and tables first and calls a model only when it must. | `n8n` `OpenAI` `Google Sheets` |
| **DFS CRM and quotation platform** | The React frontend of the platform the whole company moved onto (2025 to 2026): enquiries, quotations and follow-up, roles and sales analytics. Quotation preparation fell to under 2 minutes once the data is entered, and all 15 employees adopted it. I also developed the frontend of a second CRM for WAIS, DFS's parent company. | `React 19` `TypeScript` `Tailwind v4` `TanStack Query` |
| **[Nour Motion Studio](https://nouraldeentofi.com/motion-studio/)** | A motion-graphics video editor in the browser: 318 templates, 349 transitions, 217 backgrounds and 85 camera moves, exported to MP4 with no server and no account. | `JavaScript` `Canvas` `WebCodecs` |
| **[The Complete Umrah Guide](https://nouraldeentofi.com/umrah-guide/)** | Offline PWA in one HTML file: 35 steps, 10 languages, text-to-speech. | `PWA` `Web Speech API` |
| **[GoldenTag](https://nouraldeentofi.com/en/projects/goldentag)** | Jewelry-store management app the team built in Flutter and released on Google Play. I coordinated its delivery from requirements to release; adopted by 3 gold shops. | `Flutter` `Delivery` |

At university: a plant-health assistant on a VGG16-based CNN (TensorFlow/Keras, 2023), and a nutrition recommender built on an ensemble of 5 classifiers (2024).

**How I work:** plain code where the result must be exact, a model only where it adds something, and a person approving anything that can't be undone. Between two systems, the data contract is agreed in writing before the first line of code.

### Ask me about

- Getting an LLM to read Arabic documents reliably. The model is not the hard part.
- Making model output checkable: quoted evidence, totals computed in code, a refusal when a required field is missing.
- n8n in production: retries, error handling, cost control, and when to stop using it.
- Working with Claude Code every day: skills, MCP, and where a human must still sign off.

<img src="./assets/rule.svg" width="100%" alt=""/>

### The website experiment

My portfolio is built for humans **and** AI agents. Every fact on it is machine-readable.

<div align="center">

[`nouraldeentofi.com`](https://nouraldeentofi.com) &nbsp;·&nbsp; [`/llms.txt`](https://nouraldeentofi.com/llms.txt) &nbsp;·&nbsp; [`/api/profile.json`](https://nouraldeentofi.com/api/profile.json) &nbsp;·&nbsp; [`/mcp`](https://nouraldeentofi.com/mcp/README.md)

</div>

Ask ChatGPT or Claude *"Who is Nour Aldeen Tofi?"* and see what happens.

<img src="./assets/rule.svg" width="100%" alt=""/>

### Stack

- **AI engineering:** OpenAI API (GPT-4.1, GPT-4o) · Claude (MCP, Claude Code) · tool calling · structured JSON outputs · MCP · document AI and Arabic OCR · cost-aware model routing
- **Automation:** n8n (self-hosted with Docker) · webhooks · REST APIs · Telegram Bot API · Google Sheets and Drive APIs
- **Frontend:** React 19 · TypeScript · Next.js · Tailwind CSS · Vite · TanStack Query · i18n and RTL
- **Data, testing and delivery:** Node.js · Prisma · MySQL · Vitest · Playwright · GitHub Actions · Docker · Cloudflare
- **At university:** Python (pandas, TensorFlow/Keras)

I use Claude Code every day to plan, build, test and review.

### Contribution activity

<div align="center">

<img src="https://raw.githubusercontent.com/nouraldeentofi/nouraldeentofi/output/snake.svg" width="100%" alt="Contribution graph"/>

<br/><br/>

<img src="./assets/rule.svg" width="100%" alt=""/>

<b>Building something on large language models that has to work in Arabic?</b><br/>
<a href="https://www.linkedin.com/in/nouraldeentofi">Message me on LinkedIn</a> or email <a href="mailto:nouraldeentofi@gmail.com">nouraldeentofi@gmail.com</a><br/>
Open to AI engineering, AI automation and frontend roles and projects, in Saudi Arabia or remote.

</div>
