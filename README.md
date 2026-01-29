# Insurance-Data-Analysis-Dashboard

## Problem Statement

This dashboard helps insurance companies and business stakeholders analyze policy performance, customer demographics, and claim trends.
It enables better understanding of premium distribution, claim frequency, claim amounts, and risk factors, helping organizations improve pricing strategies, reduce losses, and enhance customer retention.

- Using this dashboard, stakeholders can:

- Monitor policy and premium performance

- Analyze claims behavior

- Identify high-risk customer segments

- Support data-driven underwriting decisions

## Steps followed

Step 1 : Loaded insurance dataset into Power BI Desktop.

Step 2 : Opened Power Query Editor and enabled:

- Column distribution

- Column quality

- Column profile

Step 3 : Enabled column profiling based on entire dataset.

Step 4 : Identified and handled null values in premium, claim amount, and customer-related columns.

Step 5 : Cleaned and transformed data:

- Corrected data types

- Standardized categorical values

Step 6 : Created relationships between policy, customer, and claims tables (if applicable).

Step 7 : Selected a suitable theme for better visual clarity.

Step 8 : Added slicers for:

- Policy Type

- Gender

- Region

- Age Group

Step 9 : Added KPI card visuals for:

- Total Policies

- Total Premium Amount

- Total Claims Amount

- Claim Ratio

Step 10 : Created bar and pie charts to analyze:

- Premium by Policy Type

- Claims by Region

- Customer distribution by Age Group

Step 11 : Used tables and matrices for detailed policy and claim breakdown.

Step 12 : Created calculated columns for age grouping and policy categorization.

Step 13 : Created DAX measures for insurance KPIs.

Step 14 : Used shapes, text boxes, and icons to enhance dashboard UI.

Step 15 : Published the report to Power BI Service.

`DAX Measures Used`
`Total Policies = COUNT(Insurance_Data[Policy_ID])`

`Total Premium = SUM(Insurance_Data[Premium_Amount])`

`Total Claims = SUM(Insurance_Data[Claim_Amount])`

`Claim Ratio = 
DIVIDE([Total Claims], [Total Premium])`

## Snapshot of Dashboard (Power BI Service)

<img width="1360" height="732" alt="FullPage" src="https://github.com/user-attachments/assets/d2488abd-bae0-4552-9908-349a113fabc5" />

## Report Snapshot (Power BI Desktop)

<img width="876" height="487" alt="ReportPage" src="https://github.com/user-attachments/assets/40574162-9e56-4462-a4ca-0b43f29f87af" />

## Insights

A single-page interactive dashboard was developed using Power BI Desktop.

Following insights can be drawn from the analysis:

[1] Policy Analysis

- Certain policy types contribute significantly more to total premium.

- Some policies have higher claim frequency, indicating higher risk.

[2] Customer Demographics

- Majority of policyholders fall into specific age groups.

- Gender and regional distribution highlight customer concentration.

[3] Claims Analysis

- Claims are higher in specific regions and policy categories.

- A small segment of customers accounts for a large portion of claim amounts.

[4] Risk Insights

- High claim ratio segments indicate potential underwriting risks.

- Helps in revising pricing and coverage strategies.

[5] Business Impact

- Enables proactive risk management.

- Supports optimization of premium pricing and claim handling.

## Tools & Technologies

- Power BI Desktop – Data modeling & visualization

- Power BI Service – Report publishing & sharing

- DAX – Measures and KPI calculations

- Power Query – Data cleaning & transformation

- Figma – Dashboard UI/UX design and layout planning

- CSV / Structured Insurance Dataset

## Conclusion

This Insurance Data Analysis dashboard provides actionable insights into policy performance, customer behavior, and claim risks.
It empowers insurance businesses to make informed, data-driven decisions to improve profitability and risk management.
