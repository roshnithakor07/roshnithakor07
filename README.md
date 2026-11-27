<div align="center">

<a href="https://roshnithakor07.github.io">
  <img src="assets/header.svg" alt="Hi there! I'm Roshni Thakor, a Full Stack Developer who builds systems behind the screen" width="100%" />
</a>

<p>
  <a href="https://roshnithakor07.github.io"><img src="https://img.shields.io/badge/Portfolio-roshnithakor07.github.io-0E7490?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/roshnithakor07"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:roshni.thakor.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.hackerrank.com/profile/roshnithakor07"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank" /></a>
  <a href="https://leetcode.com/roshnithakor07"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
</p>

</div>

<img src="assets/terminal.svg" alt="Terminal: whoami --json returns Roshni Thakor, Full Stack Developer, 3.9 years in production, open to backend and full stack roles" width="100%" />

> This profile works like my [portfolio](https://roshnithakor07.github.io): one request, traced through the systems I've built. Each section below is an endpoint.

---

### 💼 `GET /experience` &nbsp;·&nbsp; `200 OK`

| When | Role | What I shipped |
|:--|:--|:--|
| **Sep 2026 - Nov 2026** | Backend Engineer · [Shree Maruti](https://shreemaruti.com/) (via Kanhasoft) | **Smile HRMS**, a multi-tenant HR platform: Leave Management end to end, Expenses with S3 signed-URL receipts, org-scoped JWT + RBAC, **242+ unit tests** |
| **Sep 2022 - Jun 2026** | Software Developer · [Eventus Security](https://eventussecurity.com/) | SOC analytics over **hundreds of millions of records** for India's regional power grid, an AI code reviewer the team used daily, and a report engine that turned **20 hours into 1** |
| **Sep 2021 - May 2022** | Web Development Intern · [Flu Social](https://flusocial.com/) · [LetsGrowMore](https://letsgrowmore.in/) | Client sites and full-stack features alongside my degree |

---

### 🧪 `GET /projects` &nbsp;·&nbsp; `200 OK`

**At work** &nbsp;<sub>(internal products, so the code isn't public; the full stories are on my [portfolio](https://roshnithakor07.github.io/#projects))</sub>

| Project | The problem → what I built | Result |
|:--|:--|:--|
| 🔍 **DevLens** | Manual PR reviews were slow and inconsistent → AI code review on the Claude API, scoped to changed Git hunks, with **streaming** responses and NestJS-Guard RBAC | Perceived latency **~8 s → < 1 s**; used daily |
| 🛡️ **ESDL Dashboard** | Customers relied on external security tools → a real-time SOC/EDR dashboard; rewrote pagination, moved heavy work into aggregation pipelines, Redis caching, optimised ClickHouse queries | Faster, scalable dashboards over **100M+ records** |
| ⚙️ **Health Check Automation** | 16-20 hours of manual reporting → upload Excel, get 27 charts and a formatted PDF + Word report; RBAC, 2FA OTP, hardened APIs | **16-20 h → < 1 h**, fully adopted |

**On my own**

| Project | What it does | Built with | Links |
|:--|:--|:--|:--|
| 📮 **Reqway** | Postman-style API client: proxy engine, collections, environments, auth, history, code snippets | React · Express · MongoDB · JWT | [Repo](https://github.com/roshnithakor07/coderepo-react-node-postman) |
| 🎫 **Support Desk** | Ticketing with agent teams, SLA tracking and breach alerts, merge and bulk actions; **40 product rules, 132 tests** | React · Express · MongoDB · JWT | [Repo](https://github.com/roshnithakor07/coderepo-react-node-support-desk) · [Video](https://drive.google.com/file/d/1TzRcNZNis5zJPfZPnjUlP-kVZ_yzQ-8h/view) |
| 📝 **QuizCraft** | Up to 200 quiz questions from text or images in 24 languages, PDF/Word export | Next.js 14 · Groq · MongoDB | [Live](https://quizcraft-mauve.vercel.app/) · [Repo](https://github.com/roshnithakor07/quizcraft) |
| ⚡ **QuickLink** | URL shortener: Redis cache-aside (**~120 ms → ~4 ms**), sliding-window rate limits, click analytics | TypeScript · Express · MongoDB · Redis | [Repo](https://github.com/roshnithakor07/quicklink) |
| 📅 **Calendly API** | Timezone-aware availability, race-safe booking in PostgreSQL transactions, Temporal workflows for emails and Google Calendar sync | TypeScript · Express · PostgreSQL · Prisma · Temporal | [Repo](https://github.com/roshnithakor07/calendly) |
| 📊 **ComplexityIQ** | Big-O analyser for 9 languages with best/average/worst breakdown and auto-refactor | Next.js 14 · Groq · SVG | [Repo](https://github.com/roshnithakor07/complexity-iq) |
| 💸 **PayFlow** | Atomic wallet transfers with MongoDB transactions, idempotency, HMAC-signed webhooks | TypeScript · MongoDB | [Repo](https://github.com/roshnithakor07/payflow) |
| 🗄️ **FileVault** | Secure file storage with S3 presigned uploads, Redis storage quotas and RBAC | Node.js · AWS S3 · Redis | [Repo](https://github.com/roshnithakor07/FileVault) |

---

### 🏆 `GET /awards` &nbsp;·&nbsp; `200 OK`

- 🥇 **Top 3.4%** · #139 of 4,094 · HackerRank Orchestrate, Oct 2026: an AI agent pipeline that finds ghost data left behind after deletion · [leaderboard](https://www.hackerrank.com/contests/hackerrank-orchestrate-october26/challenges/ghost-data-still-exists/leaderboard?username=roshnithakor07)
- 🥈 **Top 18.5%** · #367 of 1,983 · HackerRank Orchestrate, Aug 2026: a multimodal notification router on the Claude API (text, images, voice notes → notify / digest / mute) · [leaderboard](https://www.hackerrank.com/contests/hackerrank-orchestrate-august26/challenges/message-notification-router/leaderboard?username=roshnithakor07)
- 🥉 **Top 26%** · #460 of 1,773 · HackerRank Orchestrate, Jun 2026: multimodal insurance-claim verification with vision-language models · [repo](https://github.com/roshnithakor07/multimodal-damage-claim-verification)
- 🎓 **B.E. Information Technology** · Saffrony Institute of Technology (GTU) · CGPA 9.0 / 10

---

### 🧰 `GET /stack` &nbsp;·&nbsp; `200 OK`

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,java,nodejs,nestjs,express,react,nextjs,tailwind&perline=10" alt="TypeScript, JavaScript, Python, Java, Node.js, NestJS, Express, React, Next.js, Tailwind" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,mysql,prisma,docker,aws,git,vercel&perline=9" alt="PostgreSQL, MongoDB, Redis, MySQL, Prisma, Docker, AWS, Git, Vercel" /><br/><br/>
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse" />
  <img src="https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white" alt="TypeORM" />
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Groq-F43E01?style=flat-square&logoColor=white" alt="Groq" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor" />
</p>

---

### 📊 `GET /stats` &nbsp;·&nbsp; `200 OK`

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=roshnithakor07&hide_border=true&background=FFFEF0&ring=0E7490&fire=0E7490&currStreakLabel=0E7490&sideLabels=1A1446&currStreakNum=1A1446&sideNums=1A1446&dates=5B6270&stroke=E1E1E1" height="165" alt="GitHub streak" />
</p>

<details>
<summary><b>☕ <code>GET /beyond-code</code></b></summary>

```yaml
currently_learning: [System Design, Advanced DSA, Docker & DevOps]
beyond_code:
  - 🎨 Painting & sketching
  - 🧘 Yoga & strength training every morning
  - 🌿 Spending time in nature
```

</details>

<div align="center">
<sub>Same notebook, same trace as my <a href="https://roshnithakor07.github.io">portfolio</a>. Say hi: <a href="mailto:roshni.thakor.dev@gmail.com">roshni.thakor.dev@gmail.com</a></sub><br/>
<img src="https://komarev.com/ghpvc/?username=roshnithakor07&label=profile+views&color=0e7490&style=flat-square" alt="profile views" />
</div>
