# PRODIGY_ML_01
'Task 1-Exploratory Data Analysis


# 🏡 House Price Prediction - Exploratory Data Analysis (EDA)
### 📊 Task 1 | Prodigy InfoTech Internship by Safia Alam H B

## 📁 Project Overview
This project focuses on *Exploratory Data Analysis (EDA)* of a house pricing dataset to uncover meaningful patterns and relationships among features that influence house prices.

The goal is to derive insights that would eventually help in building a predictive model for house price estimation.

---

## 🧾 Dataset Summary

- *Source*: Kaggle
- *Rows*: 1460
- *Columns*: 81
- *Target Variable*: SalePrice

### Sample Features:
- LotArea: Size of the lot in square feet
- OverallQual: Overall material and finish quality
- YearBuilt: Year the house was built
- GrLivArea: Above grade (ground) living area
- GarageCars: Size of garage in car capacity

---

## 🔍 Key Analysis Performed

- ✅ *Data Cleaning*: Handled missing values and incorrect data types
- ✅ *Descriptive Statistics*: Summary statistics of numerical and categorical features
- ✅ *Correlation Analysis*: Heatmap and Pearson correlation matrix
- ✅ *Univariate Analysis*: Distribution plots of key features like SalePrice, GrLivArea, etc.
- ✅ *Bivariate Analysis*: Relationship between SalePrice and features like OverallQual, YearBuilt, etc.
- ✅ *Outlier Detection*: Identified and visualized outliers using boxplots
- ✅ *Feature Insights*:
  - OverallQual and GrLivArea are highly correlated with price
  - Newer homes and homes with better quality materials have higher sale prices

---

## 📊 Key Insights

- *Overall Quality* of the house is one of the strongest indicators of price.
- *Garage area* and *living area* also show strong correlation with the price.
- *Year Built* plays a role, with newer homes tending to be more expensive.
- *Outliers* in large living areas with lower prices were detected and noted for cleaning.

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Jupyter Notebook

---

## 🧠 Conclusion

The EDA helped us understand the structure and hidden relationships in the data. These insights will directly inform how we prepare the data and select features for training future predictive models.

---

## 🚀 How to Run

1. Clone this repository
2. Open the notebook Task 1 - EDA on House Prices.ipynb
3. Run each cell to explore the dataset and insights
