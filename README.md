# DSA 3050A Advanced Power BI Examination

## Student Information

**Name:** Van Tasi  
**Student ID:** 666756  
**Course:** DSA 3050A – Business Intelligence & Data Visualization  

---

## Project Title

# S&P 500 Stock Market Performance Analysis

---

## Project Overview

This project presents an advanced Power BI analytical solution developed using real-world stock market data sourced from Kaggle. The report focuses on analyzing stock price trends, sector performance, volatility, and company-level performance across the S&P 500 market.

The main transactional dataset contains approximately **660,000 rows**, making it suitable for enterprise-level Business Intelligence implementation and advanced analytical reporting.

---

## Problem Statement

The objective of this project is to provide decision-makers with a professional Business Intelligence dashboard capable of identifying:

- performance trends  
- growth opportunities  
- volatility risks  
- sector-level investment insights  
- top and bottom performing companies  

This supports strategic financial decision-making and market performance evaluation.

---

## Dataset Description

The dataset includes:

- Daily stock prices  
- Company metadata  
- Sector classifications  
- Historical market observations from 2010 to 2024  

### Tables Used

### Fact Table
- `Fact_StockPrices`

### Dimension Tables
- `Dim_Company`
- `Dim_Date`

### Key Fields

- Date  
- Open  
- Close  
- High  
- Low  
- Volume  
- Sector  
- Company Name  
- Country  
- Market Cap  

### Source

**Kaggle – S&P 500 Stocks Dataset**

---

## Tools Used

- Power BI Desktop  
- Power Query  
- DAX (Data Analysis Expressions)  
- Power BI Service  
- GitHub  

---

## Data Preparation Steps

The following major transformations were performed:

- Removing duplicates  
- Handling missing values  
- Correcting data types  
- Removing unnecessary columns  
- Standardizing text fields  
- Creating calculated columns  
- Extracting Year, Month, and Quarter  
- Creating a Date dimension table  
- Building a Star Schema model  

---

## Data Model Structure

A clean **Star Schema** was implemented:

### Central Fact Table
- `Fact_StockPrices`

### Connected Dimensions
- `Dim_Company`
- `Dim_Date`

Relationships were configured using:

- One-to-Many (1:*) cardinality  
- Single-direction filtering  
- Hidden technical fields for cleaner reporting  

This structure supports efficient querying and accurate reporting.

---

## Key DAX Measures

The following measures were created:

- Total Volume  
- Average Close Price  
- Average Daily Return %  
- Average Price Range  
- Previous Year Average Close  
- Year-over-Year (YoY) Growth %  
- Year-To-Date (YTD) Close  
- Company Rank  

These measures support time intelligence, ranking, growth analysis, and executive decision-making.

---

## Dashboard Pages

## Page 1 – Executive Summary

Includes:

- KPI Cards  
- Price Trend Line Chart  
- Sector Comparison  
- Market Volatility Distribution  
- Interactive Slicers  

Focus:
High-level executive decision support.

---

## Page 2 – Detailed Analysis

Includes:

- Matrix/Table Analysis  
- Drill-Down Trend Analysis  
- Company-Level Breakdown  
- Sector vs Company Comparison  

Focus:
Detailed operational and company-level insights.

---

## Page 3 – Insights & Performance

Includes:

- Top 10 Performing Companies  
- Bottom 10 Performing Companies  
- Sector Growth Comparison  
- Volatility Analysis  
- Cross-filter interactions  

Focus:
Performance monitoring and strategic insights.

---

## Key Analytical Insights

- Technology-related sectors show stronger average performance over time  
- Significant market recovery is visible after 2020  
- Volatility clusters around small daily return ranges, indicating normal market behavior  
- Some sectors consistently underperform compared to the market average  
- High-value companies dominate market concentration and influence overall performance trends  

---

## Business Recommendations

Based on the analysis:

1. Focus investment attention on consistently high-performing sectors such as technology  
2. Monitor volatility spikes closely for portfolio risk management  
3. Diversify across sectors to reduce concentration risk and improve resilience  

---

## Challenges Encountered

Several practical challenges were encountered:

- Managing large dataset size (~660,000 rows)  
- Building clean and efficient relationships  
- Creating advanced DAX calculations for time intelligence  
- Power BI Publish-to-Web accessibility limitations  
- Maintaining dashboard clarity while handling multiple visuals  

These were resolved through structured modelling and optimization.

---
## Additional Files

Due to GitHub file size limitations, the complete Power BI `.pbix` file and the full transactional dataset containing approximately 660,000 rows could not be uploaded directly to GitHub.

The full project development was completed using the complete dataset and the full Power BI report file.

To maintain reproducibility and professional documentation, a representative sample dataset (`stocks_sample.csv`) has been included in this repository, while the complete `.pbix` file and full dataset are available via OneDrive.

### OneDrive Access Link

https://usiu-my.sharepoint.com/:u:/g/personal/vtasi_usiu_ac_ke/IQBUNEusiwIdRYarXmeVnqj2AU9-mgr3nh-r3jDdtmTuJ5k?e=5uFu5M


## GitHub Repository Structure

```text
DSA3050A-Advanced-PowerBI-Exam/
│
├── data/
├── screenshots/
├── report/
├── powerbi/
├── README.md
