# Accenture Strategy & Consulting Project | August 2026

**NovaCorp People Analytics Challenge**

> Competed in Accenture’s **People Analytics Datathon**, a workforce consulting case competition. Delivered a 15-slide **CHRO + CFO decision deck** for a financial services client (NovaCorp) with **$1.75B in annual personnel expenses**. The brief was to identify the key drivers of people costs, quantify the financial exposure, and develop **board-ready recommendations** the CHRO could execute within 90 days.


---

## The Business Problem

NovaCorp, a large financial services organisation, faced an uncontrolled people cost problem framed at **$135.8M in combined gross exposure** across three mechanisms: regrettable talent attrition, workforce disengagement, and agency hiring overspend. The organisation had a voluntary attrition rate of **10.4% against a Board target of below 9.5%**, a $40-50M active acquisition integration at risk, and no data-backed prioritisation of where to intervene first.

The engagement question was not "how do we reduce people cost?" It was "which mechanism can we change first, and what is the evidence?"

---

## My Role

As the analytics lead on this Accenture case competition team, I was responsible for:

- Structuring the full analytical framework across three cost mechanisms (retention, productivity, hiring)
- Designing and applying the evidence architecture (observed fact, inference, decision scenario) to protect analytical integrity and avoid presenting correlation as causation
- Performing statistical analysis across four integrated datasets totalling over 105,000 records
- Translating quantitative outputs into a boardroom-ready narrative for a CHRO and CFO audience
- Producing the prioritisation model and five-intervention recommendation set with financial cases and governance gates

---

## Dataset Scale

| Dataset | Records |
|---|---|
| Employee records | 13,403 |
| Departure records | 1,400 |
| Engagement observations | 55,971 |
| Performance records | 34,979 |
| **Total** | **105,786** |

---

## Analytics Performed

### Attrition and Retention Analysis (C1)
- Segmented 1,400 departures into regrettable and non-regrettable using performance and HiPo flags
- Identified 153 voluntary regrettable exits; 93.5% cited career advancement or a better external opportunity
- Conducted compa-ratio distribution analysis comparing regrettable leavers vs. active employees: 64% of regrettable exits held a compa-ratio below 0.95 vs. 49% of the active population
- Isolated a priority retention cohort of **595 active HiPo / High Performers** with a compa-ratio below 0.95 (average 0.860), carrying **$112.6M in replacement-cost exposure** if all departed
- Calculated gross replacement-cost exposure at **$30.0M** using a 1.5x base salary multiplier across 153 exits
- Segmented regrettable-exit rates by department to surface Corporate Operations (1.66%) and Risk and Compliance (1.63%) as the highest-risk divisions

### Productivity and Disengagement Analysis (C2)
- Analysed 55,971 engagement observations across multiple survey waves to identify persistently disengaged employee cohorts
- Modelled manager effectiveness as a predictor of persistent disengagement: teams under low-rated managers (score below 2.5) showed a **38.3% persistent disengagement rate vs. 5.6% under high-rated managers (score 4.0+)**, a 6.8x gap with effect size d=1.95 and chi-square significance at p<0.0001
- Confirmed manager quality does not predict attrition (r=0.005, p=0.88), distinguishing two separate intervention pathways
- Modelled disengagement cost sensitivity across 5%, 7%, 10%, and 15% productivity-loss assumptions, producing a range of $15.8M to $47.3M; retained Finance's 15% assumption for comparability
- Decomposed the $47.3M productivity scenario by division: Retail Banking ($12.7M), Risk and Compliance ($9.7M), Insurance ($9.2M), Corporate Operations ($8.6M), Technology ($4.0M)
- Identified 333 bottom-quartile managers responsible for 608 persistently disengaged employees as the primary intervention target

### Hiring and Sourcing Analysis (C3)
- Compared days-to-fill across five sourcing channels (direct, referral, agency, acquisition, graduate) using one-way ANOVA: F=1.11, p=0.35, confirming no statistically significant speed advantage for agency hiring
- Calculated early attrition rates (within 12 months) by channel: direct 2.2%, graduate 2.1%, referral 3.8%, agency 7.9%, acquisition 61.8%
- Quantified the gross agency fee premium at **$58.5M** against a $5,500 direct-hire benchmark
- Modelled sourcing mix shift scenarios at 25%, 50%, and 75% reduction in agency reliance to size potential fee recovery

