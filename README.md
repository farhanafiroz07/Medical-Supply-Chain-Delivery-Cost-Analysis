# Medical Supply Chain Analytics: Delivery and Cost Analysis

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of medical supply chain data to understand shipment delivery patterns, logistics costs, vendor distribution, and transportation methods.

Using Python, the project explores shipment records, identifies trends, examines relationships between numerical variables, and generates insights through data visualization.

## Project Objectives
- Understand medical supply chain shipment data.
- Analyze shipment and delivery performance.
- Explore shipment patterns across countries, vendors, and product groups.
- Compare different transportation methods.
- Analyze freight and insurance costs.
- Examine relationships between shipment quantities, product prices, and logistics costs.
- Identify unusual observations using statistical techniques.
- Generate meaningful insights through visualizations.

## Dataset Overview
- **Total Records:** 10,324
- **Total Columns:** 33
- **Domain:** Medical Supply Chain

The dataset contains information about:
- Shipment and delivery dates
- Countries and vendors
- Medical product groups
- Transportation methods
- Shipment quantities and product values
- Freight and insurance costs
- Manufacturing sites

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Performed
1. Data inspection and understanding
2. Data cleaning and preprocessing
3. Missing value and duplicate checks
4. Date and time analysis
5. Univariate analysis
6. Bivariate analysis
7. Multivariate analysis
8. Vendor and country analysis
9. Shipment mode analysis
10. Freight and insurance cost analysis
11. Correlation analysis
12. Outlier detection using the IQR method
13. Data visualization

## Key Findings
- The dataset includes 73 unique vendors, 88 manufacturing sites, 43 countries, and 5 product groups.
- Air transportation accounts for the largest share of total freight costs among the shipment modes analyzed.
- Monthly shipment volumes vary throughout the year.
- The average freight cost is higher than the average insurance cost.
- IQR-based outlier detection identified 1,127 high-value orders, representing approximately 10.92% of all orders.
- High-value observations were retained because they may represent genuine large medical supply orders.

## Project Structure
```text
Medical-Supply-Chain-Delivery-Cost-Analysis/
│
├── README.md
├── .gitignore
├── Medical_Supply_Chain_Analytics.ipynb
└── shipment_data.csv
```

## Conclusion
This project explores medical supply chain operations through exploratory data analysis, focusing on shipment delivery patterns, vendor distribution, transportation methods, and logistics costs.

The analysis provides insights into shipment characteristics, cost patterns, and relationships between different numerical variables. These findings provide a foundation for further analysis and potential machine learning applications.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Medical Supply Chain Analytics
