# PySpark Phase 4A – Bucketing & Segmentation

---

## Overview

This project explores various customer segmentation techniques using **PySpark**. Continuous customer spending values are transformed into meaningful business categories such as **Gold**, **Silver**, and **Bronze** using multiple bucketing approaches. The project demonstrates both rule-based and data-driven segmentation methods for customer analytics.

---

## Objectives

- Calculate customer spending.
- Perform customer segmentation using multiple techniques.
- Compare different bucketing approaches.
- Understand business-driven and statistical segmentation methods.

---

## Technologies Used

- Python
- PySpark
- Apache Spark MLlib
- Google Colab

---

## Dataset

- **sales.csv**

---

## Project Workflow

### Step 1 – Data Ingestion

- Read the sales dataset into a PySpark DataFrame.

### Step 2 – Data Cleaning

- Remove missing values.
- Validate dataset schema.

### Step 3 – Customer Spending Calculation

- Calculate the total spending for each customer.

### Step 4 – Customer Segmentation

- Apply different bucketing techniques to categorize customers.

---

## Bucketing Methods

### 1. Conditional Logic

Business rule-based segmentation using:

- 🥇 Gold
- 🥈 Silver
- 🥉 Bronze

---

### 2. SQL CASE Statement

Implement customer segmentation using SQL `CASE` expressions.

---

### 3. Bucketizer (Spark MLlib)

Perform segmentation using the **Spark MLlib Bucketizer**.

---

### 4. Quantile-based Segmentation

Create customer groups based on spending distribution using quantiles.

---

### 5. Window-based Ranking

Rank customers according to their spending using the `percent_rank()` window function.

---

## Tasks Completed

- Customer spending calculation
- Gold / Silver / Bronze segmentation
- Segment-wise customer count
- Quantile-based segmentation
- Bucketizer implementation
- Window-based customer ranking
- SQL and equivalent PySpark implementation for each segmentation method

---

## Key Concepts Covered

- Bucketing
- Customer Segmentation
- Conditional Logic
- SQL CASE Statements
- Spark MLlib Bucketizer
- Quantiles
- Window Functions
- Business Analytics

---

## Learning Outcomes

After completing this project, I gained practical experience in:

- Performing customer segmentation using multiple techniques.
- Applying business rules for customer classification.
- Using Spark MLlib Bucketizer for data bucketing.
- Ranking customers using window functions.
- Comparing rule-based and statistical segmentation strategies.
- Converting SQL queries into equivalent PySpark DataFrame operations.

---

## Project Structure

```text
Phase-4A-Bucketing/
│
├── Phase4A_Bucketing.ipynb
├── sales.csv
├── README.md
└── output/
```

---

## Skills Demonstrated

- PySpark
- Apache Spark
- Apache Spark MLlib
- SQL
- Data Engineering
- Customer Segmentation
- Bucketing
- Business Analytics
- Window Functions
- Data Transformation

---

## Author

**K. Tejithavalli**

**B.Tech – Computer Science and Engineering (Artificial Intelligence & Data Science)**

**Skills:** PySpark • Apache Spark • Apache Spark MLlib • SQL • Python • Data Engineering • Customer Analytics

---
