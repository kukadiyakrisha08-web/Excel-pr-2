# 📊 PR.2 ANALYZER

## Sales Performance Dashboard & Data Analysis using Microsoft Excel

```{=html}
<p align="center">
```
**Turning raw sales records into meaningful business insights**
```{=html}
</p>
```

------------------------------------------------------------------------

## 👋 About the Project

**PR.2 Analyzer** is an Excel-based Sales Data Analysis project. The
purpose of this project is to organize sales records, calculate
important business metrics, compare performance across customers,
regions, products and months, and present the findings through a
dashboard and analysis sheets.

The workbook contains **81 sales records** covering **January 2026 to
June 2026**. It includes sales, profit, discount, customer, product and
regional analysis.

## 🎯 Project Objectives

-   Calculate overall Sales, Profit, Orders and Average Discount.
-   Understand customer-wise purchasing and identify high-value
    customers.
-   Compare sales performance across regions and products.
-   Study monthly sales movement and month-over-month growth.
-   Examine how different discount rates affect total profit.
-   Study the relationship between Sales and Profit using regression.
-   Summarize the data with descriptive statistics and dashboard KPIs.

## 🗂️ Workbook Structure

  -----------------------------------------------------------------------
  Sheet                               What it contains
  ----------------------------------- -----------------------------------
  **Dashboard**                       Main KPIs and key business insights
                                      in one place.

  **Sales Data**                      Order-level records, including
                                      customer, region, product, date,
                                      quantity, price, cost, discount,
                                      sales and profit.

  **Customer Summary**                Customer-wise total purchase and
                                      total profit.

  **WHAT-IF Analysis**                A discount input and a sensitivity
                                      table showing the effect of
                                      discount rates on total profit.

  **Regression Analysis**             Regression statistics for the
                                      relationship between Sales (X) and
                                      Profit (Y).

  **Descriptive Statistics**          Statistical measures for Sales and
                                      Profit, such as mean, median,
                                      standard deviation, minimum and
                                      maximum.

  **Monthly Growth**                  Monthly sales totals and growth
                                      compared with the previous month.

  **High-Value Customers**            Top 10 customers ranked by total
                                      purchase, with region.

  **Pivot Summary**                   Sales summarized by Region and
                                      Product using a SUMIFS-based
                                      cross-tab.

  **Charts**                          Sheet reserved for KPI
                                      visualizations.

  **Sheet1**                          Blank/default worksheet.
  -----------------------------------------------------------------------

## 📌 Dashboard Highlights

The following values are taken from the workbook's Dashboard:

  KPI / Insight                          Result
  -------------------------- ------------------
  Total Sales                    **120,894.01**
  Total Profit                    **49,077.96**
  Total Orders / Records                 **81**
  Average Discount                    **9.63%**
  Top Customer                 **Sanjay Desai**
  Top Customer Purchases          **14,426.24**
  Best Sales Month                   **May-26**
  May-26 Sales                    **26,702.18**
  Strongest Region                    **South**
  South Region Sales              **53,849.75**
  Sales-Profit Correlation             **0.99**

*Note: Currency values are shown in the workbook's numeric format; no
currency symbol or currency code is specified in the source data.*

## 🔎 Analysis Details

### 1. Sales Data

The source sheet contains 81 order records. Important fields include
OrderID, CustomerName, Region, Product, OrderDate, Quantity, UnitPrice,
UnitCost, Discount, Sales, Profit and MonthLabel.

### 2. Customer Analysis

The Customer Summary sheet compares total purchases and total profit
customer-wise. The High-Value Customers sheet ranks the top 10
customers. Sanjay Desai is ranked first with purchases of 14,426.24.

### 3. Discount What-If Analysis

The WHAT-IF Analysis sheet lets the user change the discount input and
view the resulting total profit. Its sensitivity table shows these
example results:

    Discount Rate   Total Profit
  --------------- --------------
               0%      54,641.64
               5%      47,919.73
              10%      41,197.82
              15%      34,475.91
              20%      27,754.00
              25%      21,032.09
              30%      14,310.18

This illustrates that, under the workbook's assumptions, higher discount
rates reduce total profit.

### 4. Regression Analysis

The workbook models **Profit as Y** and **Sales as X**.

-   Multiple R: **0.9924**
-   R Square: **0.9849**
-   Observations: **81**
-   Sales coefficient (slope): **0.4050**
-   Intercept: **1.4638**

The high R Square indicates that Sales and Profit have a strong linear
relationship in this dataset. This is an association in the data; it
does not by itself prove that sales changes cause profit changes.

### 5. Descriptive Statistics

For Sales: - Mean: **1,492.52** - Median: **1,298.70** - Standard
Deviation: **1,003.54** - Minimum: **143.49** - Maximum: **4,412.14**

For Profit: - Mean: **605.90** - Median: **526.44** - Standard
Deviation: **409.52** - Minimum: **49.00** - Maximum: **1,691.87**

### 6. Monthly Growth

May-26 is the strongest month in the available period, with sales of
**26,702.18**. Its growth compared with April-26 is approximately
**52.52%**. The workbook contains monthly entries from Jan-26 through
Jun-26.

### 7. Region and Product Summary

The Pivot Summary sheet compares four regions and four products. South
is the leading region with total sales of **53,849.75**. Product B has
the highest overall product sales at **44,628.20**.

## 🧰 Tools & Excel Techniques

-   Microsoft Excel
-   Excel formulas and calculated columns
-   `SUMIFS` for customer, region and product summaries
-   KPI dashboard presentation
-   What-If / discount sensitivity analysis
-   Linear regression statistics
-   Descriptive statistics
-   Monthly growth calculation
-   Summary tables and charts

## ▶️ How to Explore the Workbook

1.  Open `PR2_Analyzer.xlsx` in Microsoft Excel.
2.  Start with the **Dashboard** sheet for the main results.
3.  Open **Sales Data** to inspect the source records and calculated
    fields.
4.  Explore **Customer Summary** and **High-Value Customers** for
    customer insights.
5.  Open **WHAT-IF Analysis** to change the discount input and inspect
    the profit result.
6.  Review **Regression Analysis**, **Descriptive Statistics**,
    **Monthly Growth** and **Pivot Summary** for deeper analysis.

## ⚠️ Notes

-   The analysis is based on the 81 records included in this workbook.
-   The workbook's Timestamp field uses `NOW()` and may update whenever
    Excel recalculates the workbook.
-   The source workbook does not specify a currency code, so this README
    does not assign one.
-   The `Charts` sheet contains a KPI visualizations heading; the main
    numeric results are documented above from the Dashboard and analysis
    sheets.

## 👨‍💻 Author

**Name:** \[krisha kukadiya\]\
**Project:** PR.2 Analyzer\
**Technology:** Microsoft Excel\
**Project Type:** Sales Data Analysis

## 🙏 Acknowledgement

I would like to express my sincere gratitude to my respected
teacher/mentor for the guidance, support and valuable suggestions
provided during this project.

I am also thankful to everyone who supported and encouraged me while
completing this work. This project helped me improve my understanding of
Microsoft Excel, data analysis, formulas, statistical concepts and
dashboard reporting.

## 📬 Thank You

Thank you for taking the time to review my project.

**PR.2 Analyzer --- Sales Performance Dashboard & Data Analysis**
