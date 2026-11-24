# Financial Risk & Loan Portfolio Analysis 
# Project Background
This project focuses on the Banking and Financial Services industry, specifically loan portfolio management, credit risk assessment, borrower analysis, and loan default analysis.

The business scenario represents a financial institution that provides Personal, Business, Mortgage, Auto, Education, and Home Improvement loans. As a Data Analyst working in the Financial Risk Management team, my role is to analyse loan portfolio data, evaluate borrower creditworthiness, identify potential default risks, and assess the financial impact of loan defaults.

The analysis covers 10K loans, with $668.4M in total loan exposure, $319.2M in outstanding exposure, 710 default loans, approximately 1K delinquent loans, and a 7% default rate.

Insights and recommendations are provided on the following key areas:

Category 1: Financial Risk & Loan Portfolio Analysis

Category 2: Credit Risk & Borrower Analysis

Category 3: Loan Default & Financial Impact Analysis

The SQL queries used to create the loan dataset table, inspect and explore the data, calculate key financial metrics, and answer various business questions related to loan exposure, loan status, risk grades, default analysis, borrower creditworthiness, and collateral shortfalls can be found here [Financial_Risk_Analysis.sql](https://github.com/user-attachments/files/35318860/Financial_Risk_Analysis.sql)

An interactive Power BI dashboard developed to analyse loan portfolio performance, financial risk, borrower creditworthiness, and loan default trends can be found here [Financial Risk Analysis Dashboard](Financial_Risk_Analysis_Dashboard.pbix).

# Data Structure & Initial Checks

The financial risk database consists of one main table named finacial_risk, containing loan-level and borrower-level information. The Power BI dashboard displays approximately 10K loan records. The exact record count can be verified using SQL.

A description of the database table is provided below:

Table 1: finacial_risk – Contains comprehensive loan and borrower-level data, including loan identification, loan dates, geographical details, loan categories, financial information, borrower credit profiles, repayment status, risk grades, missed payments, collateral values, and estimated interest.

# Executive Summary
Overview of Findings

The analysis of approximately 10K loan records revealed a total loan exposure of $668.4M, with $319.2M in outstanding balances and an overall default rate of 7% (710 default loans). Borrower analysis highlighted an average credit score of 698.99, an average debt-to-income ratio of 24.3, and approximately 11K missed payments, providing important indicators for monitoring borrower credit risk. The analysis also identified $47.9M in default loan amounts and $36.7M in default outstanding balances, highlighting the need for effective loan recovery strategies and stronger credit risk monitoring.

Dashboard Visualization

The following three Power BI dashboard pages provide a visual overview of the analysis:

1. Financial Risk Analysis

<img width="1427" height="793" alt="Screenshot 2026-11-24 180623" src="https://github.com/user-attachments/assets/9ddccd95-870a-4ed3-afe4-870caa79a073" />


2. Credit Risk & Borrower Analysis

<img width="1431" height="792" alt="Screenshot 2026-11-24 180808" src="https://github.com/user-attachments/assets/340dd0f6-cc1c-4fc7-be57-545032ed032a" />


3. Loan Default & Financial Impact
<img width="1425" height="792" alt="Screenshot 2026-11-24 180855" src="https://github.com/user-attachments/assets/5b0c56e9-39f0-4370-bb69-245af308b2c0" />

# Insights Deep Dive
Category 1: Financial Risk & Loan Portfolio Analysis
• Total Loan Exposure: The financial institution manages approximately 10K loans, representing a total loan exposure of $668.4M, providing an overview of the overall lending portfolio.

• Outstanding Loan Balance: The outstanding loan exposure is $319.2M, highlighting the amount of loan value that remains unpaid and requires continuous monitoring.

• Loan Status Distribution: Analysed loan distribution across Current, Delinquent, Default, and Paid Off categories to understand overall portfolio performance. Approximately 1K loans are delinquent.

• Loan Type & Risk Grade Distribution: Compared loan volumes and total loan amounts across different loan types and risk grades to identify portfolio concentration and potential risk exposure.

Category 2: Credit Risk & Borrower Analysis

• Borrower Credit Profile: The average borrower credit score is 698.99, providing an overview of the creditworthiness of the loan portfolio.

• Debt-to-Income Analysis: The average debt-to-income ratio is 24.3%, helping evaluate borrowers' debt obligations relative to their annual income.

• Missed Payment Analysis: Approximately 11K missed payments were recorded, highlighting the importance of monitoring repayment behaviour and identifying borrowers who may require additional attention.

• High-Risk Borrower Identification: Identified borrowers with credit scores below 670 and debt-to-income ratios above 35% to highlight accounts that may require closer credit risk monitoring.

Category 3: Loan Default & Financial Impact Analysis

• Default Loan Analysis: Identified 710 default loans, representing an overall default rate of approximately 7% of the loan portfolio.

• Default Loan Exposure: The total loan amount associated with defaulted accounts is $47.9M, highlighting the financial exposure arising from loan defaults.

• Outstanding Default Balance: Defaulted loans account for $36.7M in outstanding balances, indicating the amount still unpaid across defaulted accounts.

• Geographic & Risk Grade Analysis: Compared default outstanding balances across different states and risk grades to identify areas of concentrated financial exposure. Also examined loans where collateral value is lower than the outstanding balance to identify potential collateral shortfalls.

Recommendations:

• Based on the insights and findings above, the Financial Risk Management team should consider the following:

• Portfolio Monitoring: With $319.2M in outstanding loan exposure, establish regular monitoring of outstanding balances, repayment performance, and loan status distribution.

• Early Credit Risk Identification: Monitor borrowers with credit scores below 670 and DTI ratios above 35% to identify potentially vulnerable accounts and support timely risk reviews.

• Repayment Monitoring: Given the approximately 11K missed payment events, strengthen repayment tracking and introduce early follow-up procedures for borrowers with repeated missed payments.

• Default Recovery Management: Prioritise recovery efforts for high-value defaulted loans, considering the $36.7M outstanding default balance.

• Collateral Risk Assessment: Regularly review collateral values against outstanding loan balances and prioritise accounts with significant collateral shortfalls to understand potential recovery risks.
