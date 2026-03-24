# 📊 Customer Churn Analysis — IBM Telecom Industry

## 🔍 Project Overview
A Business Analyst portfolio project analysing customer 
churn patterns using the IBM Telecom dataset (7,043 customers)
built entirely in Microsoft Excel with full BA documentation.

## ❓ Business Problem
The company's churn rate stands at 26.5% — 1 in 4 customers 
is leaving. This project identifies the root causes of churn 
and recommends data-driven retention strategies.

## 🎯 Project Objectives
- Identify which customer segments have the highest churn
- Find patterns in contract type, payment method and tenure
- Calculate churn rate across different price bands
- Deliver a one-page dashboard for business stakeholders

## 🔑 Key Findings
- Month-to-month contracts churn at 42.7% — 15x higher than two-year contracts
- Fiber optic customers churn at 41.9% despite being premium users
- Electronic check payment method has the highest churn at 45.3%
- 56.2% of customers churn within the first 3 months — onboarding failure
- Higher monthly charges ($60+) correlate with 33%+ churn rate

## 🛠️ Tools Used
| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, Pivot Tables, Charts, Dashboard |

## 📁 Files in This Repo
| File | Description |
|---|---|
| `Churn_Project.xlsx` | Excel workbook with cleaned data, 5 pivot tables, 5 charts and summary dashboard |
| `SRS_Excel_Final_Version.pdf` | Software Requirements Specification — full BA documentation |


## 🧹 Data Cleaning Steps
- Converted CSV to Excel Table named ChurnData
- Fixed data type mismatch in SeniorCitizen column
- Created Tenure_Bucket column (0-3mo, 4-6mo, 7-12mo, 1-2yr, 2yr+)
- Created Charge_Band column (Low, Mid, High, Premium)
- Created Churn_Flag column (1 = Churned, 0 = Retained)
- Created SeniorCitizen_Clean column (Yes/No)

## 📈 Pivot Tables Built
| Pivot | Analysis | Key Finding |
|---|---|---|
| PT1 | Churn by Contract Type | Month-to-month = 42.7% churn |
| PT2 | Churn by Tenure Bucket | First 3 months = 56.2% churn |
| PT3 | Churn by Internet Service | Fiber optic = 41.9% churn |
| PT4 | Churn by Payment Method | Electronic check = 45.3% churn |
| PT5 | Churn by Charge Band | High charges = 33.7% churn |

## 💡 Recommendations
1. Convert month-to-month customers to annual contracts
2. Investigate Fiber optic service quality issues
3. Incentivise electronic check users to switch to auto-pay
4. Improve onboarding experience for first 90 days
5. Review pricing strategy for high charge band customers

## 👤 Author
Laxman Sharma | Aspiring Business Analyst
