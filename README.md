##Sales Performance & Customer Segmentation Analysis

---

## 📌 Overview

This project explores a retail customer shopping dataset to uncover patterns in how people buy, what they buy, and who they are. The goal is to turn raw transaction data into clear, actionable business insights.


---

## 🎯 Objectives

- Understand who the customers are (age, gender)
- Find which categories and items drive the most revenue
- Analyse seasonal and payment trends
- Segment customers by spending behavior
- Identify high-value customer profiles
- Calculate key business KPIs

---

🛠️ Tools & Technologies
Python
Pandas
Matplotlib
Seaborn

---

## 📊 Project Structure

```
Cart-to-Insight/
│
├── EDA_project.ipynb
├── Sales_Performance_Customer_Segmentation_Analysis.csv
├── README.md
│
├── 📁 Data Exploration/
│   ├── Basic Exploration
│   ├── Null Check
│   ├── Summary Statistics
│   └── Unique Value Analysis
│
├── 📁 Data Cleaning/
│   └── Snake case renaming + Duplicates removed
│
├── 📁 Demographics/
│   ├── Age Distribution
│   └── Gender Distribution
│
├── 📁 Purchase Analysis/
│   ├── Purchase Amount Distribution
│   ├── Spend by Category
│   └── Top 10 Purchased Items
│
├── 📁 Revenue Breakdowns/
│   ├── Revenue by Category
│   ├── Revenue by Gender
│   └── Revenue by Season
│
├── 📁 Payment Analysis/
│   ├── Payment Method Frequency
│   ├── Total Revenue by Payment Method
│   └── Average Order Value by Payment Method
│
├── 📁 Cohort Thinking/
│   ├── Age Group × Gender Spend
│   └── Age Group × Category Heatmap
│
└── 📁 KPIs/
    ├── Core KPIs (AOV, Total Revenue)
    ├── Top Category Contribution
    └── Payment Method Performance
```

**Notebook Sections:**

| # | Section | What it covers |
|---|---------|----------------|
| 1 | Imports & Load Data | Libraries + loading the CSV |
| 2 | Basic Exploration | Shape, info, column names |
| 3 | Null Check | Missing values check |
| 4 | Summary Statistics | describe() on all columns |
| 5 | Data Cleaning | Snake case renaming, duplicates removed |
| 6 | Unique Value Analysis | nunique() per column |
| 7 | Age Distribution | Customer age countplot |
| 8 | Gender Distribution | Gender countplot |
| 9 | Purchase Amount Distribution | Histogram of spend |
| 10 | Spend by Category | Boxplot per category |
| 11 | Top 10 Purchased Items | Most bought items bar chart |
| 12 | Revenue by Category | Total revenue per category |
| 13 | Item Count by Category | Transaction volume per category |
| 14 | Revenue by Gender | Gender revenue comparison |
| 15 | Revenue by Season | Seasonal revenue breakdown |
| 16 | Payment Method Frequency | How often each method is used |
| 17 | Avg Spend by Payment Method | AOV per payment method |
| 18 | Correlation Heatmap | Numeric variable relationships |
| 19 | KPIs | Total revenue, AOV, top performers |
| 20 | Top Category Contribution | % revenue share per category |
| 21 | Payment Method Performance | 3-way payment analysis |
| 22 | Cohort Thinking | Age group × gender spend analysis |
| 23 | Cohort Heatmap | Age group × category revenue heatmap |

---

## 🔍 Analysis Breakdown

**1. Data Cleaning**
- Renamed columns to snake_case
- Removed duplicates
- Checked and handled missing values

**2. Demographic Analysis**
- Age distribution across customers
- Gender split and its revenue impact

**3. Revenue Breakdowns**
- Revenue by category, gender, and season
- Category contribution as a percentage of total revenue

**4. Customer Segmentation**
- Split customers into Low, Mid, and High spenders
- Compared spend tiers across categories and age groups

**5. Cohort Thinking**
- Grouped customers by Age Group × Gender
- Identified which cohorts spend the most and in which categories

**6. Behavioral Patterns**
- Category preference by spend tier
- Payment method habits
- Seasonal shopping by gender

**7. KPIs**
- Average Order Value (AOV)
- Repeat Purchase Rate
- Top Category Contribution
- Payment Method Performance

---

## 💡 Key Findings

- **Clothing dominates** — 44.7% of all revenue comes from one category
- **Male customers** make up 67.7% of revenue — but only because there are more of them, not because they spend more per visit
- **All seasons are balanced** — the gap between best (Fall $60,018) and worst (Summer $55,777) season is only $4,241
- **AOV is consistent at ~$60** across all categories, genders, age groups and payment methods
- **25–34 females** are the highest spending cohort at $62.13 per order
- **Outerwear is underperforming** — only 7.9% revenue share, bought by just 324 out of 3,900 customers
- **Payment methods are equal** — all 6 methods perform almost identically

---


## 📈 Sample Visualizations

- Revenue contribution by category (pie + bar)
- Cohort heatmap — Age Group × Category
- Spend tier distribution
- Payment method comparison (3 charts)
- Correlation heatmap
- AOV by category

---

## 🙋 About

This project was built as part of a data analysis portfolio to demonstrate practical EDA skills — data cleaning, visualization, segmentation, cohort analysis, and KPI tracking — using a real-world retail dataset.

---
> *"Data is just numbers until you ask the right questions."*
