# 🏦 Banking Dashboard – Risk Analytics using Power BI

## 📌 Project Overview

The **Banking Dashboard** project focuses on developing a basic understanding of risk analytics in banking and financial services. The goal of this project is to analyze customer data and help financial institutions minimize the risk of losing money while lending to customers.

Using **Microsoft Power BI**, interactive dashboards were created to assist banks in making data-driven decisions based on customer profiles — such as determining whether a loan should be approved or rejected.

---

## 🎯 Problem Statement

To understand how data analytics can be used in banking to:

- Evaluate customer profiles
- Analyze loan distribution and deposits
- Measure financial KPIs
- Reduce lending risk
- Improve strategic decision-making

---

## 📊 Solution Approach

The solution was implemented using Power BI dashboards, where:

- Customer and banking data were analyzed
- Data cleaning and transformation were performed
- DAX functions were used for calculated measures
- Key KPIs were created for business insights
- Interactive visualizations were designed for decision-making

---

## 🗂️ Dataset Description

The dataset contains multiple interconnected tables related to banking operations:

- Banking Relationship  
- Clients – Banking  
- Gender  
- Investment Advisor  
- Period  

Tables are linked using **Primary Keys** and **Foreign Keys**.

---

## 🧹 Data Cleaning & Transformation

The following transformations were performed:

- ✅ Created **Engagement Timeframe** column  
- ✅ Created **Engagement Days** using `DATEDIFF`  
- ✅ Created **Income Band**:
  - `< 100000 → Low`
  - `< 300000 → Mid`
- ✅ Created **Processing Fees** column based on Fee Structure  
- ✅ Created calculated columns and measures using DAX  

---
## 📈 Key Performance Indicators (KPIs)

The dashboard tracks critical financial and operational KPIs to evaluate banking performance and lending risk:

- 👥 **Total Clients** – Measures overall customer base size.
- 💰 **Total Loan Exposure** – Aggregated value of bank loans, business lending, and credit card balances.
- 🏦 **Bank Loan Portfolio** – Total outstanding personal loan amount.
- 📊 **Business Lending Volume** – Loan exposure to small and medium enterprises.
- 💳 **Credit Card Outstanding Balance** – Total credit card liability.
- 💵 **Total Deposits** – Combined deposits across savings, checking, foreign currency, and fixed accounts.
- 💲 **Total Fees Generated** – Revenue earned through processing and service fees.
- 🏧 **Checking Account Balance**
- 💼 **Savings Account Balance**
- 🌍 **Foreign Currency Holdings**

These KPIs provide a consolidated view of revenue, liabilities, and customer engagement.

---

## 📊 Dashboard Architecture

The Power BI report is structured into the following analytical views:

1. 🏠 **Executive Overview Dashboard** – High-level KPI summary for decision-makers.
2. 📉 **Loan Analysis Dashboard** – Loan distribution by gender, nationality, investor type, and income band.
3. 💰 **Deposit Analysis Dashboard** – Deposit segmentation and account-level insights.
4. 📋 **Financial Summary Dashboard** – Consolidated performance metrics and engagement analysis.

All dashboards are interactive, enabling dynamic filtering, drill-down analysis, and cross-segmentation.

---

## 📌 Business Insights Generated

- Private banks maintain a higher client acquisition rate.
- Certain nationalities contribute significantly to total loan exposure.
- Income segmentation directly influences lending volume and repayment risk.
- Deposit patterns vary across gender and investor classifications.
- Fee generation is strongly correlated with loan distribution.

These insights assist financial institutions in optimizing lending strategies and improving risk management frameworks.

---

## 🚀 Tools & Technologies Used

- 📊 Microsoft Power BI (Data Visualization & Reporting)
- DAX (Advanced KPI Modeling & Calculated Measures)
- Data Cleaning & Data Transformation
- Financial KPI Design
- Interactive Dashboard Engineering

---

## 📷 Screenshots

<img width="1184" height="681" alt="image" src="https://github.com/user-attachments/assets/4d5eb7e0-e526-4d53-80ab-2749c88b3dd5" />

## 📌 Conclusion

This project demonstrates the practical implementation of Business Intelligence in the banking domain. By leveraging structured datasets and advanced DAX calculations, the dashboard enables data-driven lending decisions, improved financial transparency, and enhanced risk monitoring.

The solution highlights how analytics-driven reporting can strengthen operational efficiency and strategic financial planning within banking institutions.

---

## 🔮 Future Scope

- Integration of predictive analytics for loan default forecasting  
- Implementation of machine learning-based risk scoring models  
- Real-time data pipeline integration  
- Advanced drill-through and segmentation capabilities  



