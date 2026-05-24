<div align="center">

<!-- Animated Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Shivam%20Verma&fontSize=60&fontColor=ffffff&fontAlignY=35&desc=Backend%20%26%20Distributed%20Systems%20Engineer&descAlignY=58&descSize=20&animation=fadeIn" />

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Building+scalable+systems+from+scratch;Node.js+%7C+PostgreSQL+%7C+Redis+%7C+Docker;Distributed+queues%2C+real-time+infra%2C+cloud;92%25+commits+%E2%80%94+I+ship+things+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- Social Badges -->
[![Portfolio](https://img.shields.io/badge/Portfolio-shivamworks.dev-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://www.shivamworks.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shivamv99-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shivamv99)
[![LeetCode](https://img.shields.io/badge/LeetCode-Top_5%25_Global-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/MahavirCoder/)
[![CodeChef](https://img.shields.io/badge/CodeChef-3★_1700+-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/mahavir99)

</div>

---

## ⚡ About Me

```ts
const shivam = {
  role:       "Backend & Distributed Systems Engineer",
  education:  "B.Tech CSE @ IIIT Nagpur (2022–2026)",
  currently:  "SWE Intern @ klimb.io",
  obsessions: ["async queues", "zero-downtime migrations", "sub-100ms APIs"],
  building:   "systems that scale — not just code that runs",
};
```

- 🏗️ I specialize in **high-throughput backend systems** — message queues, container orchestration, real-time infra
- ⚡ Reduced dashboard load time from **2–3s → under 500ms** at klimb.io via precomputed data pipelines
- 🐳 Cut Docker execution time **300ms → 5ms (~98% faster)** using persistent containers + tmpfs mounts
- 🌐 **809 contributions** in the last year — I show up every day
- 🏆 **LeetCode 1800+** rating · Top 5% globally

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### Backend & Frameworks
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### Databases & Messaging
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![BullMQ](https://img.shields.io/badge/BullMQ-FF6B6B?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ [CodeSM](https://github.com/shivamxverma/CodeSM) — Remote Code Execution Engine
> Distributed code execution platform using BullMQ + Docker containers

**The hard parts I solved:**
- ⚡ **98% faster execution** — persistent Docker containers with tmpfs mounts (300ms → 5ms per test)
- 🔁 Dead Letter Queue + 1-hour Redis cache layer for fault-tolerant job processing
- 📦 Segregated BullMQ queues for async submission at high throughput

`Node.js` `Redis` `BullMQ` `Docker` `PostgreSQL` `AWS EC2`

</td>
<td width="50%" valign="top">

### 📚 [Storix](https://github.com/shivamxverma/Storix) — AI Document Processing Platform
> Async PDF pipeline with real-time job updates via WebSockets

**The hard parts I solved:**
- 🔄 Decoupled ingestion from processing via distributed Celery workers
- ☁️ Pre-signed S3 URLs — zero backend file transfer bottleneck
- 📡 Replaced polling with Pub/Sub + WebSocket layer for instant status updates

`Next.js` `FastAPI` `Celery` `Redis` `PostgreSQL` `AWS S3`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 [Chatterly](https://github.com/shivamxverma/Chatterly) — Horizontally Scalable Chat
> Real-time messaging that scales across multiple server instances

**The hard parts I solved:**
- 🌐 Redis Pub/Sub for cross-server event propagation — no sticky sessions
- 🔒 JWT auth + room-level authorization enforced at Socket.IO middleware
- 📨 Zero message drops under concurrent multi-user load

`Next.js` `Socket.IO` `Redis` `PostgreSQL` `Prisma` `NextAuth`

</td>
<td width="50%" valign="top">

### 🏢 [klimb.io](https://klimb.io) — Production SWE Internship
> Recruiting platform serving multiple enterprise tenants

**What I shipped:**
- 💳 **Credit-based monetization** — migrated from feature flags, cut complexity ~70%
- 🗄️ **Global field template architecture** — zero-downtime DB migration with full data integrity
- 📊 **Dashboard latency** from 2–3s → under 500ms via precomputed pipelines

`TypeScript` `React` `Node.js` `PostgreSQL` `Redis` `AWS`

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=shivamxverma&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivamxverma&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=shivamxverma&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🏆 Competitive Programming

<div align="center">

| Platform | Handle | Rating / Rank |
|----------|--------|---------------|
| 🟡 LeetCode | [MahavirCoder](https://leetcode.com/u/MahavirCoder/) | **1800+** · Top 5% Global |
| ⭐ CodeChef | [mahavir99](https://www.codechef.com/users/mahavir99) | **1700+** · 3 Stars |
| 🔵 Codeforces | — | **Pupil** · Max 1261 |
| 🟠 AtCoder | — | **Rated 440+** |

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Shivam's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=shivamxverma&theme=tokyo-night&hide_border=true&area=true)](https://github.com/shivamxverma)

</div>

---

<div align="center">

### 💬 Let's Connect

*I'm always interested in backend infrastructure, distributed systems, and open source.*

[![Email](https://img.shields.io/badge/Email-shivam.verma.dev00@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivam.verma.dev00@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-shivamworks.dev-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://www.shivamworks.dev/)

<br/>

<!-- Footer wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" />

</div>
