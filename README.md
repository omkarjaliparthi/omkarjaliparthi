<p align="center">
  <img src="./banner.png" alt="Omkar Jaliparthi — Senior PM, AI Platforms · Multi-product platform builder" width="100%" />
</p>

<p align="center">
  <a href="mailto:admin@insightsbyomkar.com"><img src="https://img.shields.io/badge/Email-6E56CF?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/jaliparthiomkar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.insightsbyomkar.com"><img src="https://img.shields.io/badge/Live_Product-insightsbyomkar.com-181717?style=flat-square" /></a>
  <a href="https://kriya.insightsbyomkar.com"><img src="https://img.shields.io/badge/Live_API-Kriya_(Insights_Astrology_API)-6E56CF?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Open_to_Relocate-US_Wide-black?style=flat-square" />
  <img src="https://img.shields.io/badge/US_Work_Authorized-success?style=flat-square" />
</p>

---

### About

**Senior PM (AI Platforms) · Founding Platform PM (Series B+) · Senior TPM.** ~5 years PM/BA running multi-team Agile delivery across **$1.2M+ portfolios** at UGOX Info Tech (2017–2019) and Finest Minds Infotech (2020–2022), then three years building a six-product AI ecosystem solo since May 2023 — with cross-service contracts (shared SSO, scoped JWTs per product, HMAC across services, BFF pattern in the workbench, RLS on every user-scoped table, homegrown observability lib that replaced Sentry). Strategy, program, and code, end to end.

The studio: **Insights by Omkar** consumer SaaS at v2.214 with paying users · **Kriya** (109-endpoint commercial astronomy API on a home-grown VSOP87D + ELP/MPP02 + DOPRI8 engine, MIT SDKs in TS / Python / Go) · **Urja** (visual API + cross-provider Critic — evaluator and generator are different LLM providers by design) · **Netra** (browser-native astrology workbench, BFF pattern over Kriya) · **Studio** (cross-subdomain SSO + identity surface) · **Commandcenter** (admin) · **Bodha** (homegrown observability).

Founded **Omkar's Holistic Services LLC** (DBA *Insights by Omkar*) in May 2023. PRD → RFC → Jira → production code → postmortem. I don't hand off work I can't do myself.

---

### Numbers

<table>
<tr>
<td><b>$1.2M+</b><br/><sub>Portfolio scale</sub></td>
<td><b>6</b><br/><sub>Products in the studio</sub></td>
<td><b>v2.214</b><br/><sub>Consumer SaaS, paying users</sub></td>
<td><b>109+</b><br/><sub>Commercial API endpoints</sub></td>
<td><b>1130+</b><br/><sub>Tests (230+ Meeus golden)</sub></td>
<td><b>3</b><br/><sub>Published SDKs (TS/Py/Go)</sub></td>
</tr>
</table>

---

### Flagships

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🔮 Insights by Omkar &nbsp; <sub><i>live · v2.214 · paying users · private repo</i></sub>
Consumer AI SaaS with multi-model governance. 12+ insight modules · 4-tier subscription · multi-tier AI support · 100+ schema-enriched pages.

**Role:** Founder · Product · Program · Engineering
**Build:** continuous since 2026-03 · 30+ Supabase migrations · 5 cron jobs · dual payment rails (Stripe + PayPal) · dual AI rails (OpenAI + Anthropic)

`Next.js 16` · `Supabase + RLS` · `Stripe + PayPal` · `Claude + GPT-4o` · `Resend` · `Vercel`

