# 🛍️ Amazon Product Data Analysis

This project performs data cleaning, transformation, and basic analysis on an Amazon product dataset using Python libraries such as **Pandas**, **NumPy**, and **Matplotlib**.

## 📁 Dataset

The dataset contains product-related information scraped from Amazon. Some columns include:

- `product_name`
- `discounted_price`
- `actual_price`
- `discount_percentage`
- `rating`
- `rating_count`

  ## 📊 Objectives

- Clean and convert price and discount data to numerical format
- Handle missing or malformed values
- Prepare the data for future analysis or machine learning tasks
- Visualize product ratings and discount patterns

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** – data cleaning and manipulation
- **NumPy** – numerical processing
- **Matplotlib** – data visualization

## 📌 Key Steps

1. **Data Loading**  
   Load and preview the dataset using `pandas`.

2. **Data Cleaning**  
   Remove special characters (`₹`, `%`, `,`) and convert strings to numeric values.

3. **Handling Missing Data**  
   Convert non-numeric or malformed values to `NaN` and optionally fill/drop them.

4. **Visualization**  
   - Plot product rating distributions  
   - Compare actual vs discounted prices  
   - Visualize discount percentages

## 🚀 Future Improvements

- Add category-wise product analysis
- Integrate with Power BI or Plotly for interactive dashboards
- Perform sentiment analysis on product reviews (if available)

## 📎 How to Run

# Install dependencies
pip install pandas numpy matplotlib

# Run the notebook
jupyter notebook Amazon_Data_Analysis.ipynb
