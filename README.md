# **LagosExpress_Grocery FMCG Analytics (PostgreSQL)**

## What this project is about
This repository contains a PostgreSQL-based analytics project for LagosExpress-Grocery, an FMCG company operating across multiple regions in Nigeria. The goal of this project is to analyze key business metrics such as:
* Sales performance across products, regions, and time periods
* Customer distribution and segmentation
* Product profitability for beverages, snacks, and toiletries

## The database consists of four core tables:
* customers – Customer demographic and profile data
* products – Information on all FMCG items sold
* sales – Transaction-level sales records
* regions – Geographic and operational region definitions

This repository includes SQL scripts, queries, and data models designed to extract insights, support reporting, and enable deeper business intelligence for LagosExpress-Grocery.


As a Data Analyst that was employed at LagosExpress-Grocery, you are tasked by the
stake-holders to find:

#### **Q1. Total amount each customer spent (JOIN): Insight:**

- Use JOINs and SUM() to calculate total spent per customer.

#### **Q2. All customers, even those without purchases (LEFT JOIN):**

- Insight: LEFT JOIN helps identify inactive customers

#### **Q3. All products and their sales, even if not sold (RIGHT JOIN): Insight:**

- RIGHT JOIN shows unsold items useful for stock planning.

#### **Q4. Total sales revenue per category (AGGREGATION):**

- Insight: Helps find the most profitable product categories.

#### **Q5. Monthly sales totals for 2025 (DATE FUNCTION):**
- Insight: Shows revenue trends per month for 2025.

#### **Q6. Classify customers based on spending (CASE): Insight:**
- Segments customers as Premium, Regular, or Low Value.

#### **Q7. Best-performing region (WITH): Insight:**
- WITH statement simplifies multi-step queries.

#### **Q8. Combine product categories and region names (UNION):**
- Insight: Demonstrates data merging across domains.

#### **Q9. Beverage sales above ₦1,000 (Logical operators):**
- Insight: Identifies high-value transactions for analysis.
