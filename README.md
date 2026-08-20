# Pharmaceutical Procurement & Spend Analytics

A data analytics project analyzing simulated pharmaceutical procurement data to identify **spending patterns, supplier performance issues, cost-saving opportunities, and sourcing risks**.

I built this project to understand how data analytics can support procurement and strategic sourcing decisions within the pharmaceutical industry.

**Interactive Tableau Dashboard:** https://public.tableau.com/app/profile/mahit.patel/viz/PharmaceuticalProcurementSpendingAnalyticsDashboard/Dashboard?publish=yes

---

## Project Goal

Imagine you are a procurement analyst at a pharmaceutical company.

Leadership wants to know:

* Where is the company spending the most money?
* Which suppliers are the most important?
* Which suppliers have poor delivery performance?
* Are we paying different prices for similar materials?
* Where could procurement costs potentially be reduced?
* How exposed is the company to supplier and geographic risk?

I used Python and Tableau to analyze these questions and turn the results into an executive procurement dashboard.

---

## Dataset

The project uses approximately **1,200 simulated purchase orders** from FY2024–FY2025.

The dataset contains:

* 10 suppliers
* 10 materials
* 5 procurement categories
* Supplier locations across the U.S., Europe, and Asia
* Purchase quantities and prices
* Supplier lead times
* Delivery performance
* Total procurement spend

The five procurement categories are:

* Raw Materials
* Manufacturing Consumables
* Lab Supplies
* Packaging
* Medical Devices

> **Note:**The dataset used for this project was synthetically generated for analysis.

---

## What I Did

### 1. Cleaned and Prepared the Data

Using **Python and pandas**, I:

* Checked for missing and duplicate records
* Standardized supplier and material information
* Converted date columns into usable formats
* Created calculated fields for procurement analysis
* Prepared a cleaned dataset for Tableau

### 2. Analyzed Procurement Spend

I calculated:

* Total procurement spend
* Spend by supplier
* Spend by category
* Monthly purchasing trends
* Supplier concentration

This helped identify where the company was spending the most money and which supplier relationships had the greatest financial importance.

### 3. Evaluated Supplier Performance

I compared suppliers based on:

* Average lead time
* On-time delivery percentage
* Total spend
* Delivery reliability

This made it possible to identify suppliers that were inexpensive but less reliable, as well as suppliers that provided stronger overall performance.

### 4. Estimated Potential Savings

I compared supplier pricing for similar materials to identify areas where the company could potentially reduce procurement costs through:

* Supplier renegotiation
* Alternative sourcing
* Purchasing consolidation

The analysis identified approximately **$14.3M in estimated potential savings**, representing about **8% of total procurement spend**.

### 5. Built an Executive Tableau Dashboard

I created an interactive Tableau dashboard so procurement leadership could quickly explore the results.

The dashboard includes:

* Total Spend
* Potential Savings
* Supplier Count
* Average Lead Time
* On-Time Delivery %
* Supplier Spend Ranking
* Category Spend Breakdown
* Monthly Spend Trends
* Geographic Sourcing
* Supplier Performance Scorecard

Users can also filter the dashboard by **year, supplier, and procurement category**.

---

## Key Results

| Metric                          |         Result |
| ------------------------------- | -------------: |
| **Total Procurement Spend**     |    **$178.3M** |
| **Estimated Potential Savings** |     **$14.3M** |
| **Potential Savings Rate**      |       **8.0%** |
| **Suppliers**                   |         **10** |
| **Average Lead Time**           | **20.55 Days** |
| **On-Time Delivery**            |      **87.8%** |

### Main Findings

**Supplier Concentration**

PharmaCorp Global accounted for approximately **$31.1M**, or **17.4% of total procurement spend**, making it the largest supplier relationship in the dataset.

**Category Concentration**

Raw Materials and Manufacturing Consumables represented more than **80% of total spend**, making these categories the largest opportunities for strategic sourcing and cost reduction.

**Supplier Reliability**

Overall on-time delivery was **87.8%**, but performance varied significantly between suppliers.

* Meridian Chem Group: **75.0%**
* ChemPro Solutions: **77.7%**

These suppliers demonstrate an important procurement tradeoff between **lower cost and supplier reliability**.

**Potential Savings**

Pricing analysis identified approximately **$14.3M in modeled savings opportunities**, primarily through supplier pricing comparisons, consolidation, and renegotiation.

---

## Tools Used

**Python**

* pandas
* matplotlib
* Jupyter Notebook

Used for data cleaning, calculations, exploratory analysis, and supplier-performance analysis.

**Tableau Public**

Used to build the interactive procurement dashboard and communicate the results visually.

**GitHub**

Used to document and present the complete project.
---

## Skills Demonstrated

`Python` `Data Cleaning` `Exploratory Data Analysis` `Procurement Analytics` `Spend Analysis` `Supplier Performance` `Strategic Sourcing` `Cost Savings Analysis` `Supply Chain Analytics` `Tableau` `Data Visualization`

---

## Why I Built This Project

After learning more about procurement within the pharmaceutical industry, I became interested in how data can be used to support sourcing and operational decisions.

I built this project to apply data analytics to a realistic pharmaceutical procurement problem and gain hands-on experience using **Python, procurement analytics, and Tableau** to turn raw purchasing data into actionable business insights.
