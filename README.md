<!-- Banner — replace the URL below once you have your generated image -->
<p align="center">
  <img src="https://raw.githubusercontent.com/stephenbett/stephenbett/main/Github.png" 
       alt="Stephen Bett — Senior Full-Stack Engineer" width="100%" />
</p>

<h1 align="center">👋 Hi, I'm Stephen Kiprop Bett</h1>

<p align="center">
  <strong>Senior Full-Stack Engineer · Fintech · SaaS Platforms · Nairobi, Kenya</strong><br/>
  M-Pesa · KRA eTIMS · Distributed Systems · Open to remote & hybrid roles worldwide
</p>

<p align="center">
  <a href="https://portfolio-rosy-xi-52.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Site-0d1117?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/stephen-bett-190166219/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:bettstephen110@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🧑‍💻 About me

Senior Full-Stack Engineer with **4+ years of production experience** building 
mission-critical SaaS platforms, payment integrations, and regulatory compliance 
systems for East African markets and enterprise clients.

I build complete systems — from domain-driven backends and distributed services 
to deployed production infrastructure with full observability.

- 🏆 **Award-winning engineer** — Innovation Week (SaccoShareX platform)
- 💳 **Production payment APIs**: M-Pesa Daraja (STK Push, C2B, B2C), KRA eTIMS OSCU, eCitizen/PesaFlow, KRA iTax
- 🏗 **Deployed SaaS products**: HomeHub RMS (live), BankConnect H2H Gateway, Marina Bay TMS
- 🌍 Based in **Nairobi, Kenya** · Open to remote & hybrid roles worldwide
- 📖 Currently deepening: Cloud architecture · Cloudflare Workers · Kubernetes

---

## 🛠 Tech stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Databases & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)

**Payments & Compliance**

![M-Pesa](https://img.shields.io/badge/M--Pesa_Daraja-00A651?style=flat-square&logo=safaricom&logoColor=white)
![KRA eTIMS](https://img.shields.io/badge/KRA_eTIMS-OSCU-CC0000?style=flat-square)
![eCitizen](https://img.shields.io/badge/eCitizen-PesaFlow-1B6CA8?style=flat-square)

**DevOps & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Featured projects

### 🏠 HomeHub SaaS RMS — Live Multi-Tenant Property Management Platform
> Commercially deployed SaaS rental management system serving live property 
> companies. Self-service, no-code configuration for landlords.

- Multi-tenant architecture with strict data isolation and subdomain resolution
- **FIFO payment allocation** engine, arrears carry-forward, double-entry ledger
- **M-Pesa STK Push** + C2B webhook handlers with idempotency guards
- WhatsApp Meta Cloud API, ExpressSMS, MailKit for tenant notifications
- Excel bulk billing pipeline with transactional rollback on validation failure
- Full CI/CD: GitHub Actions → Docker → Nginx → systemd on Linux VPS

`TypeScript` `React` `Angular` `Node.js` `SQL Server` `M-Pesa` `Docker` `GitHub Actions`

🔗 **Live API:** https://miraiholdings.mgroupke.com
---

### 🏦 Bank Integration Enterprise Platform — Multi-Tenant Bank H2H Integration Gateway
> Enterprise bank host-to-host integration platform. Multiple organisations 
> configure bank partnerships through UI — no code required.

- **PostgreSQL 17 Row-Level Security** for zero cross-tenant data leaks
- **RabbitMQ + MassTransit** saga orchestration with dead-letter queues
- **SFTP + PGP encryption** (SSH.NET, PgpCore) for bank-grade security
- **Keycloak** OIDC/OAuth2 with MFA, multi-tenant SSO, RBAC
- **OpenTelemetry + Grafana** full observability stack
- **YARP** API gateway with rate limiting and IP allowlisting
- **MinIO** S3-compatible object storage

`ASP.NET Core 10` `React 19` `PostgreSQL 17` `RabbitMQ` `MassTransit` `Redis` `Keycloak` `Docker`

---

### 🧾 Marina Bay TMS — KRA eTIMS OSCU Integration
> Complete KRA eTIMS integration enabling legally compliant electronic 
> tax invoicing directly with Kenya Revenue Authority production API.

- OSCU model: device initialization, item registration, invoice submission
- VAT classification (Exempt vs 16% Standard) and KRA signature capture
- Emergency late-sync background queue for production resilience
- Database schema upgrades: EtimsConfig, invoice KRA metadata, item codes

`Node.js` `C#` `ASP.NET Core` `KRA eTIMS REST API` `PostgreSQL` `SQL Server`

---

### 🏆 SaccoShareX — Real-Time Fintech Trading Platform
> Award-winning real-time share trading platform for SACCO members.
> Winner — Innovation Week Competition.

- **SignalR** for real-time notifications and live price updates
- **M-Pesa API** — payments, escrow, and disbursements
- **ML.NET** fraud detection and predictive analytics
- Blockchain-based immutable transaction ledger

`React` `.NET Core` `SignalR` `ML.NET` `SQL Server` `M-Pesa API`

---

### 🏛 NEMA Licensing Portal — Nationwide Government Platform
> Environmental licensing platform supporting multi-level regulatory 
> approval workflows across Kenya.

- Configurable multi-level approval workflow engine
- **KRA iTax** and **eCitizen/PesaFlow** API integrations
- Audit trails, RBAC, and SASRA-compliant data traceability

`React` `TypeScript` `.NET 8` `PostgreSQL` `KRA iTax API` `eCitizen`

---

### 🏪 Astrol POS — Offline-First Enterprise System
> Enterprise POS engineered for continuous operation during network outages.

- **IndexedDB (Dexie.js)** + Service Workers for offline transaction processing
- Sync engine for transaction reconciliation on reconnect
- Clean Architecture + CQRS (MediatR) backend
- Multi-tenant with dynamic branding per client

`React` `TypeScript` `.NET 8` `Docker` `PWA` `SQL Server` `M-Pesa`

---

## 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=stephenbett&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=stephenbett&layout=compact&theme=github_dark&hide_border=true&count_private=true" height="150" />
</p>

---

## 📫 Let's connect

| Platform | Link |
|---|---|
| 🌐 Portfolio | [portfolio-rosy-xi-52.vercel.app](https://portfolio-rosy-xi-52.vercel.app/) |
| 💼 LinkedIn | [linkedin.com/in/stephen-bett-190166219](https://www.linkedin.com/in/stephen-bett-190166219/) |
| ✉️ Email | bettstephen110@gmail.com |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=stephenbett&color=58a6ff&style=flat-square&label=Profile+views" />
</p>
