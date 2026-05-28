# National-Clothing-Chain

## Setup Instructions

This report uses local data files.

To use:
1. Download the repository
2. Open the Power BI file
3. Go to:
   Transform Data → Data Source Settings
4. Update file paths to your local data folder


👕 National Clothing Chain: Targeted Marketing Strategy (Power BI)
🚀 Overview
This project was completed as part of the Udacity Business Intelligence Nanodegree. It focuses on building a data-driven marketing strategy for a national clothing retailer experiencing stagnant sales.
Using Power BI, I analyzed customer behavior, income patterns, and product performance to determine which products should be marketed to which customers for maximum impact.

🧠 Business Problem
The company wants to re-engage customers with targeted advertising but lacks insight into:

Customer income levels
Product fit by demographic
Regional sales patterns

The goal of this project is to predict customer income and align product recommendations accordingly.
Products:

Shirt — $25
Sweater — $100
Leather Bag — $1,000


🎯 Key Objectives
This analysis answers the following business questions:

What is the relationship between income and sales?
What is the relationship between product ratings and return rates?
Can we predict customer income using sales data?
Which customer has the highest predicted income?
Which product should be advertised most frequently?


📊 Key Results
📈 Sales vs Income

Correlation (R): 0.88
R² Value: 0.78

➡️ Strong positive relationship:
Higher-income regions tend to generate higher sales.

🔄 Ratings vs Return Rate

Correlation (R): -0.83
R² Value: 0.69

➡️ Strong negative relationship:
Higher-rated products result in significantly fewer returns.

📐 Regression Model
Used to predict customer income from sales:
Y (Income) = 72.43X (Sales) + 72,638.21

➡️ Enables customer segmentation and targeted marketing.

🏆 Highest Predicted Income

Customer ID: JLit30836
Name: Jon Little


📢 Product Recommendation

✅ Shirts should be advertised the most
➡️ Broad affordability + largest target segment


📊 Dashboard Features
🔹 Core Visuals (Cross-Filtering Page)

Histogram: Income distribution
Heat Map: Household income by location
Scatterplot + Trendline: Income vs Sales
KPI Card: R² correlation value

🔹 Additional Visuals

Product performance analysis
Customer segmentation insights
Return rate breakdown
Demographic exploration


🛠️ Tools & Techniques

Power BI
Power Query (data cleaning & transformation)
DAX (calculated columns, measures, segmentation logic)
Linear regression modeling
Data visualization & dashboard design


🔍 Additional Analysis
Ratings vs Returns Regression
Y (Return Rate) = -0.01X (Rating) + 0.05

➡️ A 1-star increase in rating reduces return rate by ~1%
📌 Insight: Product quality and customer satisfaction directly impact profitability.

💡 Business Recommendations
1. 📢 Advertising Strategy

Focus heavily on shirts (largest accessible market)
Use tiered marketing for sweaters and premium items


2. 🎯 Customer Segmentation

Use predicted income to:

Target promotions
Recommend appropriate products
Personalize campaigns




3. ⭐ Product Quality Focus

Low-rated products should be flagged and improved
Improving ratings reduces costly returns


4. 📉 Return Reduction Strategy

Address quality issues proactively
Monitor rating trends as an early warning signal


▶️ How to Use

Open the .pbix file in Power BI Desktop
Explore:

Income distribution
Sales performance
Regional trends


Use interactive visuals to:

Filter by location
Drill into customer segments
Analyze correlations




📌 Final Takeaway
This project demonstrates how combining customer data, external census data, and statistical modeling can unlock powerful marketing insights.
By predicting income and understanding behavior patterns, the company can:

Increase marketing efficiency
Improve product targeting
Reduce returns
Drive revenue growth


🙋‍♀️ Author
Lydia Longanecker

GitHub: https://github.com/yourusername
LinkedIn: https://linkedin.com/in/yourprofile


📎 Acknowledgments
This project was completed as part of the Udacity Business Intelligence Nanodegree, using provided datasets including U.S. Census data, customer transactions, and product performance metrics.
