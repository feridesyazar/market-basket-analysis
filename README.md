# 🛒 Market Basket Analysis | Retail Business Insights

*From transaction patterns to practical retail decisions*

**Python · Pandas · Matplotlib · EDA · Association Rules**

## About the Project

How can supermarkets turn transaction data into useful business decisions?

This project analyzes **500 product records across 153 shopping baskets** to explore best-selling products, basket sizes and product associations. The goal is to identify **testable opportunities** for cross-selling, product placement and promotions—not to promise guaranteed sales growth.

The complete analysis, visualizations and explanations are available in [Market_Basket_Analysis.ipynb](Market_Basket_Analysis.ipynb).

## Key Insights & Business Value

Using **Support, Confidence and Lift**, the analysis identifies product combinations worth exploring. For example, **Milk → Oranges** has **50% confidence** and a **Lift of 2.64**. This indicates a positive association in the sample, but does not establish that a promotion would increase sales.

To connect the findings to business practice, we also consider independent grocery-retail research from **Germany and the United States**:

| Market | Research perspective | Business experiment to test |
|---|---|---|
| 🇩🇪 **Germany** | Price awareness, value for money and convenient store access | Test clearly priced bundles, shelf offers and digital coupons |
| 🇺🇸 **United States** | In-store experience, shopping convenience and digital engagement | Test product suggestions in retailer apps and convenient placement of associated items |

**Key takeaway:** Association rules help identify *what customers buy together*. Retail market research helps inform *how to test* potential business actions.

> **Important:** The transaction dataset contains **no country information**. The Germany–US perspectives come from external research; they are **not** a statistical comparison of purchasing behavior in these two countries. The studies use different methods and should not be treated as directly comparable measurements.

## Dataset & Limitations

**Dataset reference:** [Aman Kharwal – Market Basket Analysis using Python (2023)](https://amanxai.com/2023/10/16/market-basket-analysis-using-python/)

The data includes `BillNo`, `Itemname`, `Quantity`, `Price` and `CustomerID`. There are no transaction dates, some invoices contain inconsistent customer identifiers, and the definition of `Price` is unclear. Therefore, this project does not calculate validated revenue, profit, customer loyalty or country-specific purchasing patterns.

## External Retail Research

- **Germany:** [KPMG / EHI – Consumer Barometer 2026](https://kpmg.com/de/en/media/press-releases/2026/06/between-lifestyle-and-price-sensitivity%20.html)
- **United States:** [FMI – U.S. Grocery Shopper Trends 2026](https://www.fmi.org/our-research/research-reports/u-s-grocery-shopper-trends)

*This is an exploratory Data Science case study. The recommendations are hypotheses for future testing, not proven commercial outcomes.*
