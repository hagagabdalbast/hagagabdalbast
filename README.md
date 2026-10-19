<h1 align="center">Hagag Abdelbaset Mohamed</h1>
<h3 align="center">Full Stack Software Engineer · ASP.NET Core · SQL Server · Clean Architecture</h3>

<p align="center">
  <a href="https://hagag-mohamed.vercel.app"><img src="https://img.shields.io/badge/Portfolio-hagag--mohamed.vercel.app-123a7a?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/hagag-mohamed-b01b93185"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hagagabdalbast@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Riyadh,%20Saudi%20Arabia-1f6feb?style=flat&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Experience-4%2B%20years-2ea44f?style=flat" alt="Experience" />
  <img src="https://img.shields.io/badge/Open%20to-Backend%20%26%20Full%20Stack%20roles-8957e5?style=flat" alt="Open to work" />
</p>

---

### About

Full Stack Software Engineer with **4+ years** architecting and shipping enterprise systems across
government, EdTech, PropTech, FinTech and B2B SaaS — mostly on **ASP.NET Core** and **SQL Server**,
with production depth in **Laravel** and **Flutter**.

- 🏗️ I design for handover: **Clean Architecture, DDD and SOLID**, because the systems I build get extended for years.
- 🏢 Currently **Software Engineer @ Afaq Tech**, Riyadh — backend architect on .NET and full-stack owner on Laravel and Flutter across eight+ enterprise products.
- 👥 I lead development teams and code review, and work directly with government and enterprise clients from requirements through delivery.
- 🇸🇦 I build **Arabic-first, RTL-correct** products — designed in from the first commit, not retrofitted.
- 📬 **hagagabdalbast@gmail.com**

**Measured outcomes:** 30% faster search queries through SQL Server indexing and partitioning ·
25% less facility downtime through maintenance automation · 20% faster delivery through disciplined layered architecture.

---

### Open Source

