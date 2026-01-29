# EdTech Lead Conversion Data Analysis

A comprehensive data analytics project focused on understanding lead conversion patterns and sales performance in an EdTech environment using mock data. The project covers data cleaning, validation, multi‑dimensional analysis, and visualization to generate actionable business insights.

## Project Overview

This project analyzes an EdTech lead dataset to:

* Understand how leads convert across **regions, lead sources, student types, and course categories**
* Evaluate **salesperson and regional performance**
* Identify bottlenecks and high‑performing segments
* Provide data‑driven recommendations to improve conversion rates and revenue

The dataset represents the complete lead lifecycle from first contact to final conversion.

## Project Goal

To perform systematic data cleaning, validation, and exploratory analysis on EdTech lead data and generate meaningful insights that help optimize:

* Marketing strategy
* Sales team effectiveness
* Regional targeting
* Customer segmentation

##  Data Cleaning & Preparation

Key steps performed:

### 1. Date Validation

* Incorrect or illogical dates were **not deleted**.
* A new column `Date_quality_flag` was created to mark records as `valid` or `not valid` using Excel IF conditions.

### 2. Handling Missing Values

* Replaced blank cells with `NA` to ensure:

  * Consistent filtering and aggregation
  * Accurate visualizations
  * Reliable future analysis

### 3. Text Standardization

* Standardized categorical fields (region, lead source, student type, etc.) to avoid duplication due to case or spacing issues.

### 4. Column Reduction

Removed irrelevant or redundant columns:

* Date of lead generation
* Date of last contact
* Conversion date
* Marketing campaign (duplicate of lead source)

##  Analysis Performed

### 1. Conversion Analysis

* Conversion rate by **region**
* Conversion rate by **lead source & region**
* Conversion rate by **student type & region**

### 2. Sales Performance Analysis

* Sales by **salesperson**
* Sales by **region**
* Sales by **salesperson–region combinations**

##  Key Insights

* West region outperforms North by ~11% in conversion rate.
* Social media is the highest‑performing lead source.
* Students form the most valuable segment (~40% of conversions).
* East region students show strong conversion behavior.
* Working professionals convert the least, especially in South and East regions.
* Raj is the top‑performing salesperson by revenue and conversions.
* West region generates the highest overall sales.

## Tools & Technologies

* **Microsoft Excel** – Data cleaning, validation, pivot analysis
* **Power BI / Excel Charts** – Visualization (if applicable)


⭐ If you find this project useful, feel free to star the repository!
