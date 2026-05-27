# 🎆 Diwali Sales Analysis — Exploratory Data Analysis

> An end-to-end **Exploratory Data Analysis (EDA)** project on Diwali festival sales data using Python — uncovering customer purchasing behaviour, top-spending demographics, and high-performing product categories.

---

## 📌 Project Overview

Diwali is one of India's biggest shopping seasons. This project analyzes a Diwali sales dataset to understand **who buys what, from where, and how much** — helping businesses make smarter marketing and inventory decisions for the festive season.

---

## 🎯 Objectives

- Analyze customer demographics (age, gender, marital status, occupation)
- Identify top-spending customer groups
- Discover high-performing product categories
- Understand state-wise and zone-wise sales trends
- Generate actionable business recommendations for festive campaigns

---

## 📂 Project Structure

```
Diwali-Sales-Analysis/
│
├── Diwali_Sales_Analysis.ipynb    # Full EDA notebook
├── Diwali Sales Data.csv          # Raw sales dataset
└── README.md
```

---

## 🗂️ Dataset Description

| Column | Description |
|--------|-------------|
| `User_ID` | Unique customer identifier |
| `Gender` | Customer gender (M/F) |
| `Age Group` | Age bracket of the customer |
| `Marital_Status` | Married (1) or Single (0) |
| `Occupation` | Customer's profession |
| `State` | State of the customer |
| `Zone` | Geographic zone (North, South, East, West) |
| `Product_Category` | Category of the purchased product |
| `Orders` | Number of orders placed |
| `Amount` | Total purchase amount (₹) |

---

## 🛠️ Tools & Libraries

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 🔧 Analysis Workflow

### 1. 🧹 Data Cleaning
- Removed irrelevant and empty columns
- Handled missing values in `Amount` column
- Converted data types for accurate analysis
- Verified dataset shape and structure

### 2. 📊 Exploratory Data Analysis

| Analysis | What Was Explored |
|----------|-------------------|
| 👫 Gender Analysis | Total buyers & spending by gender |
| 🎂 Age Group Analysis | Which age group spends the most |
| 💍 Marital Status Analysis | Spending patterns of married vs single customers |
| 💼 Occupation Analysis | Top-spending professions |
| 🗺️ State-wise Analysis | Top 10 states by orders and revenue |
| 🛒 Product Category Analysis | Best-selling and highest-revenue categories |

### 3. 📈 Visualizations
- Count plots for demographic distributions
- Bar charts for spending by group
- State-wise revenue comparison
- Product category performance charts

---

## 💡 Key Insights

- 👩 **Females** made more purchases and spent more overall than males during Diwali
- 🎂 **Age group 26–35** was the highest-spending segment across all categories
- 💍 **Married customers** showed significantly higher purchase amounts
- 🗺️ **Uttar Pradesh, Maharashtra, and Karnataka** were the top revenue-generating states
- 🛍️ **Food, Clothing & Apparel, and Electronics** were the top 3 product categories by sales
- 💼 Customers from **IT, Healthcare, and Aviation** sectors were the top spenders

---

## 📈 Business Recommendations

- 🎯 Target **married women aged 26–35** in IT/Healthcare/Aviation with personalized campaigns
- 📦 Stock up heavily on **Food, Clothing, and Electronics** before Diwali season
- 🗺️ Focus digital ad spend on **UP, Maharashtra, and Karnataka** for maximum ROI
- 🛒 Offer loyalty rewards to repeat buyers to boost retention during the festive season

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/kartheek-r/Diwali-Sales-Analysis.git
cd Diwali-Sales-Analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook Diwali_Sales_Analysis.ipynb
```

---

## 📚 What I Learned

- End-to-end EDA workflow on real retail data
- Data cleaning and preprocessing with Pandas
- Creating insightful visualizations with Matplotlib & Seaborn
- Translating raw data into business recommendations
- Understanding customer segmentation through demographic analysis

---

## 🙌 Conclusion

This project reveals that **Diwali shopping is dominated by young married women** in the IT/Healthcare sector, primarily purchasing Food, Clothing, and Electronics. These insights can directly guide targeted marketing strategies and inventory planning for businesses ahead of the festive season.

---

## 👨‍💻 Author

**Ryalampadu Kartheek**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartheek-ryalampadu)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kartheekryalampadu@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kartheek-r)
