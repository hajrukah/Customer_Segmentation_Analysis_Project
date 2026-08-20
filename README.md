# MTN Customer Segmentation & Churn Analysis

> **Turning customer guesswork into data-driven decisions for Nigerian SMEs**

## 📌 Project Overview

Many Nigerian SMEs make important customer decisions based on assumptions.

They may know how much they sell, but often cannot confidently answer:

* Who are my most valuable customers?
* Which customers are likely to leave?
* Which customer segments generate the most revenue?
* What do different customers actually buy or use?
* Where should I focus my retention and marketing efforts?
* Which customers deserve a personalized offer?

This project demonstrates how **customer data can replace that guesswork with evidence**.

Using an MTN customer dataset as a practical case study, I built an end-to-end customer segmentation and churn analysis workflow that transforms raw customer data into **KPIs, segments, visual insights and business recommendations**.

The approach can be adapted by Nigerian SMEs to their own customer, sales or transaction data.

---

## 🎯 The Business Problem

### Nigerian SMEs are often guessing their customers.

For many small and growing businesses, customer information exists in spreadsheets, sales records, transaction systems or disconnected files—but that data is not always converted into useful business intelligence.

As a result, decisions about marketing, retention and customer value can become reactive:

> **“Who do we think our customers are?”**

instead of:

> **“What does our customer data actually tell us?”**

This project addresses that problem by creating a repeatable process for turning customer-level data into meaningful customer segments and actionable business insights.

---

## 💡 The Proposed Solution

The project provides a simple analytics framework:

**Raw Customer Data**
↓
**Data Cleaning & Preparation**
↓
**KPI & DAX Measures**
↓
**Customer Segmentation**
↓
**Churn & Behavior Analysis**
↓
**Interactive Dashboard**
↓
**Business Insights & Recommendations**

The result is a decision-support dashboard that helps a business understand **who its customers are, what they do, which customers are at risk, and where attention should be focused.**

---

## 🎯 Project Objectives

1. Clean and prepare customer-level data for analysis.
2. Create reliable customer and churn KPIs.
3. Segment customers using demographic and behavioral characteristics.
4. Identify patterns associated with customer churn.
5. Analyze customer purchasing and data-usage behavior.
6. Identify higher-value subscription segments.
7. Build interactive dashboards in Excel and Power BI.
8. Translate analytical findings into practical business recommendations.
9. Demonstrate how the approach can help SMEs make customer decisions using evidence rather than assumptions.

---

## 📊 Dataset

The case study contains **496 customer records** with customer-level information including:

* Customer ID
* Age
* Gender
* Customer tenure
* MTN device
* Subscription plan
* Data usage
* Number of purchases
* Satisfaction rate
* Churn status
* Revenue-related information

The data was cleaned and prepared before analysis and visualization.

---

## 🛠️ Tools Used

| Tool                | Purpose                                          |
| ------------------- | ------------------------------------------------ |
| **Microsoft Excel** | Data cleaning, analysis and initial dashboard    |
| **Power BI**        | Interactive dashboard and visualization          |
| **DAX**             | KPI and analytical measures                      |
| **GitHub**          | Project documentation and portfolio presentation |

---

# 📈 Key Results

The analysis produced the following headline KPIs:

| KPI                       |  Result |
| ------------------------- | ------: |
| Total Customers           | **496** |
| Active Customers          | **350** |
| Churned Customers         | **146** |
| Churn Rate                | **29%** |
| Total Revenue             | **96M** |
| Total Purchases           |  **5K** |
| Average Purchases         |  **11** |
| Average Data Usage        |  **99** |
| Average Satisfaction Rate |   **3** |

---

# 🔎 Key Insights

## 1. Churn is a measurable retention problem

**146 out of 496 customers have churned**, producing an overall churn rate of **29%**.

This gives the business a measurable retention baseline instead of relying on assumptions about whether customers are leaving.

---

## 2. Churn differs across customer segments

Age-based analysis shows meaningful differences between customer groups.

The **76–85 age group has approximately 48% churn**, while the **26–35 group is also elevated at approximately 34%**.