**Recent strategic decisions:** Calibrate-becomes-free (the audit's #1 strategic move; flagship now leads with a free entry point) · Sessions-pivot to fully-booked + emergency-request form (kills the cold-start problem) · Calibrate-as-homepage-hero rebrand (the positioning move).

**Standouts:** two-stage AI evaluation pipeline · 6 Tier-1 AI support agents with deterministic-hash rotation + Tier-2 auto-escalation · chargeback defense baked into receipts, admin, and agent context · atomic credit architecture with automatic refund.

→ [Live product](https://www.insightsbyomkar.com) · [Case study](https://github.com/Insights-By-Omkar/insights-by-omkar-case-study)

</td>
<td width="50%" valign="top">

#### ⭐ Kriya — Insights Astrology API &nbsp; <sub><i>live · commercial · proprietary server · 109+ endpoints</i></sub>
Commercial astronomy API built from first principles. From a 43-endpoint v1 to **109+ endpoints on engine v9.x**, zero third-party astro libraries.

**Role:** Founder · Architecture · Engineering
**Build:** ~40K+ LOC ephemeris engine · 1130+ tests (230+ Meeus golden) · TS + Python + Go SDKs · tiered pricing (Free / Kriya Pro $49 / Kriya Max $149 / Enterprise)

`Next.js` · `TypeScript` · `JWT (HS256)` · `Upstash Redis` · `VSOP87D` · `ELP/MPP02` · `OpenAPI 3.1`

**Standouts:** ~1 arcsecond planet accuracy · stateless JWT + dual-backend rate limiting (Upstash + in-process fallback) · proprietary server + MIT SDKs · interactive Scalar API docs · Vimshottari dasha, primary directions, time-lord stack, returns, eclipses-personal, firdaria, lots — full predictive surface.

→ [Live API](https://kriya.insightsbyomkar.com) · [Pricing](https://kriya.insightsbyomkar.com/pricing) · [Go SDK](https://github.com/Insights-By-Omkar/kriya-go) · [Engine notes](https://github.com/Insights-By-Omkar/kriya-engine-notes) · [Case study](https://github.com/Insights-By-Omkar/insights-astrology-api-case-study)

</td>
</tr>
</table>

---

### Platform pillars &nbsp; <sub><i>case studies</i></sub>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🎯 Urja Critic &nbsp; <sub><i>cross-provider eval · v0.8</i></sub>
Cross-provider taste auditor. The LLM that judges is by design always a different provider than the LLM that generated. Public-domain reference corpus.

**Role:** Founder · Architecture
**Surface:** Critic + Illustrate + Motion + Palette + Fonts + Compose + Three (3D) + Studio app + `urja-client` v0.2.0 npm package

→ [Live API](https://urja.insightsbyomkar.com) · [Case study](https://github.com/omkarjaliparthi/urja-critic-case-study)

</td>
<td width="50%" valign="top">

#### 🪐 Netra &nbsp; <sub><i>browser-native astrology workbench · v2.32+</i></sub>
BFF pattern over Kriya — server routes compose multiple `/api/v1/*` calls and shape per-panel responses. Six chart types, research mode, AI-grounded interpretation with citations.

**Role:** Founder · Architecture · Product
**Surface:** five-panel resizable workspace · ⌘K command palette · discriminated-union research filters · markdown notes

→ [Live](https://netra.insightsbyomkar.com) · [Case study](https://github.com/omkarjaliparthi/insights-by-omkar-netra-case-study)

</td>
</tr>
</table>

---

### Portfolio

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 📋 TPM × PM Portfolio &nbsp; <sub><i>artifacts</i></sub>
PRDs, RFCs, launch checklists, postmortems, status rollups — from shipped programs.

→ [Browse](https://github.com/omkarjaliparthi/tpm-portfolio)

</td>
<td width="50%" valign="top">

#### 🏥 MediLink &nbsp; <sub><i>capstone</i></sub>
Healthcare records platform unifying patient data across providers.

**Role:** PM · 10-person team · 6 sprints
**Outcomes:** 30%+ repeat-defect prevention · 35% fewer blockers

→ [Source & team](https://github.com/omkarjaliparthi/medilink)

</td>
</tr>
</table>

---

### Decision artifacts &nbsp; <sub><i>how I think, in writing</i></sub>

- 📐 **[Portfolio strategy](https://github.com/omkarjaliparthi/tpm-portfolio/blob/main/portfolio-strategy.md)** — the dogfood-first thesis behind a multi-product solo studio. One sentence, one Mermaid diagram, why-this-order rationale.
- 📊 **[Metrics methodology](https://github.com/omkarjaliparthi/tpm-portfolio/blob/main/methodology.md)** — every headline number in this profile, defined: scope, exclusions, what it does and does not mean. Auditable.
- 💰 **[Pricing & packaging](https://github.com/omkarjaliparthi/tpm-portfolio/blob/main/pricing-and-packaging.md)** — the framework I used to price Kriya's three tiers. Tier shape before tier numbers.
- 🏛️ **[RFC · home-grown ephemeris (build vs buy)](https://github.com/omkarjaliparthi/tpm-portfolio/blob/main/rfcs/home-grown-ephemeris-engine.md)** — four-option weighted decision, four-phase implementation plan, the moat reasoning that made Kriya possible.

---

### The studio I run

**[github.com/Insights-By-Omkar](https://github.com/Insights-By-Omkar)** — the studio's public surface. Engine notes, IP playbook, case studies, published SDK. Everything I've shipped, organized.

| Repo | What's there |
|---|---|
| **[urja-critic-case-study](https://github.com/omkarjaliparthi/urja-critic-case-study)** | Cross-provider taste auditor · architecture · rubric design · public-domain corpus policy |
| **[insights-by-omkar-netra-case-study](https://github.com/omkarjaliparthi/insights-by-omkar-netra-case-study)** | Browser-native astrology workbench · BFF pattern · research mode · AI-grounded interpretation |
| **[insights-astrology-api-case-study](https://github.com/Insights-By-Omkar/insights-astrology-api-case-study)** | Kriya architecture, accuracy, source policy |
| **[insights-by-omkar-case-study](https://github.com/Insights-By-Omkar/insights-by-omkar-case-study)** | Consumer SaaS architecture, decisions, operating playbooks |
| **[kriya-go](https://github.com/Insights-By-Omkar/kriya-go)** | Official Go SDK · MIT · v1.0.0 · 109+ endpoints |
| **[kriya-engine-notes](https://github.com/Insights-By-Omkar/kriya-engine-notes)** | Accuracy methodology · Moon-residual disclosure · API-versioning policy |
| **[solo-founder-ip-playbook](https://github.com/Insights-By-Omkar/solo-founder-ip-playbook)** | Trademarks, copyright, trade-secret posture · build-in-public with costs |

---

### Strengths

**Product** — 0→1 discovery · API product design · structured-output AI UX · agent UX · pricing & packaging · developer experience
**Program** — versioned releases · pre-launch governance · incident response · cross-functional orchestration · roadmap ops
**Engineering** — full-stack TS/Next.js · Supabase + RLS · payment webhooks · multi-agent orchestration · evals · first-principles systems
**Business** — unit economics · chargeback defense · refund policy design · subscription + usage monetization · developer licensing

---

### Toolkit

`Jira` · `Confluence` · `Figma` · `ServiceNow` · `SAFe` · `Scrum` · `OKRs`
`TypeScript` · `Python` · `Go` · `Java` · `Kotlin` · `SQL` · `Next.js` · `Supabase`
`GCP` · `BigQuery` · `Upstash Redis` · `Stripe` · `PayPal` · `OpenAI` · `Anthropic` · `OpenAPI 3.1` · `TensorFlow`

---

### Credentials

| | |
|---|---|
| **M.S. Computer Science** | Pace University, NY · *Software Development & AI* · 2024 |
| **LL.B.** | *Regulatory, contracts, governance* · 2021 |
| **ICWA Intermediate** | ICAI-CMA · *Cost & management accounting* · 2020 |
| **B.Tech, Robotics** | V R Siddhartha Engineering College · 2017 |
| **Certifications** | Atlassian APM · SAFe 6 Agilist · Certified Scrum Master · IBM Deep Learning · Six Sigma Green Belt |

---

<p align="center">
<b>Open to Senior PM (AI Platforms) · Founding Platform PM (Series B+) · Senior TPM roles</b><br/>
<sub>AI platforms · Cross-provider evaluation · Developer tools · Agents · Platform PM · Evals</sub><br/>
<sub>Based in San Jose, CA · Open to relocation US-wide — comp + benefits drive the decision · NYC / SF Bay / Seattle / Remote · US work-authorized · No sponsorship needed</sub>
</p>

<p align="center">
<a href="mailto:admin@insightsbyomkar.com">admin@insightsbyomkar.com</a>
&nbsp;·&nbsp; <a href="https://www.linkedin.com/in/jaliparthiomkar">LinkedIn</a>
&nbsp;·&nbsp; <a href="https://www.insightsbyomkar.com">insightsbyomkar.com</a>
</p>

