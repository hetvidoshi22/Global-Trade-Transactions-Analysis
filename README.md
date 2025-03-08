📊 Global Trade Transactions Analysis 🌍
Overview
This project analyzes import and export transactions to understand global trade trends. It looks at trade values, product types, transportation methods, and country-wise trade flows to find useful insights, such as the most traded products and preferred shipping methods.

Dataset Details
The dataset (trade_transaction_data.xlsx) contains 10 columns:

Column Name	Description
Transaction_ID	Unique ID for each trade transaction
Trade_Type	Whether it is an Import or Export
HS_Code	Product classification code
Product_Name	Name of the traded product
Quantity	Number of items traded
Trade_Value	Value of the trade (in currency)
Country_of_Origin	Country from where the goods were shipped
Country_of_Destination	Country where the goods were delivered
Mode_of_Transport	Transport method (Air, Sea, Rail, Road)
Incoterms	Trade agreement terms (EXW, FOB, CIF, etc.)
🔹 Note: This dataset was generated using ChatGPT and does not represent real-world trade data. It is meant for learning and analytical practice only.

Key Insights
🔹 Handling Data Issues
✅ Identified and fixed outliers in the Trade_Value column using the IQR method.
✅ Replaced extreme values with averages to maintain accuracy.

🔹 Trade Trends & Patterns
📌 Top 5 most traded products by volume and value.
📌 Major trading countries based on total trade value.
📌 Most used transportation methods for high-value goods.

🔹 Effect of Incoterms on Trade Costs
📌 Analyzed which Incoterms are most used and how they affect trade pricing.

Technologies Used
Python 🐍 (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook 📓 for data analysis
