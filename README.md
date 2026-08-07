<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Noto+Sans+Display&weight=600&size=40&pause=600&color=58A6FF&background=FFFFFF00&vCenter=true&random=false&width=503&height=65&lines=Hi+There+%F0%9F%91%8B!;I+am+Shiva+Raghav." alt="Typing SVG" />
  </a>
</p>

Backend and full-stack engineer. Sunnyvale, CA.

I work on the unglamorous parts of production systems: ingestion reliability, background job infrastructure, and the failure modes that only show up at volume.

**Currently:** building FlowTask, and looking for backend / full-stack work at an early-stage team.

---

## What I've built

**FlowTask** — Task and goal management platform with an AI planning agent. Solo-built and running in production.
`Turborepo` · `React` · `TypeScript` · `Node` · `Postgres` · `Prisma` · `Meilisearch` · `BullMQ`

The parts worth talking about: a background job layer handling scheduled agent check-ins with per-user context assembled at runtime, and a four-layer evaluation loop for LLM output — schema validation, heuristic checks, LLM-as-judge, and a golden set — because the naive version of this drifts silently and you don't find out until users do.

[Repo](https://github.com/shivarag200701/flowtask) · [Docs](https://github.com/shivarag200701/flowTask-docs) · [Live](https://www.shiva-raghav.com/)

**Mermory** — Founding Engineer. Document-to-flashcard platform.

Rebuilt the ingestion pipeline from 70% to 98% success across 12,000+ items using idempotency keys and at-least-once delivery. The original pipeline dropped work silently on retry; the fix was making every stage safe to run twice.

**Agnikul Cosmos** — Aerospace validation and microservices systems. Chennai, India.

Decomposed a monolithic validation service into independently deployable components.

**Cloud Deployment Platform** — Multi-service build-and-host pipeline on AWS (S3, Lambda, SQS, ECS). Build queueing, log streaming, and artifact serving.

[Repo](https://github.com/shivarag200701/cloud_deployment_platform)

---

## Work I do outside my own projects

Contributor to [oxc](https://github.com/oxc-project/oxc) — Rust-based JavaScript toolchain.

---

## Stack

**Primary:** TypeScript, Node.js, Python, PostgreSQL, Prisma, Redis, BullMQ
**Also:** React, Next.js, Express, Meilisearch, Docker, AWS

---

## Background

M.S. Computer Science, Illinois Institute of Technology, Chicago.

Previously mechanical engineering — which is where I learned that most systems fail at the interfaces, not the components.

---

## Activity

<p align="left">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shivarag200701&theme=dark&hide_border=true" alt="GitHub streak" />
</p>

<p align="left">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shivarag200701&radius=16&theme=github-compact&area=true&hide_border=true&custom_title=Contributions" alt="Contribution graph" />
</p>

---

[Portfolio](https://www.shiva-raghav.com/) · [LinkedIn](https://www.linkedin.com/in/shiva-raghav/)
