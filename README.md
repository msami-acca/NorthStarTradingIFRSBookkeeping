# Project Overview

**NorthStar Trading Ltd** is a fictional UK-incorporated private company engaged in **B2B technology equipment distribution**.

This project demonstrates a an end-to-end accounting cycle in Excel, starting from source transactions and ending with closing entries and the post-closing trial balance.

| Item | Details |
| --- | --- |
| Company | NorthStar Trading Ltd |
| Industry | B2B Technology Equipment Distribution |
| Legal form | UK private company |
| Accounting framework | IFRS Accounting Standards |
| Functional / presentation currency | USD |
| Accounting period | 1–31 January 2026 |
| Project role | Junior Financial Accountant - Simulated Project |

---

# Disclaimer

NorthStar Trading Ltd is a **fictional company created for educational and portfolio purposes**.

All transactions, customers, suppliers, balances, assumptions and financial information are fictional.

This project should not be interpreted as professional accounting advice or as evidence of employment/client experience.

---

# 1. Objective

The project demonstrates:

**Source Transactions → General Journal (including source transactions and month-end adjusting entries) → General Ledger  → Adjusted Trial Balance → Financial Statements → Closing Entries → Post-Closing Trial Balance → Ratio Computation**

It covers double-entry bookkeeping, receivables/payables, accruals, prepayments, PPE, depreciation, inventory valuation, financing, revenue, cost of sales, financial statements, closing entries, ratio computation and practical Excel implementation.

---

# 2. Source Transactions

The following fictional transactions were recorded using the double-entry accounting system.

#### Transactions

**1 January:** Issued $500,000 ordinary shares for cash; proceeds deposited into the USD bank account.

**2 January:** Paid $12,000 legal/professional costs directly related to company establishment.

**3 January:** Purchased office furniture for $24,000 through the bank. Useful life: 5 years; residual value: $0; straight-line depreciation.

**4 January:** Purchased computer equipment for $30,000 through the bank. Useful life: 3 years; residual value: $0; straight-line depreciation.

**5 January:** Paid $8,000 office rent for January.

**6 January:** Paid $12,000 for 12 months of insurance commencing 1 January.

**7 January:** Purchased stationery for $1,800 by bank transfer.

**8 January:** Purchased inventory costing $75,000 from Alpha Supplies on credit.

**9 January:** Paid $3,000 freight/handling directly relating to the Alpha inventory purchase.

**10 January:** Purchased inventory costing $60,000 from Beta Distribution, paid through bank.

**11 January — Customer A:** Credit sale $110,000; cost of inventory sold $63,000.

**12 January:** Returned inventory costing $8,000 to Alpha Supplies due to defects.

**14 January:** Bank sale $55,000; cost of inventory sold $31,000.

**15 January:** Purchased inventory costing $244,000 from Gamma Tech on credit.

**17 January — Customer B:** Credit sale $135,000; cost of inventory sold $78,000.

**18 January:** Paid Alpha Supplies $40,000 against its payable.

**20 January:** Customer A paid $70,000 against its receivable.

**21 January — Customer B return:** Goods with selling price $12,000 and cost $7,000 were returned. Goods are saleable and returned to inventory.

**22 January:** Obtained a $150,000 three-year bank loan at **8% annual interest**.

**23 January:** Bank sale $80,000; cost of inventory sold $46,000.

**24 January:** Bank deducted a $2,000 loan arrangement fee from the loan proceeds.

**25 January — Customer C:** Credit sale $150,000; cost of inventory sold $87,000.

**26 January:** Paid salaries of $18,000.

**27 January:** Customer B paid $90,000 against its receivable.

**28 January:** Paid advertising expenses of $5,000.

**29 January — Customer D:** Received $30,000 advance for goods to be supplied in February. For this project, record the advance using **Prepaid Income**.

**29 January:** Paid electricity/utilities of $4,500.

**30 January:** Paid bank charges of $2,000.

