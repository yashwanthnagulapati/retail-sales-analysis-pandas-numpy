# 🛍️ Retail Sales Analysis with Pandas + NumPy

## Project Overview
This project analyzes a simulated **retail sales dataset (~300 records)** using **Python (Pandas + NumPy)**.  
The goal is to demonstrate **data cleaning, exploratory analysis, and deriving business insights** from raw data.  

## 🛠️ Tools & Libraries
- Python 3  
- Pandas  
- NumPy  

## Key Analysis Steps
1. **Data Cleaning**
   - Checked for missing values and duplicates  
   - Converted `PurchaseDate` into datetime format  

2. **Exploratory Analysis**
   - Unique customers & orders count  
   - Region with the most orders  
   - Top product categories by revenue  
   - Top 5 customers by spending  
   - Average customer age by product category  

3. **Business Insights**
   - **Best-selling month:** September 2023 with ~$28.6K revenue  
   - **Customer segmentation:** Age groups (18–25, 26–35, 36–50, 51+)  
   - **High-value transactions:** Top 10% of orders above the 90th percentile  
   - Recalculated revenue using **NumPy vectorized multiplication**  

4. **Visualization**
   - Total sales revenue by month  
   - Revenue by product category  
   - Revenue contribution by age group   

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yashwanthnagulapati/retail-sales-analysis-pandas-numpy.git

2. Install dependencies:
   pip install -r requirements.txt

3. Open Jupyter Notebook and run the analysis:
  jupyter notebook retail_sales_analysis.ipynb

  
