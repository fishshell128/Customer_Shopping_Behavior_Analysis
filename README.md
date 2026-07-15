# Customer Shopping Behavior Analysis

An end-to-end data analytics project that explores customer shopping behavior using **Python**, **PostgreSQL**, and **Tableau**.

The goal of this project is to clean, analyze, visualize, and present customer purchasing patterns to generate actionable business insights.

---

# Overview

This project follows a complete data analytics workflow:

- Data cleaning with Python
- SQL analysis using PostgreSQL
- Interactive dashboard development in Tableau
- Business insight presentation using Gamma

The final dashboard enables users to explore customer behavior by subscription status, gender, product category, shipping type, and age group.

---

# Dataset

The dataset contains **3,900 customer records** with shopping information including:

- Customer ID
- Age
- Gender
- Product Category
- Purchase Amount
- Review Rating
- Subscription Status
- Shipping Type
- Previous Purchases
- Discount Applied
- Promo Code Used

Dataset file:

```
clean_customer_data.csv
```

---

# Tools

- Python (Pandas)
- PostgreSQL
- Tableau
- Gamma (Presentation)
- Git & GitHub

---

# Project Workflow

### 1. Data Cleaning (Python)

- Loaded the dataset using Pandas
- Checked data types
- Identified missing values
- Performed basic data exploration
- Exported the cleaned dataset

Notebook:

```
Customer_Shopping_Behavior_Analysis.ipynb
```

---

### 2. SQL Analysis (PostgreSQL)

Performed SQL queries to answer business questions, including:

- Revenue by gender
- Customers using discounts
- Average review rating by product
- Customer segmentation
- Purchase behavior analysis

SQL file:

```
customer_behavior_sql_queries.sql
```

---

### 3. Dashboard Development (Tableau)

Built an interactive dashboard containing:

- KPI Cards
  - Number of Customers
  - Average Purchase Amount
  - Average Review Rating

- Pie Chart
  - Customer Subscription Status

- Bar Charts
  - Revenue by Category
  - Sales by Category

- Horizontal Bar Charts
  - Revenue by Age Group
  - Sales by Age Group

Interactive filters:

- Subscription Status
- Gender
- Category
- Shipping Type

---

# Dashboard

Main dashboard:

```
customer_behavior_dashboard.twb
```

Dashboard preview:

![Dashboard](dashboard.png)

---

# Presentation

A business presentation summarizing the project and key insights was created using **Gamma**.

Presentation:

```
Presentation_slides.pdf
```

---

# Key Results

Some insights from the analysis include:

- Clothing generated the highest revenue among all categories.
- Customers with subscriptions accounted for approximately 29% of total customers.
- Young Adults generated the highest overall revenue.
- Average purchase amount remained around **$60** across customers.
- Clothing products also recorded the highest number of sales.

---

# Repository Structure

```
.
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
├── Customer_Shopping_Behavior_Analysis.ipynb
├── clean_customer_data.csv
├── customer_behavior_dashboard.twb
├── customer_behavior_sql_queries.sql
├── dashboard.png
├── Presentation_slides.pdf
└── README.md
```

---

# How to Run

### Python

Run the Jupyter Notebook:

```
Customer_Shopping_Behavior_Analysis.ipynb
```

---

### PostgreSQL

Import the dataset into PostgreSQL and execute:

```
customer_behavior_sql_queries.sql
```

---

### Tableau

Open:

```
customer_behavior_dashboard.twb
```

Connect it to:

```
clean_customer_data.csv
```

GitHub: https://github.com/fishshell128