This demonstrates why businesses should avoid treating their entire customer base as one homogeneous group.

---

## 3. Gender provides an additional segmentation signal

Female customers show approximately **31% churn**, compared with **28% for male customers**.

The difference is relatively small, so gender should not be treated as the main explanation for churn. However, it can be useful when combined with other customer characteristics.

---

## 4. Active customers can still churn

One of the important findings is that churned customers are not necessarily inactive customers.

Average data usage is approximately:

* **100 GB — churned customers**
* **98 GB — retained customers**

Average purchases are approximately:

* **11 — churned customers**
* **10 — retained customers**

This means that **high engagement alone does not guarantee retention**.

Businesses therefore need to look beyond usage and purchasing activity and investigate factors such as pricing, service quality, satisfaction and competitive alternatives.

---

## 5. Customer value matters

Revenue analysis shows that higher-value subscription plans contribute strongly to overall revenue.

For an SME, this means that customer retention should not focus only on **how many customers are leaving**.

It should also ask:

> **“Which customers are leaving, and how valuable are they to the business?”**

---

# 💼 Business Recommendations

## 1. Stop treating all customers the same

Use segmentation to identify differences in customer behavior, value and churn risk before launching marketing or retention campaigns.

## 2. Prioritize high-value customers

Identify customers who generate significant revenue and combine customer value with churn risk to determine where retention efforts should be concentrated.

## 3. Investigate the reasons behind churn

Because churned customers remain relatively active, businesses should investigate:

* Pricing
* Service quality
* Customer satisfaction
* Network/service experience
* Competitor alternatives
* Subscription value

## 4. Personalize customer engagement

Use customer segments to provide more relevant:

* Offers
* Promotions
* Loyalty incentives
* Service communication
* Retention campaigns

## 5. Make the dashboard part of the decision process

The dashboard should not simply be a reporting document.

It can be used regularly to monitor customer KPIs, identify changes in churn, and determine which segments require attention.

---

# 📊 Dashboard

The Power BI dashboard provides an interactive view of:

* Customer KPIs
* Churn rate
* Churn by gender
* Churn by age group
* Churn by MTN device
* Revenue by subscription plan
* Purchasing behavior
* Data usage
* Churn status
* Customer filters and slicers

### Dashboard Preview

Add the final Power BI dashboard screenshot here:

```text
![MTN Customer Segmentation Dashboard](screenshots/dashboard.png)
```

---

# 📄 Insight Summary

A polished one-page business insight summary is included with the project.

# 📂 Project Structure

```text
mtn-customer-segmentation/
│
├── README.md
│
├── data/
│   └── mtn_clean.csv
│
├── excel/
│   └── mtn_customer_segmentation_project.xlsx
│
├── powerbi/
│   └── mtn_customer_segmentation_projrct.pbix
│
├── reports/
│   └── MTN_Insight_Summary.pdf
│
└── screenshots/
    └── dashboard.png
```

The demonstration will show:

1. The business problem
2. The cleaned dataset
3. The Excel analysis
4. The Power BI dashboard
5. Key customer insights
6. Churn findings
7. Business recommendations

---

# 🚀 Business Impact

The main value of this project is not the dashboard itself.

The value is the **decision-making approach** behind it.

Instead of asking:

> **“Who are our customers?”**

based on assumptions, an SME can use its data to answer:

> **“Which customers do we have, what are they worth, how do they behave, and which ones need our attention?”**

This creates a foundation for more targeted marketing, better retention decisions and more effective use of limited business resources.

---

# 🧠 Conclusion

This project demonstrates how customer analytics can help Nigerian SMEs move from **guessing to knowing**.

By combining customer segmentation, churn analysis, purchasing behavior, usage patterns, customer value and interactive visualization, businesses can turn existing customer data into practical decisions.

The MTN case study provides a working example of this approach, while the underlying framework can be adapted to an SME's own customer or transaction data.

**The goal is simple: don't guess your customers. Use your data to understand them.**

---

## 👤 Author

**Rukaiyah Sanni**

*Data Analytics Project — Customer Segmentation & Churn Analysis*
::: 
