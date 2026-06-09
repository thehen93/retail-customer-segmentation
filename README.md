# Online Retail Customer Segmentation

Customer segmentation and market basket analysis of the UCI Online Retail dataset using RFM analysis, K-means clustering and the Apriori algorithm in Python.

## Project Overview

This project analyzes an online retail dataset containing transactions from a UK-based retailer between December 2010 and November 2011. The goal is to identify customer groups with similar purchasing behavior and understand what products are commonly bought together.

## Dataset

- **Source:** [UCI Machine Learning Repository — Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Creator:** Daqing Chen
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **Size:** ~540,000 transactions
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Analysis

- **Data cleaning** — handling missing values, removing duplicates, detecting anomalies and validating data formats
- **Temporal analysis** — examining how sales, revenue and customer base changed over time
- **Customer segmentation** — RFM analysis (Recency, Frequency, Monetary) with K-means clustering to identify customer groups
- **Market basket analysis** — Apriori algorithm to find products commonly bought together

## Results

- 3 distinct customer segments identified: Loyal High Spenders, Occasional Customers and Lost/Inactive Customers
- Strong product associations found, particularly within matching product sets and design variants

## Libraries Used

pandas, numpy, matplotlib, seaborn, scikit-learn, mlxtend

## Setup

```bash
pip install -r requirements.txt
```

Then open `retail-customer-segmentation.ipynb` in Jupyter.
