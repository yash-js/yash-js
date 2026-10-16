# Hi, I'm Yash Purani

**Full Stack & AI Engineer** · Node.js · Python (FastAPI) · React / Next.js · LLMs & RAG

I build SaaS products end to end, from the Postgres schema to the AWS deploy, and I build the LLM features that sit inside them.

Most recently at **Zava AI** (UK, remote), I owned the whole stack of a business operations SaaS used by UK private clinics: database design, APIs, frontend, deployments, and the AI layer. The parts I'm proudest of:

- **AI email support agent** that searches a client's knowledge base (RAG) and drafts a reply to a customer query in about 30 seconds
- **Modular MCP server layer** so every third-party API plugs into the AI features the same way, which cut the integration work for each new client
- **Workflow detection prototype**: an Electron + React app with a local Python FastAPI service that records user activity, asks GPT-4o whether a multi-step sequence repeats, and generates an n8n automation for it

~5 years across SaaS, eCommerce, EdTech and AI products. Before Zava, I cut backend response times by 45% on an on-demand laundry platform by fixing slow queries and API logic.

---

## What I work with

| | |
| :--- | :--- |
| **GenAI / LLMs** | LLM APIs (OpenAI, OpenRouter), RAG over knowledge bases, prompt engineering, token and cost control, MCP servers, n8n agent workflows |
| **Backend** | Node.js, Express, Python, FastAPI, Pydantic, SQLModel, REST APIs, WebSockets |
| **Frontend** | React, Next.js, TypeScript, Redux, Tailwind CSS, React Native, Electron, HTML5 Canvas |
| **Data** | PostgreSQL, MongoDB, MySQL, Redis, Prisma, Sequelize |
| **Cloud & DevOps** | AWS (EC2, S3, Lambda), Docker, GitHub Actions, Vercel, Cloudflare Pages |
| **Testing** | Cypress (E2E), Jest |
| **Daily tools** | Claude Code, Cursor |

---

## Things I've built

### GitGuise · [gitguise.dev](https://gitguise.dev) · [repo](https://github.com/yash-js/gitguise)
Open-source desktop app for developers who juggle more than one GitHub account on one machine. A pre-push hook reads the remote URL, picks the right identity, and rewrites HTTPS remotes to SSH so the wrong account never pushes. Ships with a 7-step SSH setup wizard, a repo scanner, and config export/import. Launched on Product Hunt.
`Electron` `Node.js` `node-pty` `GitHub Actions`

### fastapi-jwt-auth · [repo](https://github.com/yash-js/fastapi-jwt-auth)
An auth service done properly rather than the tutorial version: Argon2 password hashing, 15-minute JWT access tokens, and **opaque refresh tokens that are stored only as SHA-256 hashes** and rotated on every use, with revocation on logout. Protected routes resolve the current user through a `Depends()` chain with a yield-managed DB session.
`Python` `FastAPI` `Pydantic` `SQLModel` `PyJWT`

### Aligno · [aligno.in](https://aligno.in)
Project management SaaS with multiple workspaces, Kanban boards, OKR/goal tracking, and live collaboration and notifications over WebSockets.
`Next.js` `Node.js` `PostgreSQL` `Prisma` `WebSockets`

### FynCart · [fyncart.store](https://fyncart.store)
Multi-role eCommerce platform with Razorpay payments, Redis caching, and Cloudinary for media.
`Next.js` `Node.js` `PostgreSQL` `Redis`

### Learning Tracker · [learn.yashpurani.com](https://learn.yashpurani.com)
Turns a YouTube playlist into a structured course with streaks and per-video notes.
`Next.js` `Node.js` `PostgreSQL`

### DSA · [repo](https://github.com/yash-js/DSA) · [LeetCode](https://leetcode.com/u/yash_purani/)
Every accepted LeetCode submission syncs here automatically, mostly in Java.

<img src="https://img.shields.io/github/directory-file-count/yash-js/DSA?style=flat-square&logo=github&color=2ea44f&label=Problems%20Solved&type=dir" alt="Problems Solved" />

---

## Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yash-js&theme=tokyo-night&hide_border=true" width="100%" alt="GitHub activity graph" />
</p>

---

## Reach me

[yashpurani.com](https://yashpurani.com) · [LinkedIn](https://linkedin.com/in/yashpurani) · [yashpurani8@gmail.com](mailto:yashpurani8@gmail.com)

Based in Gujarat, India. Open to remote roles and relocation.
