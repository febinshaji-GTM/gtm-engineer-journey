# ForecastLoop: Ideal Customer Profile (ICP)

*Version 1.1 · Fictional company, built for the Week 1 GTM engineering exercise*

## 1. Company Snapshot

**ForecastLoop** is a pipeline forecasting and deal-risk tool for B2B SaaS sales teams, priced at **$1,200–6,000/month**. It is built for mid-market sales leaders who currently forecast from spreadsheets and gut feel. It solves missed quarterly forecasts by flagging at-risk deals from CRM activity, so revenue teams stop finding out in week 12 that the quarter is off track.

## 2. ICP Criteria

| Category | Criteria |
| --- | --- |
| Industry | B2B SaaS (core), fintech, cybersecurity, and martech |
| Company size | 50–500 employees; 8+ quota-carrying reps |
| Region | US, UK, India |
| Tech stack | Salesforce or HubSpot CRM; Slack; Gong or Outreach is a bonus |
| Triggers | Hiring a RevOps or Sales Ops role, funding in the last 12 months, new VP Sales or CRO, missed quarterly forecast |
| Disqualifiers | Under 10 employees, no dedicated sales team, B2C or transactional sales, direct competitors (Clari, BoostUp, Aviso), no CRM |

## 3. Buyer Personas

|  | **VP of Sales (economic buyer)** | **RevOps Manager (champion and user)** |
| --- | --- | --- |
| Goals | Hit the number, forecast within 5% accuracy, give the board no surprises | Build a reliable forecast process, cut manual reporting, clean up CRM data |
| Pain point 1 | Forecast calls rely on rep opinion, not data | Spends 10+ hours a week building forecast decks by hand |
| Pain point 2 | Slipped deals surface too late to recover | Reps don't update the CRM, so the data can't be trusted |
| Pain point 3 | Hard to explain misses to the CEO and board | Too many disconnected tools and dashboards to maintain |
| How they find tools | Peer referrals, CRO Slack and LinkedIn communities, analyst reports | G2 reviews, RevOps communities (RevOps Co-op, Pavilion), Google, product demos |
| Likely objections | "We already have Salesforce dashboards." "Will reps actually use it?" "Is the ROI provable this quarter?" | "Another tool to integrate and maintain." "Will it be accurate on our messy data?" "I need security and IT sign-off." |
| Messaging angle | Lead with certainty: spot the deals that will slip while there is still time to save the quarter | Lead with time saved: replace the weekly forecast deck with a live, CRM-driven view |

## 4. Scoring Model

Every lead gets two scores, plus a hard-exclusion check. **Fit** measures who they are. **Intent** measures why now. Fit alone never makes a lead Tier A, because a company that matches the profile but has no reason to act is not ready for outreach.

### Step 1: Hard exclusions (checked first)

If **any** of these is true, stop scoring and label the lead **Tier X (excluded)**:

- Under 10 employees
- No dedicated sales team
- B2C or transactional sales
- Direct competitor (Clari, BoostUp, Aviso)
- No CRM

### Step 2: Fit score (max 40)

| Signal | Points | Data source |
| --- | --- | --- |
| Employees 50–500 | +10 | LinkedIn, Apollo, or Clay enrichment |
| Target industry (SaaS, fintech, cybersecurity, martech) | +15 | Clay or Apollo company data |
| Uses Salesforce or HubSpot | +10 | Technology detection data |
| Target region (US, UK, India) | +5 | Company HQ data |

### Step 3: Intent score (max 40)

| Signal | Points | Data source |
| --- | --- | --- |
| Hiring for a sales or RevOps role | +20 | LinkedIn job posts or a jobs data provider |
| Funded in the last 12 months | +10 | Crunchbase-style funding data |
| New VP Sales or CRO in the last 6 months | +10 | LinkedIn job changes or news |

### Step 4: Tiers

| Tier | Rule | Action |
| --- | --- | --- |
| **X** | Any hard exclusion | Remove from all lists |
| **A** | Fit ≥ 25 **and** Intent ≥ 20 | Contact now, with personalized outreach within 48 hours |
| **B** | Fit ≥ 25 and Intent < 20 | Nurture with content, and re-score when a trigger fires |
| **C** | Fit < 25 | Ignore, and revisit only if the company profile changes |

### Signals not scored in version 1

| Item | Why it isn't scored |
| --- | --- |
| Missed quarterly forecast | Not visible in public data. An SDR records it manually during discovery. |
| 8+ quota-carrying reps | Estimated by counting Account Executive titles on LinkedIn and verified during qualification. |
| Gong or Outreach in the stack | A nice-to-have. It becomes a tiebreaker once there is enough data. |

## 5. Review

- **Cadence:** revisit the ICP every quarter, or after 20 or more closed deals.
- **Validate:** compare Tier A win rate, sales cycle length and average deal size against Tier B. Tier A should convert at least 2x better.
- **Owners:** RevOps maintains the scoring model, Sales gives feedback on lead quality, and Marketing aligns campaigns to Tier A and B personas.
- **Open assumptions:** price bands, the 8+ rep minimum and the India market fit are untested, so check them against the first 10 deals.
