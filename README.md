# Diwali Sales Data Analysis

An end-to-end Exploratory Data Analysis (EDA) project using Python to analyze Diwali festival sales data. This project uncovers critical insights into customer demographics, regional purchasing power, and top-performing product categories to help a retail business optimize its marketing strategies and inventory planning for future festive seasons.

---

## 📌 Project Overview
This project focuses on executing an end-to-end Exploratory Data Analysis (EDA) on retail transaction data captured during the Diwali festival period in India. By leveraging data-driven customer segmentation, the primary goal is to decipher purchasing behaviors, identify key demographic drivers, evaluate product category performance, and deliver actionable insights. These findings can be leveraged to refine marketing campaigns, optimize inventory distribution, and maximize corporate revenue during peak holiday seasons.

### Key Objectives:
*   **Identify Ideal Customer Profiles:** Segment consumers by gender, age group, state, and occupation.
*   **Enhance Product Inventory:** Pinpoint the highest-selling product categories and specific items to avoid stockouts.
*   **Geographical Targeting:** Determine which zones and states generate the highest revenue.
*   **To maximize profitability, enhance customer retention, and optimize resource allocation for future festive cycles by delivering a comprehensive, data-driven consumer persona mapping and sales strategy playbook.**

---

## 🛠️ Tech Stack & Tools
*   **Language:** Python
*   **Environment:** collab Notebook
*   **Libraries:** 
    *   `Pandas` (Data manipulation & structural cleaning)
    *   `NumPy` (Numerical array calculations)
    *   `Matplotlib` & `Seaborn` (Data visualization)

---

## 📊 Dataset Description
The dataset contains **11,000+ rows** of customer transactions during the Diwali period. Key features include:

* **User_ID** - Unique identification number assigned to each customer.
* **Cust_name** - The name of the customer.
* **Product_ID** - Unique identification code for each product purchased.
* **Gender** - The gender of the customer (e.g., Male, Female).
* **Age** - The age of the customer in years.
* **Group** - The specific age group or demographic category the customer belongs to (e.g., 26-35).
* **Marital_Status** - The marital status of the customer, often represented as a binary code or text (e.g., 0 for Single, 1 for Married).
* **State** - The geographical state where the customer resides.
* **Zone** - The broader geographical region or zone where the customer is located (e.g., North, South, West, East).
* **Occupation** - The employment sector or profession of the customer (e.g., IT, Healthcare, Banking).
* **Product_Category** - The category or classification of the purchased product.
* **Orders** - The total number of items or orders placed by the customer in that transaction.
* **Amount** - The total monetary value or expenditure of the transaction.
* **Status** - The current state of the order or account (e.g., Complete, Pending, Cancelled).
---

## 🚀 Execution Workflow

### 1. Data Cleaning & Preprocessing
*   Dropped empty/unrelated columns (`Status` and `unnamed1`).
*   Handled missing values in the `Amount` column.
*   Corrected column data types (converted `Amount` from float to integer for clean financial plotting).

### 2. Exploratory Data Analysis (EDA)
Visualized key business questions using bar charts, count plots, and pie charts:
*   **Gender Analysis:** Comparing purchasing power and order counts between genders.
*   **Age Profile:** Identifying which age group contributes the most to gross sales.
*   **Geographic Performance:** Ranking the top 10 states by total orders and total revenue.
*   **Occupation & Category Insights:** Correlating buyers' industries with their choice of product categories.

---

## 📈 Key Findings & Business Insights
*   **The Power Buyer Profile:** Married women aged **26–35 years** are the highest spending cohort.
*   **Top Geographies:** Residents of **Uttar Pradesh, Maharashtra, and Karnataka** drove the maximum number of orders and sales amount.
*   **Professional Sector:** Individuals working in **IT, Healthcare, and Aviation** sectors constitute the top buyers.
*   **Product Preferences:** **Food, Clothing & Apparel, and Electronics** emerged as the top 3 highest revenue-generating categories.

---

## 📊 Solution to Business Objective
*   To maximize sales growth and efficiency during the Diwali festive season, the client should deploy a hyper-localized marketing and operational strategy that heavily targets their highest-converting demographic-  unmarried females aged 26 to 35 working in high-income sectors like IT, Healthcare, and Aviation. By focusing digital advertising budgets on self-gifting and lifestyle themes for this specific high-disposable-income pool across powerhouse states like Uttar Pradesh, Maharashtra, and Karnataka, the business can significantly optimize its return on ad spend.

*   To maximize the average transaction value, the digital storefront should implement smart, cross-category product bundling that pairs high-volume items like traditional clothing and food boxes with high-revenue electronics at the checkout stage. Regionally pooling fast-moving inventory into fulfillment centers within these top-performing states will guarantee rapid delivery times and eliminate cart abandonment caused by festive shipping delays. Finally, to eliminate negative growth hazards and prevent capital from bleeding, the client must aggressively liquidate slow-moving categories like sports products and office supplies to free up premium warehouse space, while simultaneously capturing the underperforming male segment by introducing low-friction, pre-packaged family and corporate gifting bundles.

## Conclusion: 
*   1. Females dominate purchasing power. They account for roughly $70\%$ of total revenue and place significantly more orders than males, proving to be the business's primary consumer base.

*   2. Young adults drive the market. The **26–35 age cohort** is the undisputed powerhouse segment, with females in this specific bracket contributing the highest individual order volume.

*   3. Sales are highly centralized. The Central and Southern zones dominate regional revenue, with **Uttar Pradesh, Maharashtra, and Karnataka** standing out as the top three revenue-generating states.

*   4. Unmarried consumers spend more. Single/unmarried individuals (flag 0) display higher aggregate spending profiles and order frequencies during the festive season compared to married shoppers.

*   5. Corporate tech sectors lead expenditure. Customers working in **IT, Healthcare, and Aviation** possess the highest purchasing density, likely driven by high festive disposable income and corporate bonuses.

*   6. A clear Value vs. Volume split exists.Food and Clothing & Apparel generate the highest transaction volume (most units sold), while **Electronics** drives the highest cash value per order.

*   7. Transactions are small but high-potential. Most consumers purchase **1 to 2 items per order**, and while individual transaction value is right-skewed (most transactions are moderate), a highly valuable long-tail of high-ticket spenders exists.
