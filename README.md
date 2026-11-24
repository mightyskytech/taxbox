<div align="center">

# TaxBox NG

**Lagos PAYE calculator for the Nigeria Tax Act (NTA) 2026**

Accurate PAYE computation, payroll tools and tax guidance for individuals, HR teams and tax consultants.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

Built by [Mighty Sky Technologies](https://mightyskytech.com)

</div>

---

## Overview

TaxBox NG computes Pay-As-You-Earn (PAYE) tax under Nigeria's new Tax Act 2026 for Lagos State. It serves three types of user, each with its own role-based dashboard:

| Persona | What they get |
|---|---|
| 👤 **Individual taxpayer** | Instant take-home pay, tax breakdown and old-vs-new regime comparison |
| 🏢 **HR / payroll manager** | Batch payroll from spreadsheets, employee records, remittance and payment schedules |
| 📑 **Tax consultant** | Client records, withholding tax schedules, direct assessment, audit checklists and staff cost analysis |

## Key features

- **NTA 2026 PAYE calculator** with a full, line-by-line tax computation table
- **Old regime comparison** to show how the new law changes an employee's tax
- **Reverse calculator** — work out the gross salary needed for a target net pay
- **Optimisation sandbox and scenario manager** to test and save what-if pay structures
- **Batch upload** of payroll from Excel/CSV for many employees at once
- **Interactive charts** of tax bands and deductions
- **Tax reminders** and payment channel guidance for remittance deadlines
- **AI tax assistant** chatbot for plain-English answers to PAYE questions
- **Record management** for employees, expatriates, PAYE remittances, WHT schedules, development levy, business premises and more
- **Secure accounts** with registration, login, password reset and JWT-protected routes
- **Installable web app** (PWA) that works well on mobile

## Tech stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite, Tailwind CSS, React Router, Recharts, Zod, SheetJS (xlsx) |
| Backend | Node.js, Express, SQLite (better-sqlite3), JWT authentication, bcrypt |
| AI | Serverless AI endpoint for the tax assistant |

## Getting started

```bash
# Clone the repository
git clone https://github.com/mightyskytech/taxbox.git
cd taxbox

# Install dependencies (frontend and backend)
npm install
npm install --prefix server

# Run frontend and backend together (seeds the demo database first)
npm run dev:all
```

Other scripts:

| Command | Purpose |
|---|---|
| `npm run dev` | Start the frontend only |
| `npm run dev:server` | Seed and start the API server |
| `npm run build` | Type-check and build for production |
| `npm run lint` | Run ESLint |

## Documentation

- [Technical specification](SPECIFICATION.md)
- [User guide](USER_GUIDE.md)
- [Costing](COSTING.md)

## Disclaimer

TaxBox NG gives estimates to help with planning. Always confirm final figures with the Lagos State Internal Revenue Service or a qualified tax adviser.

---

<div align="center">

**Need a custom payroll, tax or business web app?**  
[Mighty Sky Technologies](https://mightyskytech.com) · [mightyskytechnologies@gmail.com](mailto:mightyskytechnologies@gmail.com)

</div>
