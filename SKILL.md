---
name: us-legal-mcp-skill
description: Official United States (US) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# United States Legal Research & Multi-Tier Case Law Skill (`us-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **United States (US)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `42 U.S.C. § 1983, 17 U.S.C. § 107, 410 U.S. 113, or 21 C.F.R. § 314.50`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** 94 U.S. Federal District Courts, U.S. Bankruptcy Courts, U.S. Court of International Trade & State Trial/Superior Courts
   - **Second Instance (Cantonal / Regional / Appellate):** 13 U.S. Circuit Courts of Appeals (1st–11th, D.C., Federal Circuit) & 50 State Intermediate Appellate Courts
   - **Supreme & Constitutional Instance:** Supreme Court of the United States (SCOTUS) & 50 State Supreme Courts / Courts of Last Resort
   - **Primary Tiered Database:** CourtListener / Free Law Project Multi-Tier Federal & State Database (courtlistener.com) (`https://www.courtlistener.com/api/rest/v4/search/`)
