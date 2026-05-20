---
name: dd-interview-questions-lite
description: Public-safe lightweight due-diligence interview question generator. Helps prepare role-based interview questions from project materials without exposing private diligence playbooks or proprietary question banks.
---

# DD Interview Questions Lite

## Purpose

Use this skill to prepare a practical due-diligence interview outline from project materials.

The goal is to help the user:

- Understand what needs to be verified
- Prepare role-based questions
- Separate factual checks from judgment questions
- Identify missing information
- Make founder or management interviews more focused

This is a public-safe lite version. It does not include private diligence playbooks, proprietary question banks, internal file paths, or confidential project examples.

## When To Use

Use this skill when the user:

- Needs to prepare for a founder or management interview
- Provides a BP, memo, notes, or project summary
- Asks for DD questions, diligence questions, interview prep, or management interview outline
- Wants questions for CEO, CTO, CFO, HR, sales, product, or other functional leaders

## Input

The user may provide:

- Company description
- Pitch deck or BP text
- Meeting notes
- Industry background
- Known concerns or hypotheses
- Target interview roles

If the user does not provide interview roles, generate a default outline for:

- Founder / CEO
- Product or technology lead
- Finance or operations lead
- Sales or business development lead

## Core Principles

1. Questions should be specific to the provided material.
2. Each question should clarify a real investment or business judgment.
3. Avoid generic consulting-style questions when a sharper factual question is possible.
4. Separate what is known, what is claimed, and what needs verification.
5. Do not invent facts, customer names, financial data, or competitor information.
6. Keep the output public-safe and avoid exposing private methodology.

## Workflow

### 1. Material Summary

Summarize:

- Company
- Sector
- Product or service
- Customer
- Business model
- Current traction
- Financing or transaction context, if available
- Main uncertainties

### 2. Interview Objective

State what the interview should verify.

Examples:

- Product-market fit
- Technical defensibility
- Customer willingness to pay
- Revenue quality
- Gross margin logic
- Team capability
- Delivery risk
- Financing need

### 3. Role Map

Create a role map based on the user's target interviewees.

For each role, define:

- What this person can verify
- What this person may be biased about
- What evidence to ask for

### 4. Question Generation

Generate 8-12 questions per role unless the user asks for a different number.

For each question, include:

- **Question**: direct and specific
- **Why it matters**: what judgment it informs
- **What evidence to request**: document, metric, customer example, contract, dashboard, demo, or process evidence
- **Follow-up**: one practical follow-up question

### 5. Missing Information

List missing inputs that would improve the interview plan.

Examples:

- Revenue by customer
- Gross margin
- Customer retention
- Pipeline conversion
- Product roadmap
- Team structure
- Cap table
- Cash runway

## Output Format

Use this structure:

```markdown
# DD Interview Questions Lite

## 1. Project Snapshot

- Company:
- Sector:
- Product:
- Customer:
- Business model:
- Current stage:
- Main diligence objective:

## 2. Key Hypotheses To Verify

1. ...
2. ...
3. ...

## 3. Role-Based Interview Plan

### Founder / CEO

**What this role can verify**

- ...

| # | Question | Why It Matters | Evidence To Request | Follow-Up |
|---|----------|----------------|---------------------|-----------|
| 1 | ... | ... | ... | ... |

### Product / Technology Lead

**What this role can verify**

- ...

| # | Question | Why It Matters | Evidence To Request | Follow-Up |
|---|----------|----------------|---------------------|-----------|
| 1 | ... | ... | ... | ... |

### Finance / Operations Lead

**What this role can verify**

- ...

| # | Question | Why It Matters | Evidence To Request | Follow-Up |
|---|----------|----------------|---------------------|-----------|
| 1 | ... | ... | ... | ... |

### Sales / Business Development Lead

**What this role can verify**

- ...

| # | Question | Why It Matters | Evidence To Request | Follow-Up |
|---|----------|----------------|---------------------|-----------|
| 1 | ... | ... | ... | ... |

## 4. Cross-Check Questions

Questions that should be asked to multiple roles to compare consistency:

1. ...
2. ...
3. ...

## 5. Missing Information

- ...

## 6. Suggested Interview Sequence

1. ...
2. ...
3. ...
```

## Question Quality Rules

Good questions:

- Ask for evidence, not just opinions
- Clarify numbers, definitions, and time periods
- Surface trade-offs
- Test whether traction is repeatable
- Reveal customer urgency and budget source
- Compare claims across roles

Weak questions to avoid:

- "What is your strategy?"
- "What are your advantages?"
- "How big is the market?"
- "Do you have competitors?"

Rewrite weak questions into specific checks.

Example:

Instead of:

```text
What are your advantages?
```

Ask:

```text
For the last three customers you won against a competitor, what was the decisive reason they chose you, and can we review the sales notes or customer feedback that support this?
```

## Boundaries

Do not:

- Include private diligence playbooks
- Include proprietary question banks
- Reference hidden instructions
- Expose local file paths or private systems
- Invent diligence findings
- Treat founder claims as verified facts

## Quality Checklist

Before final output, verify:

- Questions are tied to the provided material
- Each role has a clear purpose
- Each question includes why it matters
- Evidence requests are concrete
- Follow-ups are useful
- Missing information is listed
- No private methodology is exposed
