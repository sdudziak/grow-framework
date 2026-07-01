# GROW Framework — Documentation

**Context:** Built while scaling an engineering department from 4 to 70+ engineers. Used in production across multiple teams for several years.
**Format:** Excel workbook (`GROW_Framework_v2_EN.xlsx`)
**License:** Creative Commons Attribution 4.0 (CC BY 4.0) — free to use, share, and adapt with attribution.
**Status:** Available for reuse. No corporate IP claim — never signed over.

---

## What Problem It Solved

Before GROW, seniority was assigned informally — by gut feel of a single team lead.
This created:
- Disputes over promotions ("why is X a Senior and I'm not?")
- Inconsistency across teams (Senior on one project ≠ Senior on another)
- No shared language for growth conversations
- No objective basis for salary adjustments tied to level

After GROW, no seniority decision was contested. Not one. The framework scaled beyond
what any single person could influence directly — team leads across all teams adopted it,
ran their own evaluations, and produced consistent, defensible outcomes.

---

## Structure — The Workbook

6 sheets, one evaluation per person:

| Sheet | Who fills it | Purpose |
|-------|-------------|---------|
| `Evaluation Rules` | Reference | Rules, process, scoring explanation |
| `Subject Criteria` | Subject (self) | Self-assessment of all criteria |
| `Leader Criteria` | Direct Team Lead | Leader's independent assessment |
| `HR Criteria` | HR | HR's independent assessment |
| `Overseer Criteria` | Cross-team Senior/Lead | External validation for contested cases |
| `Assessment & Feedback` | HR + Leader | Conclusions, gap analysis, IDP |

**Key design principle:** each perspective fills in independently before any discussion.
Discrepancies between self-assessment, leader, and HR are flagged — the gap itself is the input
to the feedback conversation, not a bug in the process.

---

## The 4 Levels

| Level | Tag | Experience threshold |
|-------|-----|---------------------|
| Junior | `#apply` — tries, follows, applies | 0.5–2.5 yrs commercial |
| Mid | `#enable` — independent, self-sufficient | 2–5 yrs |
| Senior | `#ensure/advise` — guarantees quality, advises | 5+ yrs |
| Expert / Architect | `#initiate/influence` — initiates, inspires, drives | 7+ yrs |

The tags aren't decorative. They describe the **direction of impact**:
- Junior's impact is inward (on their own work)
- Mid's impact is self-directed (unblocks themselves)
- Senior's impact is team-directed (unblocks others, sets standards)
- Expert/Architect's impact is organisation-directed (changes how the company works)

---

## The 8 Evaluation Categories

Each category has level-specific criteria. All 4 levels assessed side-by-side.

### Section A — Project Work
| Category | What it measures |
|----------|----------------|
| **Code quality** | Clean code, testing, documentation, review capability, propagating standards |
| **Task estimation** | Accuracy, handling estimation failure, helping others estimate |
| **Independence / scope** | Can operate without supervision, handles ambiguity, unblocks others |

### Section B — Competencies
| Category | What it measures |
|----------|----------------|
| **Knowledge** | Depth in primary technology + breadth across adjacent areas; SDLC; business understanding |

### Section C — Skills
| Category | What it measures |
|----------|----------------|
| **Technical skills** | Tool mastery, paradigms, design patterns, testing, tech selection, risk identification |
| **Language skills** | Verbal + written foreign language (typically English); progression: clear → correct → fluent → negotiation-capable |
| **Teamwork** | Collaborative vs. competitive instinct; conflict resolution; team spirit cultivation |

### Section D — Attitude
| Category | What it measures |
|----------|----------------|
| **Growth, engagement, motivation, communication, relationships** | Self-directed development plan, SMART goals, proactivity, stability of motivation, internal vs. external drive, cross-department collaboration |

---

## The Scoring System

Each criterion is scored with exactly one of four values:

| Mark | Meaning |
|------|---------|
| **YES** | Criterion clearly present |
| **PARTIAL** | In progress — being acquired, or present selectively |
| **NO** | Not present |
| **N/A** | Not applicable — criterion doesn't exist in this engineer's project context, or the evaluator lacks data |

