# 🛒 Amazon Product Analysis Project
# 🔍 Project Overview
This project focuses on analyzing Amazon product data, including prices, ratings, and review metrics, to uncover actionable insights for e-commerce optimization. The analysis includes data cleaning, encoding, visualizations, and correlation studies.

# 🧾 Dataset Highlights
Product ID

Product Name

Category

Actual Price & Discounted Price

User Ratings & Rating Count

Review Title & Content

User Info & Product Links

# 🧹 Data Cleaning & Preprocessing
Removed null values and duplicates

Converted rating_count to integers

Handled inconsistent price formats (e.g., “₹1,23,999” → 123999)

Ensured all numerical fields are float/int type for analysis

# 📊 Exploratory Data Analysis
Created histograms of price distribution

Built heatmaps to visualize correlations (e.g., between price and rating)

Used groupby() to identify top-rated products

Analyzed price trends across categories

📌 Key Insights
Weak positive correlation (0.12) between price and rating

One high-priced products received strong ratings

Most data concentrated around mid-range prices (10k–40k INR)

# 📈 Visualizations
Heatmap for missing value 

Correlation heatmaps

Bar charts for missing value % in columns

Scatter plot for actual_price vs rating

Histogram For actual price distribution 

# 📁 Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

GitHub for version control

# 🔄 Future Work

Perform sentiment analysis on review content

Predict sales trends based on features

Add Power BI dashboard version for business-friendly presentation

# 📂 How to Run

1. Clone the repo
2. Open Jupyter Notebook
3. Run all cells in sequence 