**[multitenant-clean-architecture](https://github.com/hagagabdalbast/multitenant-clean-architecture)** — a
multi-tenant SaaS starter on ASP.NET Core 10, distilled from the patterns behind the platforms below.

Tenant isolation is enforced in one place rather than by convention: EF Core global query filters
attached by reflection to every tenant-scoped entity, plus tenant stamping and a cross-tenant write
guard in `SaveChanges`. A handler never writes a tenant predicate, so it can never forget one.
Also includes a bounded `Channel<T>` background email queue with backpressure, SignalR notifications
isolated by per-tenant groups, and a derived RBAC permission matrix. 38 tests, warnings as errors.

---

### Featured Work

Most of what I build is client and government software, so the source lives in private
repositories. Each project below has a full write-up — architecture, modules, stack and
screenshots — on my portfolio.

| Project | What it is | Stack |
| --- | --- | --- |
| [**Afaq FMS**](https://hagag-mohamed.vercel.app/en/projects/afaq-fms) | 🟢 Live · Multi-tenant facilities-maintenance ERP — 20+ modules, consultant → contractor → ministry ticket workflow, SignalR. 697+ tickets closed across 99 departments | ASP.NET Core 8 · SQL Server · SignalR · Hangfire · Flutter |
| [**Ministry Meeting Rooms**](https://hagag-mohamed.vercel.app/en/projects/meeting-rooms) | 🟢 Live · Hall booking for a Saudi ministry — week grid, per-hall approvals, Outlook invites, Exchange sync, one-time-code sign-in, LDAP lookup | ASP.NET Core 8 · Clean Architecture + CQRS · MediatR · xUnit |
| [**Afaq Legal**](https://hagag-mohamed.vercel.app/en/projects/afaq-legal) | 🟢 Live · Law-office management — cases, session roll, appeal deadlines, judgments, contracts and fee agreements with role-based workflows | ASP.NET Core 10 · EF Core · SQL Server · Flutter |
| [**Ensraf**](https://hagag-mohamed.vercel.app/en/projects/ensraf) | 🟢 Live in 7 schools · School dismissal, attendance & transport — a Filament admin and three Flutter apps (guardians, drivers, classrooms) with live bus tracking. 47 domain entities | Laravel 12 · Filament · Flutter · FCM |
| [**Mutaallim (EduPlatform)**](https://hagag-mohamed.vercel.app/en/projects/eduplatform) | 🟢 Live · Learning platform with an AI tutor that answers only from the student's book, read-aloud, translation and LiveKit live classes — AI runs on-server | .NET 8 · React · LiveKit · Ollama · Docker |
| [**Afaq AMS**](https://hagag-mohamed.vercel.app/en/projects/afaq-ams) | 🟢 Live · Preventive maintenance — EAV property model, QR scan-to-report stickers, maintenance plans with due/overdue tracking | ASP.NET Core 9 · EF Core 9 · SQL Server |
| [**MediaPlus**](https://hagag-mohamed.vercel.app/en/projects/mediaplus) | 🟢 Live · Digital-signage SaaS — subscription billing, a Flutter display client and a Kotlin manager app, remote power control and OTA updates | ASP.NET Core · Flutter · Kotlin · Jetpack Compose |
| [**Aqari**](https://hagag-mohamed.vercel.app/en/projects/aqari) | 🟢 Live · Real-estate marketplace (web + mobile) — map search with clustering, agent marketplace, real-time chat, mortgage and investment tools | Laravel 12 · MySQL · Pusher · Flutter |
| [**ErpGold**](https://hagag-mohamed.vercel.app/en/projects/erpgold) | 🛠️ In development · Gold & jewelry ERP — every piece tracked by weight, karat and pure weight; a Windows agent drives label printers and scales | ASP.NET Core · SQL Server · Next.js 16 |
| [**FatoraScan**](https://hagag-mohamed.vercel.app/en/projects/fatorascan) | ZATCA-compliant e-invoicing — validates QR payloads against the TLV specification, bilingual AR/EN OCR on scanned invoices | ASP.NET Core · PostgreSQL · React |
| [**AlMuhaisni**](https://hagag-mohamed.vercel.app/en/projects/almuhaisni) | 🟢 Live · Property management platform — search response time cut 30% via SQL Server indexing and table partitioning | .NET Core · Dapper · SQL Server |

<p align="center">
  <a href="https://hagag-mohamed.vercel.app/en#projects"><b>→ All 17 projects, with full case studies</b></a>
</p>

---

### Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)

**Backend**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core%208%2F9%2F10-512BD4?style=flat&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/Entity%20Framework%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-C71A36?style=flat)
![Laravel](https://img.shields.io/badge/Laravel%2012-FF2D20?style=flat&logo=laravel&logoColor=white)
![Filament](https://img.shields.io/badge/Filament-FDAE4B?style=flat&logo=laravel&logoColor=black)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat&logo=odoo&logoColor=white)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat&logo=blazor&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Databases**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

**Architecture & Real-time**

![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-0b3d91?style=flat)
![DDD](https://img.shields.io/badge/Domain--Driven%20Design-0b3d91?style=flat)
![Multi-tenant SaaS](https://img.shields.io/badge/Multi--tenant%20SaaS-0b3d91?style=flat)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat&logo=dotnet&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit%20(WebRTC)-1f8cf9?style=flat)
![Hangfire](https://img.shields.io/badge/Hangfire-b4232c?style=flat)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### Experience

| Role | Company | Period |
| --- | --- | --- |
| Software Engineer | **Afaq Tech** — Riyadh, Saudi Arabia | Nov 2025 – Present |
| Software Engineer | **SpeedProgramming** — Jeddah, Saudi Arabia | May 2025 – Oct 2025 |
| Software Engineer | **4rubaiyat** — Riyadh, Saudi Arabia | May 2024 – Feb 2025 |
| Software Engineer | **Information Systems, Egyptian Armed Forces** — Cairo, Egypt | Oct 2021 – Oct 2023 |

🎓 **Bachelor's Degree in Computer and Information Systems** — Minia University (2016 – 2020)

---

<p align="center">
  <a href="https://hagag-mohamed.vercel.app"><img src="https://img.shields.io/badge/See%20the%20full%20portfolio-123a7a?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/hagag-mohamed-b01b93185"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hagagabdalbast@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://wa.me/966549389625"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
</p>
