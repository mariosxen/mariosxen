<p align="center">
  <a href="https://mxenofontos.com"><img src="assets/banner.svg" alt="Marios Xenofontos · IT Systems Administrator II · DevSecOps focus" width="100%"></a>
</p>

<p align="center">
  <a href="https://mxenofontos.com"><img src="https://img.shields.io/badge/Portfolio-mxenofontos.com-f59e0b?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/marios-xenofontos/"><img src="https://img.shields.io/badge/LinkedIn-marios--xenofontos-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:mariosxen7@icloud.com"><img src="https://img.shields.io/badge/Email-mariosxen7%40icloud.com-334155?style=for-the-badge&logo=icloud&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cloudflare-Workers%20·%20Zero%20Trust-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/SAST-Semgrep-0f766e?style=flat-square" alt="Semgrep">
  <img src="https://img.shields.io/badge/Secrets-Gitleaks-b91c1c?style=flat-square" alt="Gitleaks">
  <img src="https://img.shields.io/badge/Deps-Dependabot-025E8C?style=flat-square&logo=dependabot&logoColor=white" alt="Dependabot">
  <img src="https://img.shields.io/badge/Auth-Better%20Auth-111827?style=flat-square" alt="Better Auth">
  <img src="https://img.shields.io/badge/AI-MCP%20%2B%20RBAC-7c3aed?style=flat-square" alt="MCP with RBAC">
</p>

---

### 👋 Hi, I'm Marios

IT Systems Administrator II in **Larnaca, Cyprus**, focused on **DevSecOps**. I build web apps with AI, then do the part AI won't do for you: **secure them, ship them through CI/CD and keep them running on Cloudflare**.

- 🛡️ Every app passes the same security baseline before it ships
- 🔐 Logins sit behind **Cloudflare Zero Trust**; data reads go through **MCP with role checks**
- 📈 Logs, audit trails, health checks and alerts on everything in production
- 💾 Off-site backups and a written recovery plan per app
- 🤖 I build with AI and Cloudflare every day, so I keep up with both as they change

> My repositories are private. This page shows what the projects do and how they're built and secured. Happy to talk through any of it.

---

### 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cloudflare,workers,githubactions,github,docker,ts,nodejs,react,nextjs,vite&perline=10" alt="Cloudflare, Workers, GitHub Actions, GitHub, Docker, TypeScript, Node.js, React, Next.js, Vite"><br>
  <img src="https://skillicons.dev/icons?i=tailwind,prisma,postgres,vitest,linux,ubuntu,nginx,ansible,grafana,bash&perline=10" alt="Tailwind, Prisma, PostgreSQL, Vitest, Linux, Ubuntu, Nginx, Ansible, Grafana, Bash"><br>
  <img src="https://skillicons.dev/icons?i=powershell,azure,git,vscode&perline=10" alt="PowerShell, Azure / Entra ID, Git, VS Code">
</p>

---

### 🚀 What I've built

| | Project | What it does | Status |
|:-:|---|---|:-:|
| 🤖 | **Internal AI assistant** | AI chat that answers from an organisation's databases through **MCP**, with RBAC on every source, limits on what the AI can read, and GDPR & EU AI governance built in | ![building](https://img.shields.io/badge/-building-f59e0b?style=flat-square) |
| 🗂️ | **IT environment & asset hub** | Every system and piece of software, what it does, where its data lives and who owns it. Live data from the GitHub & Cloudflare APIs, per-person hardware, joiners and leavers | ![live](https://img.shields.io/badge/-live-16a34a?style=flat-square) |
| 📅 | **Workforce scheduling** | Organisation-wide shift planning with roles, automatic overtime and payroll exports | ![live](https://img.shields.io/badge/-live-16a34a?style=flat-square) |
| ⭐ | **Appraisal system** | One performance review process for everyone, history in one place | ![live](https://img.shields.io/badge/-live-16a34a?style=flat-square) |
| 📊 | **Department operations apps** | KPI and case tracking, one app per department | ![live](https://img.shields.io/badge/-live-16a34a?style=flat-square) |
| 🗓️ | **Social media calendar** | One content calendar across all social accounts | ![live](https://img.shields.io/badge/-live-16a34a?style=flat-square) |
| 🛡️ | **Security baseline for AI-built apps** | Hardened Workers template, threat model, OWASP rules, SAST, secret, dependency and live-site scanning | ![in use](https://img.shields.io/badge/-in%20use-2563eb?style=flat-square) |

---

### 🔄 How every app ships

```mermaid
flowchart LR
  A["🧱 Hardened template<br/>threat model · OWASP"] --> B["🔍 Scan<br/>Semgrep · Gitleaks · Dependabot · actionlint"]
  B --> C["⚙️ GitHub Actions<br/>Wrangler · environments · health check"]
  C --> D["☁️ Cloudflare edge<br/>WAF · bot rules · origin lock"]
  D --> E["🔐 Zero Trust<br/>Cloudflare Access · Entra ID · Intune"]
  E --> F["🧠 Apps & AI<br/>MCP · role checks"]
  F --> G["💾 Backups & recovery<br/>off-site · DR plan"]
  F -.-> H["📈 Logs & alerts<br/>Workers Logs · Logpush · audit"]
```

---

### 🧩 Details

<details>
<summary><b>☁️ Cloudflare</b></summary>
<br>

Workers · Pages & static assets · D1 · KV · R2 · Durable Objects · Queues · Workflows · Workers AI · Vectorize · Hyperdrive · Email · Analytics Engine · Secrets Store · Access / Zero Trust · WAF · Turnstile · rate limiting · mTLS · Images · Workers for Platforms · cron triggers · service bindings · staging & production environments

</details>

<details>
<summary><b>⚙️ GitHub & CI/CD</b></summary>
<br>

GitHub Actions (reusable and scheduled workflows, environments and production gates) · Wrangler · Dependabot · CODEOWNERS · Gitleaks secret scanning · actionlint workflow checks · Semgrep SAST · dependency audits · D1 migrations in CI · post-deploy health checks

</details>

<details>
<summary><b>📈 Logging & checks</b></summary>
<br>

Workers Logs · Logpush · audit and security event logs · Analytics Engine · Web Analytics · health endpoints · uptime monitors · alerts · CSP · HSTS · security.txt

</details>

<details>
<summary><b>🔐 Auth & identity</b></summary>
<br>

Better Auth (open source, self-hosted on D1: email one-time codes, rate limits, secure sessions) · Microsoft 365 · Entra ID · Intune · Conditional Access · passkey MFA

</details>

<details>
<summary><b>🛠️ Development</b></summary>
<br>

TypeScript · Node.js · Hono · React · Next.js (OpenNext) · Vite · Tailwind CSS · Zod · Drizzle · Prisma · PostgreSQL · Vitest (Workers pool) · Playwright · ESLint · Biome · Vercel AI SDK · MCP

</details>

<details>
<summary><b>🖥️ Infrastructure & network</b></summary>
<br>

Ubuntu Server · Windows Server & Active Directory · Docker · Nginx · Ansible · VMware vSphere · Proxmox · Hyper-V · Veeam · Synology · TrueNAS · Ubiquiti UniFi · Cisco Meraki · VLANs · WireGuard · IPsec · Zabbix · Grafana · Uptime Kuma · PowerShell · Bash

</details>

---

<p align="center">
  <sub>📍 Larnaca, Cyprus · 🇬🇷 Greek · 🇬🇧 English · <a href="https://mxenofontos.com">mxenofontos.com</a></sub>
</p>
