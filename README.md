# Credit Risk Analysis Dashboard

A **Power BI dashboard** that analyses loan data to find which borrowers are most likely to **default** (not repay their loan).

**Tools:**  Power BI, DAX

## Dataset

Dataset has 32,581 rows and 12 columns. After removing duplicates, missing values, and outliers, **28,495 records** remain.

## Key Findings

- Default rate rises from **9.6%** (Grade A) to **98.3%** (Grade G).
- When the loan is above **30% of income**, the default rate jumps to **71%**.
- Borrowers with a past default fail again **37.8%** of the time, versus **18.2%** for a clean record.
- Income matters more than age: low-income borrowers default **36% to 41%**, high-income only **8% to 11%**.

## Dashboard Features

- **8 KPI cards** (4 per page): Avg Loan Int Rate, Total Loan Applications, Loan Default Rate, Avg Loan Amount, Total Defaults, Avg Loan % of Income, Avg Applicant Income, Avg Credit History
- **Charts:** default rate by loan purpose, loan grade, home ownership, past default, loan amount, and loan % of income; share of defaults by income group; age vs income heatmap (matrix)
- **3 slicers:** Loan Purpose, Home Ownership, Age Group
- **DAX measures and calculated columns:** Default Rate, Total Defaults, Number of Loans, Age Group, Income Group, LPI Group, Loan Amount Group, Past Default



## Author

**Kalpak Khandbhor** 
