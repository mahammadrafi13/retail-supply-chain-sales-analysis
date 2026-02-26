# 📊 Retail Supply Chain & Sales Analysis Dashboard

# 📌 Project Overview

This project is an interactive business intelligence dashboard built
using Power BI (by Microsoft) to analyze retail sales, profitability,
and supply chain performance.

The dashboard provides actionable insights into:

-   Revenue performance
-   Profit trends
-   Gross margin analysis
-   Regional sales performance
-   Category-level profitability
-   Seasonal demand patterns
-   High-revenue but low-margin products

This project demonstrates strong skills in data modeling, DAX,
visualization design, and business problem-solving.

# 🎯 Business Problem

Retail businesses often struggle with:

-   Identifying profitable vs. non-profitable products
-   Understanding regional performance variations
-   Tracking seasonal demand patterns
-   Detecting revenue concentration risks
-   Monitoring gross margin fluctuations

This dashboard helps decision-makers quickly identify performance gaps
and optimization opportunities.

# 📂 Dataset Description

The dataset includes:

-   Order Date
-   Product Name
-   Product Category
-   Region
-   Sales Amount
-   Profit
-   Quantity
-   Cost / Production Cost
-   Month-Year

The data was cleaned, transformed, and modeled before visualization.

# 🛠 Tools & Technologies Used

-   Power BI Desktop
-   Data Modeling (Star Schema approach)
-   DAX Measures
-   KPI Cards
-   Line & Bar Charts
-   Scatter Plot (Revenue vs Profit Analysis)
-   Slicers (Year, Category, Region)


# 📐 Data Modeling Approach

-   Fact Table: Sales Data
-   Dimension Tables: Date, Product, Region, Category

Relationships were configured properly to avoid many-to-many issues and
ensure accurate calculations.


# 📊 Key DAX Measures

key dax measures
- Total Sales = SUM(Sales[Sales])
- Total Profit = SUM(Sales[Profit])
- Gross Margin % = DIVIDE([Total Profit], [Total Sales], 0)


# 📈 Dashboard Features

# 🔹 Page 1 -- Executive Performance Overview

-   KPI Cards: Total Sales, Total Profit, Gross Margin %
-   Sales Trend (Year/Month)
-   Profit Trend
-   Regional Sales Comparison
-   Category Contribution

# 🔹 Page 2 -- Profitability & Product Insights

-   Sales vs Profit Scatter Plot
-   Top Performing Products
-   Low Margin High Revenue Products
-   Seasonal Demand Analysis
-   Interactive Slicers (Year, Region, Category)

# 🔍 Key Insights Generated

-   Technology category generates highest revenue
-   Some high-revenue products have low profit margins
-   Certain regions outperform others consistently
-   Clear seasonal demand spikes visible in specific months
-   Gross margin trend helps monitor profitability health

# 💡 Business Value

This dashboard helps:

-   Identify underperforming products
-   Optimize pricing strategies
-   Improve supply chain decisions
-   Reduce revenue concentration risk
-   Enhance profitability monitoring

# 🚀 How to Use

1.  Download the .pbix file
2.  Open using Power BI Desktop
3.  Use slicers to filter by Year, Region, Category
4.  Interact with visuals for detailed insights

# 📁 Repository Structure

Retail-Supply-Chain-Sales-Analysis/
│
├── retail-supply-chain-sales-analysis.pbix
├── dashboard-page-1.jpg
├── dashboard-page-2.jpg
├── retail-store-messy-data.csv
└── README.md

# 👨‍💻 Author

Mahammad Rafi
GitHub: mahammadrafi13
Focused on Data Analytics | Business Intelligence | Dashboard Design

# 📌 Future Improvements

-   Add Forecasting using time intelligence
-   Implement Drill-through pages
-   Add Customer Segmentation
-   Publish to Power BI Service for live sharing
-   Embed report in portfolio website
