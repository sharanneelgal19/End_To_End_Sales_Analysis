📊 Regional Sales Analysis
Overview

This project analyzes historical regional sales data to identify sales trends, profitability patterns, top-performing products, seasonal variations, and channel performance.

The project follows a complete data analytics workflow using Python for data preparation and EDA and Power BI for interactive visualization and business insights.

Dataset

The dataset contains sales information covering multiple years across U.S. regions and includes information related to:

Orders and order dates
Customers
Products
Sales channels
Revenue and cost
Profit and profit margin
States and regions
Budgets

The data was cleaned, transformed, and combined from multiple tables before analysis.

Tools & Technologies
Python
Pandas
NumPy
Matplotlib / Seaborn
Jupyter Notebook / Google Colab
Power BI
Microsoft Excel
Project Steps


1. Data Loading

Loaded the sales dataset into Python and performed an initial exploration to understand its structure and variables.

2. Data Cleaning

Combined relevant tables
Removed redundant columns
Standardized column names
Renamed columns where required
Checked for missing values and duplicates
Prepared the dataset for analysis

4. Feature Engineering

Created additional analytical fields such as:

Profit
Profit Margin %
Order Month
Month Number
Regional and geographical attributes

5. Exploratory Data Analysis

Performed EDA to identify:

Monthly sales trends
Product performance
Profitability
Sales by channel
Regional and state-level performance
Seasonal patterns
Outliers and trends

6. Power BI Dashboard

Created an interactive dashboard to allow users to explore sales performance by time, product, region, and channel.

7. Report & Presentation

Prepared a project report documenting the analysis and findings, along with a PowerPoint presentation summarizing the business problem, methodology, insights, and dashboard.

Dashboard

The Power BI dashboard provides an interactive view of:

Revenue
Profit
Profit Margin
Product performance
Regional sales
State-level performance
Sales channels
Monthly trends

Users can apply filters to explore different dimensions of the sales data.

Results & Key Insights

The analysis identified several notable patterns:

Sales generally followed a consistent monthly cycle, with peaks around May–June and lower sales in January.
Products 26 and 25 were among the leading products by revenue.
Wholesale contributed the largest share of sales, followed by Distributor and Export channels.
California recorded the highest total sales among states in the analysis.
Product-level analysis highlighted opportunities to improve lower-performing products and grow mid-tier products.


How to Run

Python
Clone or download this repository.

Install the required Python libraries:

pip install pandas numpy matplotlib seaborn openpyxl

Open the Jupyter Notebook or Python file.

Update the dataset path if required.

Run the notebook cells sequentially to perform data cleaning and EDA.


Power BI
Open Power BI Desktop.
Open the .pbix dashboard file.
Refresh the data source if required.
Use the available filters and visuals to explore the analysis.
Project Structure


Regional-Sales-Analysis/
│
├── Dataset/
│   └── Regional Sales Dataset.xlsx
│
├── Python/
│   └── EDA_Regional_Sales_Analysis.ipynb
│
├── PowerBI/
│   └── SALES REPORT.pbix
│
├── Report/
│   └── Sales Report.pdf
│
├── Presentation/
│   └── Regional Sales Analysis.pptx
│
└── README.md