**31 January:** Paid professional accounting fees of $6,000.

---

# 3. Month-End Adjustments — 31 January 2026

1. Salaries of **$2,500** have been incurred but not yet paid.
2. Utilities of **$1,200** have been incurred but not yet paid.
3. Straight-line depreciation:
    1. Furniture **(cost:** $24,000 / life: 5 years) = $400 
    2. Computer equipment **(cost:** $30,000 / life: 3 years) = $833.33
4. Insurance: $12,000 covers 12 months beginning 1 January.
5. Inventory Valuation: Included in the inventory (valued at $76,000) are items costing $5,000 with an estimated selling price of $3,800 and costs to sell of $300 (i.e. NRV = $3,500)
6. Loan Interest: $150,000 loan at 8% annual interest; one month of accrued interest = $1,000.
7. Income Tax
    1. For project completeness, an income tax expense of $45,000 is assumed
    2. This is a **project assumption**, not an actual tax computation for a real company.

---

# 4. Financial Statements

Following financial statements have been prepared throughout the project:

1. SOPL - Statement of Profit or loss (Income Statement)
2. SOFP - Statement of Financial Position (Balance Sheet)
3. SOCF - Statement of Cash Flows

# 5. Closing Entries

Relevant entries have been made to close the following temporary accounts into the Retained Earnings account: Revenue, Sales returns, Cost of sales, Inventory write-down, Salaries & wages, Rent, Insurance, Advertising, Utilities, Stationery, Professional fees, Depreciation, Loan interest, Bank charges and Income tax expense. 

These entries have resulted in the closing balances of above mentioned account to become zero and the profit to be transferred to the Retained Earnings account

---

# 6. Project Assumptions and Simplifications

These are intentional project decisions and should not be treated as errors when reviewing the workbook.

### Income Tax

The $45,000 income tax expense is a project assumption used for completeness.

### Loan Arrangement Fee

The $2,000 arrangement fee is handled using a simplified treatment appropriate to the project's current learning level. A more advanced IFRS 9 model would consider transaction costs and the effective interest rate.

### Bank Instead of Cash on Hand

Bank/bank-sale transactions are recorded through the **Bank** account. No separate physical cash account is maintained.

---

# 7. Excel Implementation

The workbook is intended to demonstrate practical Excel skills alongside accounting knowledge.

Key features:

- Structured Excel tables
- XLOOKUP-based account-code mapping
- Linked worksheets
- Data validation
- General journal
- Account-level general ledger
- Running inventory balance
- Trial balance formulas
- Adjustment schedules
- Linked financial statements
- Closing entries
- Reconciliation controls

---

# 8. Skills Demonstrated

## Accounting

- Double-entry bookkeeping
- Revenue and sales returns
- Cost of sales
- Trade receivables and payables
- Accruals
- Prepayments
- PPE and depreciation
- Inventory NRV/write-down
- Bank financing
- Interest expense
- Trial balance
- Financial statements
- Closing process

## IFRS / ACCA Knowledge

- IAS 2 — Inventories
- IAS 16 — Property, Plant and Equipment
- IFRS 15 — Revenue / customer advances
- IFRS 9 — Financing concepts (simplified treatment; EIR/transaction-cost accounting not fully applied)
- IFRS 18 — Presentation and Disclosure in Financial Statements

## Excel

- XLOOKUP
- FILTER
- IFERROR
- CHOOSECOLS
- XMATCH
- Other arithmetic and logical operators such as SUM, ROUND and OR
- Structured tables
- Linked worksheets
- Formula-driven accounting schedules
- Running balances
- Trial balance controls
- Financial statement linking
- Data Validation
- Reconciliation

# 9. Copyright

🔒 © 2026 Muhammad Sami. All Rights Reserved. 

This project is provided for viewing and educational purposes only. Copying, reproducing, redistributing, modifying, or presenting any part of this work as your own is prohibited without prior permission.
