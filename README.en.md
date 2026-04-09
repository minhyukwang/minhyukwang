<div align="center">

<img src="https://readme-typing-svg.vercel.app/?lines=Hi%2C+I%27m+Minhyuk;Full+Stack+%7C+Web+%7C+Data+Layer;Enterprise+SSO+%C2%B7+Next.js+%C2%B7+SQL&font=Fira%20Code&center=true&width=700&height=55&color=58A6FF&vCenter=true&size=22&duration=3200&pause=900&repeat=true" alt="Typing intro">

### Minhyuk Wang (Peter) · Seoul

<a href="mailto:minhyuk.tech@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/minhyukwang"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/minhyuktech"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

<br>

[**← 한국어 (Korean)**](README.md) · **English** · [**Side project docs**](./projects/README.md)

</div>

<img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='3'%3E%3Cdefs%3E%3ClinearGradient id='g' x1='0%25' y1='0%25' x2='100%25' y2='0%25'%3E%3Cstop offset='0%25' stop-color='%2358A6FF' stop-opacity='0.1'/%3E%3Cstop offset='50%25' stop-color='%2358A6FF' stop-opacity='0.45'/%3E%3Cstop offset='100%25' stop-color='%2358A6FF' stop-opacity='0.1'/%3E%3C/linearGradient%3E%3C/defs%3E%3Crect width='100%25' height='3' fill='url(%23g)'/%3E%3C/svg%3E" width="100%" height="3" alt="">

## One-liner

**Full Stack Developer in Seoul** — I ship **enterprise-scale SSO & authorization** and product-grade **Next.js** stacks. I care about **observable SQL**, **session models** (JWT vs cookie vs WebView), and **SLOs** that survive on-call.

## About

I build and operate large systems end-to-end. Today I run **federation-wide login & bank menu/permission** flows—high availability, latency, audit—and multi-system integration.

On the side, I work across **attendance**, **market data**, **team collaboration**, and **commerce**.

## Enterprise timeline

| Period | Focus |
| ------ | ----- |
| 2024.07 — **Present** | Financial sector **SSO & menu permissions** — reliability & audit |
| 2023.04 — 2024.06 | Next-gen **shared platform** (login, IAM modules) |
| 2021.08 — 2023.03 | **MES** refractories — MSA, settlement integrations |
| 2020.11 — 2021.07 | Enterprise **proposal** workflow — business + UI + DB |
| 2019.09 — 2020.10 | **Rail control** — framework migration, heavy TX |
| 2018.09 — 2019.08 | **Smart factory** data platform |

## Side projects

| Name | Period | Stack (short) | Architecture doc |
| ---- | ------ | ------------- | ---------------- |
| Attendance | 2025 — present | Next.js, WebView, reporting | [**attendance-app**](./projects/attendance-app.md) |
| Investment data | 2024 — 2025 | Next.js, Python batch, viz, **batch monitor** | [**investment-data**](./projects/investment-data.md) |
| Team collaboration | 2022 — 2023 | Next.js, realtime — **Hermes WS gateway** | [**team-collaboration**](./projects/team-collaboration.md) |
| Vertical commerce | 2020 — 2021 | Next.js — **Atlas file server** | [**vertical-commerce**](./projects/vertical-commerce.md) |

## Stack · layers

**Languages**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Frontend / runtime**  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Backend · data**  
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**Delivery · auth**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

<details>
<summary><b>Engineering highlights</b> (metrics — expand)</summary>

- **SQL / aggregates** — Monthly attendance API p95 ~2.8s → ~420ms after collapsing ORM graph into one bounded query + indexes.
- **WebView / auth** — Session churn ~3.5% → ~0.9% via refresh + HttpOnly cookies + SameSite discipline.
- **Enterprise SSO** — Peak login latency, permission sync SLAs, fewer misconfiguration tickets, faster rollback decisions via metrics & canaries.
- **Ops** — Slow-query hygiene, SLO-aware timeouts, shorter runbooks.

</details>

<details>
<summary><b>Architecture principles</b> (expand)</summary>

Keep Next.js UI + API in one codebase but **separate read vs write SLOs**. Use Prisma for migrations/CRUD; push heavy reads to **SQL/views**. For WebView, pick session strategy with **cookie domain** + **refresh dedup** + measurable mismatch rates.

</details>

**Contact** · [minhyuk.tech@gmail.com](mailto:minhyuk.tech@gmail.com) · [@minhyukwang](https://github.com/minhyukwang) · [LinkedIn](https://www.linkedin.com/in/minhyuktech)

<div align="center">

<img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='2'%3E%3Crect width='100%25' height='1' fill='%2358A6FF' fill-opacity='0.15'/%3E%3C/svg%3E" width="100%" height="2" alt="">

</div>