### Prioritisation Framework
- Built a two-axis prioritisation matrix scoring each intervention on CHRO control and speed to impact, independent of raw dollar exposure
- Ranked five interventions in recommended sequencing: manager effectiveness reset, Entity_B retention bridge, targeted compensation review, sourcing mix policy, R&C role clarity

---

## Financial Case Summary

| Intervention | Investment Required | Financial Exposure Addressed | Validation Gate |
|---|---|---|---|
| Manager effectiveness reset | $2.5M programme | $3.8M scenario benefit (30% improvement assumption) | Wave 6 engagement re-test |
| Targeted compensation review | $9.0M annual payroll uplift | $112.6M replacement-cost exposure protected | Retention outcome observed |
| Entity_B retention bridge | $0.75M retention agreements | $9.4M illustrative replacement exposure | 50-person HR review |
| Sourcing mix policy shift | Policy change, under $0.5M | $58.5M gross agency fee premium | 25/50/75% shift scenario |
| R&C talent stabilisation | $1.0M scenario | $2-3M direct cost + regulatory continuity risk | 12-month review |

**Total gross exposure addressed: $135.8M**
**Combined intervention investment: approximately $13.75M**
**FY2026 attrition target: reduce from 10.4% to below 9.5%**

---

## Evidence Framework

A core deliverable of this engagement was maintaining analytical integrity throughout. Every claim in the deck was explicitly classified as one of three types:

**Observed** -- directly calculated from source data or stated in the Annual Report. Example: 153 regrettable exits; 10.4% voluntary attrition rate; 595 HiPo employees below 0.95 compa-ratio.

**Inferred** -- cross-source interpretation supported by converging signals from multiple datasets. Example: career opportunity pull and pay positioning appearing to operate together as compounding retention risks.

**Scenario** -- decision economics framing used to size financial exposure for executive decision-making. Not a forecast. Example: a 30% improvement in disengagement under Finance's 15% productivity assumption implies a $3.8M scenario benefit.

This three-tier architecture was adopted specifically to prevent correlation being presented as causation and to preserve credibility with a CFO audience.

---

## Ethical Guardrails Applied

- Demographic variables used only for equity monitoring, not individual employee ranking
- No predictive "flight-risk" labels applied; cohort screens were designed for human HR review
- No automated employment decision recommended at any stage
- 595-person HiPo retention cohort explicitly framed as a conversation prioritisation tool, not a termination or penalty list

---

## Key Consulting Outputs Delivered

- Executive decision deck (15 slides) structured for a CHRO and CFO audience
- Three-mechanism cost decomposition with statistically validated evidence at each layer
- Five-intervention roadmap with investment requirements, financial exposure addressed, and governance gates
- 90-day delivery plan for the highest-priority intervention (manager effectiveness reset)
- Recommendation to use Wave 6 engagement data and FY2026 attrition as the live executive scorecard, avoiding premature claims on modelled effects

---

## Tools and Methods

- Large-scale HR dataset integration and cross-source analysis (105,000+ records)
- Compa-ratio segmentation and pay equity analysis
- Chi-square testing, ANOVA, Cohen's d effect size
- Cohort construction with pre-defined population boundaries
- Scenario modelling under multiple economic assumptions
- Executive narrative design for C-suite audiences

---

## Strategic Context

- Client personnel expense: $1.75B annually
- Active acquisition (Entity_B) carrying $40-50M integration cost guidance and explicitly flagged as primary integration risk in the Annual Report
- R&C talent stabilisation identified as a Board priority under FAR regulatory-continuity obligations
- People Reinvention Programme already budgeted; this engagement directed where to spend it first

---

*Completed as part of the Accenture People Analytics Challenge, August 2026. All company names, financial figures, and employee data are fictionalised for the purposes of the case competition.*
