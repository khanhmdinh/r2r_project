# SAP Functional Mini Project – Record-to-Report (R2R)

## Overview
This repository contains a self-designed SAP functional mini project focused on the **Record-to-Report (R2R)** business process for a trading company.
The goal is to demonstrate how you understand **financial processes, month-end closing and reporting** from a SAP FI/CO point of view.

This project complements the Order-to-Cash (O2C) project and can be used in your portfolio to show broader SAP functional skills.

## Business Scenario
A mid-sized B2B trading company uses an ERP/SAP-like system to record daily business transactions:
- Sales (revenue and receivables)
- Purchases (materials and payables)
- Operating expenses
- Period-end adjustments (accruals, prepayments, reclassifications)

Finance wants a more structured and transparent process for:
- Recording business events into the General Ledger
- Performing month-end closing activities
- Producing standard financial statements (Trial Balance, P&L, Balance Sheet)

## Objectives
- Design a simplified **Chart of Accounts (CoA)**.
- Map key business events to **FI postings (Dr/Cr)**.
- Document a **Record-to-Report Blueprint** including month-end closing steps.
- Create a **Functional Specification (FS)** for a monthly Profit & Loss (P&L) report by cost center.
- Simulate postings and financial statements using sample data (e.g. in Excel).

## Repository Structure (suggested)

```text
.
├── docs
│   ├── R2R_Business_Blueprint_v1.0.pdf
│   ├── R2R_PnL_By_CostCenter_FS_v1.0.pdf
│   ├── R2R_Posting_Simulation.xlsx
│   ├── R2R_Test_Cases.xlsx
│   └── R2R_Closing_Checklist_v1.0.pdf
└── README.md
```

> Note: In your real portfolio, replace these file names with your actual documents (DOCX/PDF/XLSX).

## Key Deliverables

### 1. R2R Business Blueprint
- Company and FI/CO organization structure (Company Code, Controlling Area, Cost Centers, Profit Centers).
- Simplified Chart of Accounts.
- Business events and related posting logic (Dr/Cr).
- Month-end closing process (checklists and main activities).
- High-level integration with O2C (SD-FI) and P2P (MM-FI).

### 2. Functional Specification – Monthly P&L by Cost Center
- Business requirement description (management view on cost centers).
- Selection criteria (company code, fiscal year, period, cost center range).
- Field list (accounts, descriptions, balances, cost center, period/YTD figures).
- Calculation logic and grouping rules.
- Layout and sorting requirements.
- High-level test scenarios.

### 3. Posting Simulation & Test Cases
- Sample transactional data (sales, purchases, expenses) posted into G/L.
- Trial Balance, P&L, and Balance Sheet derived from postings (e.g. using Excel formulas).
- Test cases validating:
  - Correct Dr/Cr postings
  - Zero difference between total debits and credits
  - Correct aggregation into financial statements

### 4. Month-End Closing Checklist
- Steps for period-end closing:
  - Checking open items
  - Posting accruals/deferrals
  - Running foreign currency revaluation (optional)
  - Running financial statements
- Responsibilities and timing.

## How to Use This Project in Your Portfolio
- Export the R2R Business Blueprint and FS as **PDFs** and link them in your CV/LinkedIn.
- Show that you understand how daily operations feed into FI and financial statements.
- During interviews, explain:
  - How you designed the Chart of Accounts.
  - How you mapped business events to Dr/Cr entries.
  - How you defined the month-end closing process.
  - How your P&L by Cost Center report helps management decisions.

## Skills Demonstrated
- Understanding of the Record-to-Report cycle.
- Designing a Chart of Accounts and posting logic.
- Writing Business Blueprint and Functional Specification for FI/CO processes.
- Simulating postings and constructing financial statements.
- Analytical & documentation skills related to finance and SAP FI/CO.

---

You can rename this file to `README.md` and adjust company names, dates, and file names to match your actual work.
