# 🛍️ Exploratory Data Analysis (EDA) of E-commerce Diwali Sales

## Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of an e-commerce platform's Diwali sales data. The primary goal was to process, clean, and analyze customer purchasing trends across various dimensions (gender, age, state, marital status, and product category) to deliver **actionable business intelligence**.

## 🛠️ Technology Stack
* **Language:** Python
* **Libraries:** **Pandas** (for data manipulation and cleaning), **NumPy** (for numerical operations), **Matplotlib** and **Seaborn** (for data visualization).
* **Environment:** Jupyter Notebook

## Data Cleaning & Preprocessing Highlights
* **Data Size:** Analyzed 11,000+ customer records across 15 initial columns.
* **Integrity:** Handled null/missing values using `.dropna()` and removed irrelevant columns.
* **Data Typing:** Converted the 'Amount' column from a `float` to an `integer` using `.astype('int')` to ensure accurate financial aggregation.

## 📊 Key Business Insights

The analysis identified the following high-impact segments for targeted marketing:

| Segment | Insight | Impact |
| :--- | :--- | :--- |
| **Highest Spender** | **Married Women** in the **26-35** age group have the largest purchasing power. | Target marketing campaigns specifically toward this demographic. |
| **Highest Revenue Product** | **Food** was the highest-grossing category by total **Amount**, despite **Clothing** having the highest *number of orders*. | Focus inventory and premium marketing on high-revenue Food items. |
| **Top States** | **Uttar Pradesh, Maharashtra, and Karnataka** account for the majority of orders and sales amount. | Prioritize logistics and promotional offers in these regions. |

## 📊 Key Visualizations

### 1. Highest Spending Customer Segment

This chart identifies the Married Women (26-35) as the demographic with the highest purchasing power.

Bar chart showing total sales amount by age group and gender (https://raw.githubusercontent.com/komaljhalanee/python-diwali-sale-eda/refs/heads/main/asset/highest-spending-demographic.png)

<br>

### 2. Product Revenue vs. Popularity

This visualization highlights that Food generates the highest total revenue, separating profit from order volume.

Bar chart showing total revenue by product category (https://raw.githubusercontent.com/komaljhalanee/python-diwali-sale-eda/refs/heads/main/asset/most-ordered-product.png)

<br>

### 3. Top Regional Orders

A breakdown of transaction volume by state, focusing on the top 10 contributors.

Bar chart showing total number of orders by state (https://raw.githubusercontent.com/komaljhalanee/python-diwali-sale-eda/refs/heads/main/asset/state-wise-total-orders.png)
