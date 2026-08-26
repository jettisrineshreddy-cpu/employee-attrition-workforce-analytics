# Global E-Commerce Customer & Revenue Analytics

## ShadowFox Data Analyst Internship — Intermediate Level

This project is the Intermediate-level work completed as part of my ShadowFox Data Analyst Internship.

The goal of the project was to go beyond basic sales reporting and understand how customers, segments, products, discounts, regions, and profitability were performing across the business.

I used **Microsoft Excel** for data preparation and exploratory analysis, and **Microsoft Power BI** to build the final interactive report.

---

## Project Overview

The dataset contains **2,000 e-commerce transactions** covering:

- Customer information
- Customer segments
- Countries and regions
- Products and categories
- Quantities and prices
- Discounts
- Sales and profit
- Payment methods

The analysis was designed around a few practical business questions:

- How is revenue and profit performing?
- Which customer segments contribute the most?
- How many customers make repeat purchases?
- Which products generate the most revenue?
- How do discounts relate to profitability?
- Which regions perform strongly in both sales and margin?

---

## Data Preparation

I first prepared the dataset in Excel before moving the cleaned data into Power BI.

The preparation included:

- Checking data types
- Checking missing values
- Checking fully duplicated rows
- Standardizing text fields
- Creating useful analytical fields

Additional fields created for analysis included:

- **Order Year**
- **Order Month**
- **Order Month Name**
- **Profit Margin %**
- **Discount Band**

The final dataset contained **2,000 rows with no missing values and no fully duplicated rows**.

---

## Key Analysis

The project focused on four main areas:

### Customer Behaviour

I looked at repeat and one-time purchasing behaviour to understand the strength of customer engagement.

- **1,534 unique customers**
- **392 repeat customers**
- **1,142 one-time customers**
- **25.55% repeat customer rate**

The analysis also showed that the top 10 customers contributed only about **6.35% of total revenue**, suggesting that revenue was not heavily dependent on a small group of customers.

### Customer Segment Performance

The three customer segments were compared using sales, profit, and profit margin.

- **Consumer** — approximately $256.29K sales and $87.30K profit
- **Corporate** — approximately $146.05K sales and $44.46K profit
- **Home Office** — approximately $82.22K sales and $27.11K profit

Consumer was the largest segment and also recorded the strongest margin among the three.

### Discount & Profitability

One of the most useful findings came from comparing discount levels with profit margin:

| Discount Band | Profit Margin |
|---|---:|
| No Discount | 38.72% |
| 0–5% | 35.36% |
| 6–10% | 31.93% |
| 11–15% | 27.02% |
| 16–20% | 21.39% |

Higher discount levels were associated with lower profit margins. This was treated as an observed relationship rather than a proven causal effect.

### Regional Performance

Regional performance was compared using both revenue and profitability.

- **Europe:** approximately $137.01K sales
- **North America:** approximately $133.88K sales
- North America recorded the strongest regional margin at approximately **33.80%**
- Europe recorded approximately **33.34%**

This showed why looking at revenue alone is not always enough when evaluating business performance.

---

## Power BI Report

The final Power BI report contains three pages.

### 1. Executive Overview

Provides a high-level view of:

- Total Sales
- Total Profit
- Profit Margin
- Unique Customers
- Repeat Customer Rate
- Monthly revenue and profit trends
- Customer segment performance
- Regional revenue

### 2. Customer & Segment Analysis

Focuses on:

- Customer behaviour
- Repeat vs one-time customers
- Sales and profit by customer segment
- Profit margin by segment
- Top 10 customers by revenue

### 3. Product & Profitability Analysis

Focuses on:

- Top products by revenue
- Sales vs profit margin by product
- Profit margin across discount bands
- Revenue by region
- Regional profitability

The report also uses slicers so the analysis can be explored interactively by year, customer segment, region, and product category.

---

## Key Takeaways

The main things I found from the analysis were:

1. **Customer repeat behaviour is the main opportunity.** Most customers purchased only once, while the repeat customer rate was 25.55%.

2. **Consumer customers are the main revenue segment.** They generated the highest sales and profit among the three segments.

3. **Higher discount levels were associated with weaker margins.** The decline became more noticeable above the 10% discount range.

4. **Revenue was broadly distributed.** The top 10 customers accounted for only about 6.35% of total revenue.

5. **Revenue scale and profitability are not always the same.** Regional performance needs to be considered using both sales and margin.

---

## Recommendations

Based on the findings, the main recommendations were:

- Focus on converting one-time customers into repeat buyers.
- Strengthen post-purchase engagement and follow-up campaigns.
- Review heavy discounting, especially above the 10% range.
- Prioritize products and customer segments that combine strong sales with healthy margins.
- Evaluate regional performance using profitability as well as revenue.

---

## What I Learned

This project helped me move from simple spreadsheet reporting into more detailed business analysis.

I practiced:

- Data cleaning and preparation
- Exploratory analysis
- Customer and segment analysis
- Revenue and profitability analysis
- Creating reusable Power BI measures
- Building interactive Power BI reports
- Using slicers and filters
- Turning analytical results into business recommendations

It was also the stage where I started thinking less about just **“what happened?”** and more about **“what patterns are visible, and what could the business do about them?”**

---

## Files

- `Global_ECommerce_Customer_Revenue_Analytics.pbix` — Final Power BI report
- `Global_ECommerce_Sales_Datasales.xlsx` — Dataset used for the project
- `intermediate_executive_overview.png` — Executive Overview page
- `intermediate_customer_segment.png` — Customer & Segment Analysis page
- `intermediate_product_profitability.png` — Product & Profitability Analysis page

---

## Project Workflow

**Dataset → Excel Preparation → Exploratory Analysis → Deeper Business Analysis → Power BI → Insights → Recommendations**
