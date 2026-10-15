# Hi, I'm Triston 👋

AI Engineer at **SL Information Sdn Bhd** · Subang Jaya, Malaysia
B.Eng. Artificial Intelligence, Xiamen University Malaysia

I build AI systems that turn messy real-world input — scanned forms, receipts, bills, transcripts,
live conversations — into data people can trust. The pattern I keep coming back to:
**the model proposes, a human confirms, the system keeps an audit trail.**

---

## 🌱 Featured — [WeSee](https://github.com/tristontoh/WeSee)

**AI-powered ESG intelligence for Malaysian companies** · MAIC Nexus Challenge, Track 6 · team lead (5)

Multi-tenant ESG reporting platform built around Bursa Malaysia's Common Sustainability Matters and
IFRS S1/S2, ahead of the National Sustainability Reporting Framework (NSRF).

- **Carbon Intelligence engine** — upload a TNB bill, fuel manifest or phone photo; a Vision-LLM
  proposes emission records and a human confirms. The response schema pins every target to the
  tenant's own emission factors, so the model can't name one that doesn't exist.
- **Assurance sign-off** — tamper-evident SHA-256 over reported values, revocation, full audit trail.
- **Platform** — Scope 1/2/3 dashboard, IFRS S1/S2 disclosures, materiality, targets, PDF/CSV export,
  TOTP MFA, scoped API tokens, ORM-enforced tenant isolation.

`Java 21` `Spring Boot 3` `React 19` `TypeScript` `PostgreSQL` `Flyway` `Gemini` `Docker`

---

## 🧰 Other things I've built

| Project | What it does | Stack |
|---|---|---|
| **JobSnooze** | Finds matching jobs overnight, gates on salary, tailors each application and pre-fills the form — then stops. A human presses submit; no CAPTCHA-solving or bot evasion, by design. Desktop app + Chrome extension. | TypeScript, Electron, Playwright, Supabase (RLS, Edge Functions), Gemini |
| **Finance Tracker** | Photograph a receipt, confirm what the app read, get a verified record. Monthly reports, AI analysis, chat over your own spending — all local, one-click launch on macOS. | React, Express, PostgreSQL, Gemini |
| **AI Roleplay Sales Trainer** | Insurance agents practise live conversations against an AI customer persona in English, Bahasa Malaysia or Tamil, then get rubric-scored coaching. Multi-branch admin, analytics, real-time notifications. *(client POC)* | Spring Boot, TypeScript, Gemini, WebSocket |
| **Handwritten Form Digitizer** | Turns scanned handwritten factory forms into database records: LLM extraction → fuzzy part-number matching → human review → export into the factory's own Excel templates. *(client project)* | Spring Boot, Angular 20, PostgreSQL, Gemini |
| **Document OCR Extraction** | Multi-template PDF extraction pipeline with OCR benchmarking, deployed as a Windows service. *(work project)* | .NET 8, C#, LEADTOOLS, PaddleOCR, PostgreSQL / SQL Server |
| **Meeting Minutes Generator** | Upload a Teams transcript, get structured minutes filled into a Word template. | React, Express, Claude API |
| **LexAgent** | AI legal assistant with case intake and chat. | Spring Boot, Angular, Gemini |
| **Route Sketch** | AI trip planner with a day-by-day timeline and map. | Angular, Express, Gemini |

*Most of these repos are private — happy to walk through any of them.*

---

## 🛠️ Tech I work with

**AI** — Vision-LLM document extraction, OCR, RAG, prompt/schema design for structured output, Gemini & Claude APIs
**Backend** — Java / Spring Boot, .NET / C#, Node / Express, Python / FastAPI
**Frontend** — React, Angular, TypeScript, Tailwind CSS, Electron
**Data & infra** — PostgreSQL, Supabase, Flyway, Docker, Playwright

## 📫 Reach me

tristontoh1212@gmail.com
