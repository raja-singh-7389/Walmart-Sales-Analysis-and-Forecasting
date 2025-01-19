# 🛍️ Walmart Sales Analysis and Forecasting

📊 Analyze, Understand, and Forecast Weekly Sales for Walmart Stores

This project uses a dataset of Walmart store sales to perform Exploratory Data Analysis (EDA), identify patterns, relationships, and seasonal trends, and forecast future sales using predictive modeling.

🚀 Features
	•	📈 Correlation Analysis: Understand the impact of unemployment, CPI, and temperature on sales.
	•	🗓️ Seasonal Trends: Analyze monthly trends to identify peak sales periods.
	•	🔍 Top & Worst Performers: Identify the highest and lowest-performing stores.
	•	🔮 Sales Forecasting: Predict weekly sales for the next 12 weeks for each store.
	•	📊 Visualizations: Create meaningful plots to make insights more intuitive.

📁 Dataset Information

The dataset (walmart.csv) contains 6435 rows and 8 columns:

Column	Description
Store	Store number
Date	Week of sales
Weekly_Sales	Weekly sales for the given store
Holiday_Flag	Whether the week is a holiday (1 = Yes, 0 = No)
Temperature	Temperature on the sales day
Fuel_Price	Cost of fuel in the region
CPI	Consumer Price Index
Unemployment	Unemployment rate

🛠️ Tech Stack
	•	Languages: Python 🐍
	•	Libraries:
	•	Data Manipulation: pandas, numpy
	•	Visualization: matplotlib, seaborn
	•	Predictive Modeling: statsmodels, scikit-learn, xgboost

📂 Directory Structure

project-folder/
│
├── walmart.csv                # Dataset
├── analysis_and_modeling.py   # Analysis and forecasting code
├── README.md                  # Project documentation
└── plots/                     # Saved visualizations

📊 Key Insights

a. Impact of Unemployment

Stores most affected by unemployment rate have been identified based on the negative correlation between unemployment and sales.

b. Seasonal Trends

Sales show a clear seasonal trend, with peaks during major holiday months.

c. Effect of Temperature

Some stores display a significant correlation between temperature and sales, indicating sensitivity to weather changes.

d. Consumer Price Index (CPI)

CPI impacts sales for certain stores, with some stores showing a decline in sales as CPI increases.

e. Top Performing Stores

Top 5 performing stores were identified based on historical sales data.

f. Worst Performing Stores

The least-performing store was identified, and the performance gap between the best and worst stores was analyzed.
