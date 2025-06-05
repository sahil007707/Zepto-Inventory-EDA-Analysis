# 📦 Zepto Dataset - EDA & Data Cleaning

## 🧠 Exploratory Data Analysis & Cleaning on Grocery Product Dataset

This project performs detailed **data cleaning**, **exploratory data analysis (EDA)**, and **visualization** on a dataset from Zepto, an Indian quick commerce platform. The goal is to extract insights related to **product pricing, discounts, stock availability**, and more.

---

## 📁 Dataset Overview

- **Source**: Kaggle / Zepto
- **Format**: CSV
- **Columns include**:
  - `name` – product name  
  - `Category` – product category  
  - `mrp` – maximum retail price  
  - `discountedSellingPrice` – discounted price  
  - `discountPercent` – discount percentage  
  - `availableQuantity`, `quantity` – stock levels  
  - `weightInGms` – weight of item in grams  
  - `outOfStock` – boolean flag for availability  

---

## 🔧 Tasks Performed

### ✅ Data Cleaning
- Checked for null values
- Removed duplicate entries
- Ensured data type consistency

### 📊 Exploratory Data Analysis
- Products out of stock
- Top products by:
  - Discount percent
  - Discount amount
  - Discounted price
- Category-wise summary of discounts
- Stock visualization

### 📈 Visualizations
- Bar plots (Seaborn) for top discounted products
- Category-wise analysis
- Horizontal bar charts for product clarity
- Scatter plots for product quantities and discounts

---

## 📌 Key Insights

- Certain products show **steep discounts** (up to 58%)
- Some **categories dominate** in high-discount products
- A large number of products are **still listed as out of stock**
- Product names need rotation or horizontal layout for clarity in plots

---

## 🛠 Tools & Libraries

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---


