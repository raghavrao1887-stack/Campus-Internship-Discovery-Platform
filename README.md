# Campus Internship Discovery Platform

### 0→1 Product Case Study — Research, Prioritization, PRD & Prototype

A product case study exploring how IIT students discover internships, track application deadlines, and prepare for online assessments.

**Role:** Product — Solo  
**Author:** Rao  
**Program:** B.Tech Mechanical Engineering, IIT Ropar  
**Status:** Clickable Figma prototype + Round 1 research complete

---

## 🔗 Prototype

**[View Interactive Figma Prototype](YOUR_FIGMA_LINK_HERE)**

---

## 📌 Project Snapshot

| Area | Decision |
|---|---|
| Problem | Internship opportunities are scattered across multiple channels, causing missed opportunities and deadlines |
| Primary users | 3rd-year and final-year students |
| Secondary users | 2nd-year students |
| MVP wedge | Deadline tracker + curated feed + lightweight OA prep path |
| North Star | Qualified applications per user per month |
| Research | 3 student interviews |
| Prototype | Clickable mobile-first Figma prototype |
| Deferred | Resume matching + alumni referrals |

---

# 1. Problem

IIT students discover internships and placement opportunities across multiple channels:

- Career Development & Placement Cell (CDPC)
- Internshala
- LinkedIn
- WhatsApp / Telegram groups
- Alumni outreach
- Personal alerts and search workflows

Because these channels operate independently and application windows can be short, students can miss relevant opportunities even when they are actively looking.

### Problem Statement

> **Students need a single, reliable way to discover relevant internships, track deadlines, and prepare for assessments. Today they rely on scattered sources and personal workarounds, which leads to missed opportunities and wasted effort.**

The project focused on three core problems:

1. **Discovery** — finding relevant opportunities without checking multiple sources.
2. **Deadlines** — remembering and acting before application windows close.
3. **Preparation** — knowing what to prepare for a specific role or company.

---

# 2. Research

## Research Approach

I conducted short structured conversations with students covering:

- How they currently find internships
- The last opportunity they missed and why
- How they prepare for online assessments
- The single thing they would improve in their current workflow

### Round 1

**n = 3 students**

- 2 × 3rd-year Mechanical Engineering
- 1 × 2nd-year student

### Key Findings

**1. Awareness and timing are major problems**

Both 3rd-year students had missed opportunities because they were unaware of them.

**2. Students already build their own workarounds**

Examples included:

- Gmail + ChatGPT alerts
- Active LinkedIn searching
- Internshala
- Cold-emailing alumni

This suggested that the real competitor was not another internship platform — it was the student's existing workflow.

**3. OA content already exists**

Students already use resources such as PYQs, preparation platforms and AI tools.

The gap was not necessarily more content.

The gap was:

> **Knowing where to start and what to prepare for a specific role.**

**4. Alumni referrals require trust**

Interest in referrals existed, but students wanted college certification and verification of student quality before trusting such a system.

---

# 3. Research → Product Insight

The research changed the initial product direction.

### Initial assumption

Build a broader internship platform containing:

- Internship discovery
- Deadline tracking
- OA preparation
- Resume matching
- Alumni referrals

### What the research suggested

The MVP should focus on the highest-value workflow instead of trying to solve everything.

### Final MVP Direction

> **Curated internship discovery + deadline tracking + lightweight role-specific OA guidance**

Resume matching and alumni referrals were moved to a later version because they require additional data, trust and supply-side validation.

---

# 4. Target Users

## The Explorer — 2nd Year

**Goal:** Find direction and land a first serious internship.

**Behavior:**
- Exploring finance, non-core and core Mechanical paths
- Browses without a fixed target
- Unsure where to start with preparation

**Needs:**
- Relevant opportunities
- A clear starting point
- Lightweight preparation guidance

---

## The Grinder — 3rd Year

**Goal:** Secure a strong internship/PPO and prepare for recruitment.

**Behavior:**
- Uses multiple platforms simultaneously
- Searches LinkedIn
- Uses alerts
- Cold-emails alumni
- Prepares using PYQs and preparation platforms

**Pain Points:**
- Scattered information
- Missed opportunities
- Deadline pressure
- Unclear preparation requirements

**Needs:**
- One place for relevant roles
- Deadline reminders
- Application tracking
- Role-specific preparation guidance

---

## The Closer — Final Year

**Goal:** Convert applications into a full-time opportunity.

**Hypothesized needs:**
- Full-time role discovery
- Deadline calendar
- Resume tailoring
- Referral access

**Status:** Untested in Round 1 and planned for further research.

---

# 5. Competitive Landscape

| Alternative | Strength | Gap |
|---|---|---|
| WhatsApp / Telegram | Fast, familiar, already part of daily habits | Unstructured; no personalization or tracking |
| CDPC | Authoritative for on-campus roles | One-way communication; easy to miss |
| LinkedIn | Large reach and alumni network | Noisy and not optimized for student timelines |
| Internshala / Unstop | Large listing volume | Generic discovery and weak deadline workflow |
| DIY alerts | Personalized and flexible | Requires individual effort and fragmented coverage |

### Key Competitive Insight

The biggest competitor is the student's **existing habit of checking multiple sources**.

Therefore, the product needs to be:

- Faster
- More relevant
- Better curated
- More reliable around deadlines

---

# 6. Feature Prioritization

I used the **RICE framework**:

> **RICE = (Reach × Impact × Confidence) ÷ Effort**

| Feature | Reach | Impact | Confidence | Effort | RICE |
|---|---:|---:|---:|---:|---:|
| Deadline tracker | 1000 | 2 | 70% | 2 | **700** |
| Curated / personalized feed | 1000 | 2 | 70% | 4 | **350** |
| OA prep path | 800 | 2 | 50% | 3 | **267** |
| Resume matcher | 600 | 2 | 50% | 6 | **100** |
| Alumni referrals | 500 | 3 | 50% | 8 | **94** |

### MVP Decision

The MVP became:

**1. Deadline tracker**  
**2. Curated internship feed**  
**3. Lightweight OA preparation path**

### Deferred to V2

- Resume-to-JD matching
- Alumni referral marketplace

The decision was driven by effort, evidence strength, data dependencies and trust requirements.

---

# 7. Product Requirements

## Objective

Help IIT students avoid missing relevant internship and placement windows while surfacing opportunities and preparation guidance matched to their profile.

### MVP Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| F1 | Role feed with year, branch, role type, location and deadline filters | Must |
| F2 | Profile setup with year, branch, skills and interests | Must |
| F3 | Save roles and set deadline reminders | Must |
| F4 | Deadline tracker with list and calendar views | Must |
| F5 | Basic rule-based recommendations | Should |
| F6 | Curated, company-wise OA preparation path | Should |

### V2

| Feature | Reason |
|---|---|
| Resume-to-JD matching | Requires stronger validation and JD data |
| Alumni referrals | Requires trust, verification and alumni supply |

---

# 8. Core User Flow

```text
Profile Setup
      ↓
Personalized Internship Feed
      ↓
Role Details
      ↓
Save Opportunity
      ↓
Set Deadline Reminder
      ↓
OA Preparation Path
      ↓
Apply
      ↓
Track Application Status
