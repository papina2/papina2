# 👋 Hi, I'm **Papina Dev**

### Backend • AI • Game Dev • Full‑Stack Engineer

[![GitHub followers](https://img.shields.io/github/followers/papina2?style=social)](https://github.com/papina2) ![Years Coding](https://img.shields.io/badge/Years_Coding-10+-brightgreen) ![Profile Views](https://komarev.com/ghpvc/?username=papina2\&color=blueviolet)

---

## 💻 About Me

```ts
const papina = {
  handle: "papina",
  focus: ["Backend Architecture", "AI/ML", "Game Dev", "Realtime Systems"],
  languages: ["TypeScript", "Python", "Lua", "C++"],
  motto: "Turning coffee into code since 2012 ☕→💻"
};
```

I build production-ready systems: scalable backends, multiplayer game services, AI pipelines, and polished web frontends. I bridge game engines and web tech to deliver robust dev experiences for FiveM / RedM servers and modern web apps.

---

## 🛠 Tech Stack — Professional Edition

### Languages & Runtimes

* TypeScript, JavaScript (ESNext)
* Python (AI/ML, tooling)
* Lua (FiveM / RedM scripts)
* C++ (high-performance game backend)

### Frontend

* React, Next.js (App Router & Server Components)
* Vite, Tailwind CSS, SASS/SCSS
* HTML5, CSS3, Progressive Web Apps (PWA)
* Storybook, Headless UI, shadcn/ui

### Backend & Infra

* Node.js, NestJS, Express, Fastify
* PostgreSQL (Prisma / TypeORM / Sequelize), MongoDB
* Redis, RabbitMQ / Kafka (message queues)
* Docker, Docker Compose, Kubernetes (k8s)
* NGINX, PM2, systemd
* CI/CD: GitHub Actions, GitLab CI

### Real‑time & Multiplayer

* Socket.IO, WebRTC, WebSockets
* FiveM / RedM server scripting (Lua + C++ integration)
* Dedicated server orchestration and autoscaling

### AI/ML & Data

* PyTorch, TensorFlow, Hugging Face transformers
* LangChain, OpenAI API, embeddings & vector DBs (Milvus, Pinecone, Weaviate)
* OpenCV, basic computer vision pipelines

### Dev Tools & Quality

* pnpm, npm, yarn, Turborepo, Nx
* ESLint, Prettier, Husky, lint-staged
* Jest, Vitest, Playwright, Cypress
* Sentry, Prometheus + Grafana, ELK stack

---

## 🚀 Project Highlights

### Unknown Horizons RP (FiveM)

* Roleplay server with custom Lua scripts, inventory, job systems, and admin tools.
* Integrations: Discord bot for moderation & whitelist, MySQL for persistence, web admin panels.

### Unwritten Universe (UE5)

* Action RPG prototype in Unreal Engine 5 with procedural world generation and C++ networking.
* AI-driven NPC ecosystems and server-authoritative multiplayer components.

---

## 🔧 Example Setup — Web + API (Next.js + Node + Postgres)

### Backend (quick start)

```bash
# install
pnpm install

# start dev API server
pnpm --filter api dev

# run tests
pnpm test
```

### Frontend (Next.js)

```bash
pnpm --filter web dev
# build and start for production
pnpm --filter web build && pnpm --filter web start
```

Sample scripts in package.json (monorepo-aware):

```json
{
  "scripts": {
    "dev": "turbo run dev",
    "build": "turbo run build",
    "test": "turbo run test"
  }
}
```

---

## 🔁 CI / CD (recommended)

* Use GitHub Actions with matrix builds (lint, test, build). Deploy containers to Docker registry and use k8s or managed services (DigitalOcean Kubernetes, Amazon EKS).
* Example actions: `lint.yml`, `test.yml`, `deploy.yml` (build -> push -> helm upgrade).

---

## 🕹 FiveM / RedM (Lua) — pro tips

* Organize resources: `server/`, `client/`, `shared/` with Clear exports and events.
* Use a central `config.lua` for settings and feature toggles.
* Protect admin endpoints and use server-side permission checks.
* Prefer server-validated state for critical operations (money, inventory, whitelist).

---

## ✅ Best Practices I Follow

* Type everything (TypeScript + strict mode)
* Write tests for business logic (unit + integration)
* Keep infra declarative (IaC: Terraform / Helm)
* Maintain observability (metrics, tracing, structured logs)
* Small, reviewable PRs + automated checks

---

## 📦 Boilerplate & Reusable Snippets

* `next-starter`: Next.js + Tailwind + Prisma + Auth
* `fiveM-template`: Lua resource skeleton with role/check middlewares
* `ai-pipeline`: embeddings + vector search + retrieval chain example

If you want, I can generate any of the above boilerplates (Next.js starter, FiveM resource template, or AI pipeline example).

---

## 📫 Contact & Links

* GitHub: [https://github.com/jdcoding01](https://github.com/jdcoding01)
* Email: [jdcoding01@gmail.com](mailto:jdcoding01@gmail.com)

> “Code is the ultimate playground where mathematics meets art.” — A. Developer