**The N/A column is critical.** It prevents engineers from being penalised for things outside
their control (e.g., scoring NO on "leads client calls" if their project has no client contact).
It also prevents evaluators from scoring things they genuinely can't observe.

### Threshold to qualify for a level

> Pass condition: **>50% in every individual category** AND **average score ≥70%** across all categories.

This is a dual gate, not a single average. An engineer who scores 100% on code quality and 0%
on teamwork does not qualify — the 50% floor prevents outlier compensation. The 70% average
ensures the bar is meaningful.

**PARTIAL scoring:** counts as 0.5 YES in the percentage calculation. Not zero, not one — acknowledges
partial acquisition honestly.

---

## The Senior / Expert Self-Assessment Gate

Before formal evaluation of Senior or Expert/Architect level, the subject completes
9 reference questions. These are calibration questions — the answers inform whether the formal
evaluation should proceed at that level at all.

1. Can I identify bad practices and non-standard approaches on a project?
2. Can I locate their root causes?
3. Can I independently begin paying down technical debt?
4. Can I prepare an argument to convince management to allocate time for it?
5. Can I select the right technologies for a project's requirements?
6. Can I predict which technological direction the industry will move in?
7. Can I show less experienced colleagues their development path?
8. Can I smoothly migrate an existing architecture to a new one?
9. Can I minimise the impact of past poor architectural decisions?

These questions are not scored by the formula — they're reflective prompts. If the subject
cannot answer yes to most of them, the evaluation stays at Mid level regardless of project tenure.
This prevents time-in-role from driving promotions instead of actual capability.

---

## The Evaluation Process

**Who participates (minimum):** Subject + HR + Direct Team Lead. 3 people required.
**Optionally:** Overseer (cross-team Senior/Lead) — for contested cases or when the Lead lacks data.
**When:**
- New hire: first evaluation within 3 months (after onboarding, not before)
- Junior / Mid: every 6 months
- Senior / Mid: every 12 months
- Expert: individually, per agreed development plan

**Process:**
1. Subject is notified in advance — enough time to prepare honestly
2. All parties fill in their respective sheets **independently, before discussion**
3. Sheets compared — discrepancies identified
4. Feedback meeting: HR + Leader deliver findings; Overseer attends if needed
5. Individual Development Plan (IDP) created from gap analysis
6. SMART goals set for the next cycle

**On extreme discrepancies:** if self-assessment and leader assessment differ by more than
one seniority band, this is flagged as a signal — either the engineer is in the wrong role
(under/over-levelled) or the leader lacks visibility into the engineer's actual work.
Both outcomes require action, not just averaging.

---

## What Makes It Different

| Most "seniority frameworks" | GROW |
|----------------------------|------|
| Single evaluator | 3–4 independent perspectives |
| Gut-feel holistic judgment | 8 explicit categories with level-specific criteria |
| Pass/fail or 1–5 scale | YES/PARTIAL/NO/N/A — acknowledges partial acquisition + inapplicability |
| Average across categories | Dual gate: floor per category + overall average |
| Defined by management | Transparent to engineers — criteria visible before evaluation |
| Applied top-down | Self-assessment built in as first layer |
| Focused on output | Includes attitude, language, teamwork — not just technical delivery |

---

## Outcomes

- **Zero contested seniority decisions** after GROW adoption
- Adopted by all team leads across multiple teams — culture scaled beyond direct influence
- Engineers knew what they were working toward between cycles (the criteria are the roadmap)
- Underperformance near zero — not because of enforcement, but because the framework makes
  growth gaps visible early enough to address them with IDPs before they become performance issues
- Enabled scaling the engineering department while maintaining consistent standards

---

## Authors

- Szymon Dudziak
- Katarzyna Lasoń
- Adam Biegański

---

## Availability & Attribution

Free to use under CC BY 4.0. Required credit line on any use or derivative:

> *GROW Framework — by Szymon Dudziak, Katarzyna Lasoń, Adam Biegański. CC BY 4.0.*

Canonical source: https://github.com/sdudziak/grow-framework

License: [CC BY 4.0](./LICENSE) — `SPDX-License-Identifier: CC-BY-4.0`
Workbook: [`GROW_Framework_v2_EN.xlsx`](./GROW_Framework_v2_EN.xlsx)
