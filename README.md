<div align="center">

<br/>

<!-- LOGO / BANNER -->
<img src="https://img.shields.io/badge/SkillSetu__AI-PM%20Portfolio-0A2540?style=for-the-badge&logo=openai&logoColor=white" alt="SkillSetu_AI Banner" height="48"/>

<br/><br/>

# 🎯 SkillSetu_AI
### *AI-Powered Skill Assessment & Personalised Learning Path Platform*

<br/>

> **A Product Management portfolio project** exploring how artificial intelligence can close the gap between where professionals are today and where they aspire to be — through smart assessments, dynamic learning journeys, and outcome-driven growth plans.

<br/>

[![Status](https://img.shields.io/badge/Status-Concept%20%2F%20MVP-orange?style=flat-square)](.)
[![Type](https://img.shields.io/badge/Type-PM%20Portfolio%20Showcase-0A2540?style=flat-square)](.)
[![Domain](https://img.shields.io/badge/Domain-EdTech%20%7C%20AI%20%7C%20Career%20Growth-6C63FF?style=flat-square)](.)
[![Author](https://img.shields.io/badge/Author-PM%20Portfolio-2ECC71?style=flat-square)](.)

<br/>

---

</div>

## 📌 Table of Contents

- [Problem Statement](#-problem-statement)
- [Product Vision](#-product-vision)
- [How It Works](#-how-it-works)
- [Core Features](#-core-features)
- [User Journey](#-user-journey)
- [Product Architecture](#-product-architecture)
- [Key Metrics (North Star)](#-key-metrics-north-star)
- [Roadmap](#-roadmap)
- [PM Learnings & Insights](#-pm-learnings--insights)
- [About This Project](#-about-this-project)

---

## 🧩 Problem Statement

<div align="center">

> *"Professionals know they need to grow — but they don't know **where** to start, **what** to learn, or **how** to measure progress."*

</div>

<br/>

| Pain Point | Impact |
|:-----------|:-------|
| 📉 Generic learning platforms offer one-size-fits-all courses | Low completion rates, poor skill retention |
| 🔍 No personalised gap analysis against real job requirements | Learners study the wrong skills |
| 🤖 Manual assessment is time-consuming and biased | Delayed, inaccurate feedback loops |
| 📊 No visibility into measurable skill progress over time | Low motivation, high dropout |

---

## 🌟 Product Vision

<div align="center">

**"Empowering every professional to know exactly what skill to build next — and giving them the clearest, fastest path to get there."**

</div>

<br/>

SkillSetu_AI is envisioned as an intelligent career co-pilot that:

- **Assesses** current skills using AI-driven diagnostics
- **Maps** gaps against target roles or industry benchmarks
- **Generates** personalised, adaptive learning paths
- **Tracks** growth with data-backed milestones and nudges

---

## ⚙️ How It Works

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                        SKILLSETU_AI FLOW                        │
└─────────────────────────────────────────────────────────────────┘

         ┌──────────┐       ┌──────────────┐       ┌────────────┐
         │          │       │              │        │            │
  USER ──►  Profile  ├──────► AI  Skill     ├───────►  Gap        │
         │  Setup   │       │  Assessment  │        │  Analysis  │
         │          │       │              │        │            │
         └──────────┘       └──────────────┘        └─────┬──────┘
                                                           │
                    ┌──────────────────────────────────────┘
                    ▼
         ┌──────────────────┐       ┌──────────────────┐
         │                  │       │                  │
         │  Personalised    │──────►│  Progress        │
         │  Learning Path   │       │  Tracking &      │
         │  (AI Generated)  │       │  Nudges          │
         │                  │       │                  │
         └──────────────────┘       └──────────────────┘
                    │
                    ▼
         ┌──────────────────┐
         │   Outcome:       │
         │   ✅ Skill        │
         │      Uplift      │
         │   ✅ Role         │
         │      Readiness   │
         └──────────────────┘
```

</div>

---

## 🚀 Core Features

<div align="center">

| # | Feature | Description | Priority |
|:-:|:--------|:------------|:--------:|
| 1 | **AI Skill Diagnostic** | Adaptive questionnaire + scenario-based tests to assess real competency | 🔴 P0 |
| 2 | **Gap Mapper** | Benchmarks user skills vs. target role or industry standard | 🔴 P0 |
| 3 | **Learning Path Engine** | AI curates a step-by-step, personalised curriculum from vetted sources | 🔴 P0 |
| 4 | **Progress Dashboard** | Visual skill growth tracker with milestones and completion badges | 🟡 P1 |
| 5 | **Role Readiness Score** | A single score showing readiness for a target job role | 🟡 P1 |
| 6 | **AI Mentor Nudges** | Proactive check-ins, reminders, and adaptive path adjustments | 🟢 P2 |
| 7 | **Peer Benchmarking** | Compare growth with anonymised cohort data | 🟢 P2 |

</div>

---

## 🗺️ User Journey

<div align="center">

```
PERSONA: Priya — A mid-level professional targeting a Product Manager role
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  STEP 1          STEP 2          STEP 3          STEP 4
  ────────        ────────        ────────        ────────
  Signs up   ──►  Takes 20-min ──►  Views her   ──►  Starts her
  & sets         AI assessment     Skill Gap        personalised
  target role    (adaptive)        Report           learning plan

  STEP 5          STEP 6          STEP 7
  ────────        ────────        ────────
  Completes  ──►  Gets Role   ──►  Shares
  modules &       Readiness        certificate
  earns badges    Score: 87%       on LinkedIn

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  EMOTION:   😟 Confused  →  😮 Surprised  →  😊 Motivated  →  🎉 Confident
```

</div>

---

## 🏗️ Product Architecture

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                    PRODUCT LAYER VIEW                       │
├──────────────────┬──────────────────┬───────────────────────┤
│   FRONTEND       │   AI / LOGIC     │   DATA & CONTENT      │
│   (User Layer)   │   (Core Engine)  │   (Knowledge Layer)   │
├──────────────────┼──────────────────┼───────────────────────┤
│                  │                  │                       │
│  • Onboarding    │  • NLP Assessment│  • Skill Taxonomy DB  │
│  • Dashboard     │    Engine        │  • Role Benchmarks    │
│  • Learning      │  • Gap Analysis  │  • Curated Content    │
│    Path View     │    Algorithm     │    Library            │
│  • Progress      │  • Path          │  • Industry           │
│    Tracker       │    Generator     │    Standards Map      │
│  • Profile &     │  • Nudge &       │                       │
│    Settings      │    Reminder AI   │                       │
│                  │                  │                       │
└──────────────────┴──────────────────┴───────────────────────┘
```

</div>

---

## 📊 Key Metrics (North Star)

<div align="center">

| Metric | Definition | Target |
|:-------|:-----------|:------:|
| 🌟 **Skill Uplift Rate** | % of users who improve their role readiness score within 60 days | > 70% |
| 📈 **Path Completion Rate** | % of users who finish their AI-generated learning path | > 40% |
| ⏱️ **Time to First Insight** | Minutes from sign-up to receiving a personalised Gap Report | < 25 min |
| 🔁 **7-Day Retention** | % of users who return within 7 days of completing assessment | > 55% |
| 😊 **NPS Score** | Net Promoter Score from active learners | > 45 |

</div>

---

## 🗓️ Roadmap

<div align="center">

```
PHASE 1 — DISCOVER        PHASE 2 — DEFINE         PHASE 3 — DELIVER
(Month 1–2)               (Month 3–4)               (Month 5–6)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
✅ User research           ✅ PRD & Wireframes        🔲 MVP Launch
✅ Competitive analysis    ✅ User flow mapping       🔲 Beta user testing
✅ Problem definition      🔲 Prototype (Figma)       🔲 Metric baselining
✅ Persona creation        🔲 Stakeholder review      🔲 Iteration cycle 1
```

</div>

---

## 💡 PM Learnings & Insights

This project reflects my practical application of core PM frameworks:

**Discovery & Research**
- Conducted user interviews with 10+ professionals across domains to validate the skill-gap problem
- Mapped the competitive landscape (Coursera, LinkedIn Learning, Pluralsight) to identify white spaces

**Prioritisation**
- Applied the **RICE framework** to prioritise features (Reach × Impact × Confidence ÷ Effort)
- Used **MoSCoW method** for MVP scoping: Must-have vs. Should-have vs. Could-have

**Product Thinking**
- Defined the North Star Metric as **Skill Uplift Rate** — anchoring all decisions to user outcome, not engagement vanity metrics
- Modelled the product around a **Jobs-to-be-Done** lens: *"When I feel stuck in my career, I want to know exactly what skill to build next, so I can move toward my goal with confidence."*

---

## 👤 About This Project

<div align="center">

| | |
|:-|:-|
| **Project Type** | Product Management Portfolio Showcase |
| **Domain** | EdTech · AI · Career Development |
| **Frameworks Used** | RICE, MoSCoW, JTBD, North Star Metric, User Story Mapping |
| **Artefacts Included** | Problem Statement, PRD Concept, User Journey, Roadmap, Metrics |
| **Status** | Concept Stage — open to collaboration & feedback |

<br/>

---

*Built with product thinking, user empathy, and a belief that the right skill, learned at the right time, changes careers.*

<br/>

**⭐ If this project resonates with you, give it a star — it helps others discover it.**

</div>
