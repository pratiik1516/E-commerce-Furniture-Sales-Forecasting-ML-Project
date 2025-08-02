# 🛋️ E-commerce Furniture Dataset 2024 – Sales Prediction & Analysis

This project involves data analysis and predictive modeling on a furniture dataset scraped from AliExpress to forecast product sales, uncover pricing insights, and identify trends in online consumer behavior.

---

## 📌 Project Objective

To predict the number of furniture items sold (`sold`) based on key product attributes such as `price`, `tagText`, and `productTitle`.

---

## 🧰 Tools & Technologies

- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **ML Models**: Linear Regression, Random Forest Regressor  
- **Other Tools**: Jupyter Notebook, Git

---

## 📊 Dataset Overview

- **Source**: Scraped from AliExpress (via Apify)  
- **Size**: 2,000 furniture product entries  
- **Features**:
  - `productTitle`: Item name
  - `price`: Selling price
  - `originalPrice`: Original price (with discounts)
  - `sold`: Units sold
  - `tagText`: Shipping or promotional tags

---

## 🔍 Workflow

1. **Data Cleaning**  
   - Removed missing and irrelevant values  
   - Encoded categorical tags  

2. **Exploratory Data Analysis (EDA)**  
   - Identified patterns in pricing, shipping tags, and sales volume  
   - Visualized relationships using scatter plots and histograms  

3. **Feature Engineering**  
   - Calculated discount percentages  
   - Converted `productTitle` to TF-IDF vectors (100+ features)

4. **Model Training & Evaluation**  
   - Trained Linear Regression & Random Forest models  
   - Random Forest achieved **85% R² score** on test data  
   - Evaluated using Mean Squared Error and R² Score

---

## 📈 Key Outcomes

- **85% accuracy** in sales prediction using Random Forest  
- **~15% performance boost** through feature engineering  
- Found that **Free Shipping** correlates with a **30% increase** in average sales


