# 📊 Sales Prediction — Advertising Analysis & Linear Regression

A data science project focused on predicting sales revenue based on advertising expenditure across different media channels. This project utilizes Simple Linear Regression to quantify the relationship between marketing budgets and total sales.

---

## 📋 Dataset

The project uses the **Advertising Dataset** (commonly found in ISLR). It tracks the budget allocated to different media and the resulting sales.

| Column | Description |
|---|---|
| **TV** | Advertising budget spent on TV (in thousands of dollars) |
| **Radio** | Advertising budget spent on Radio |
| **Newspaper** | Advertising budget spent on Newspaper |
| **Sales** | Target variable representing sales of the product (in thousands of units) |

---

## 🔧 Workflow & Methodology

1.  **Data Inspection** — Understanding data dimensions, types, and summary statistics.
2.  **Data Cleaning** — Checking for null values and ensuring data integrity.
3.  **Exploratory Data Analysis (EDA)** — 
    * Outlier detection using Boxplots.
    * Visualizing the target variable distribution.
    * Analyzing correlations between features (TV, Radio, Newspaper) and Sales.
4.  **Feature Selection** — Identifying the most impactful predictor (TV) for the Simple Linear Regression model.
5.  **Model Building** — Splitting data into training and testing sets (70/30) and training the regression model.
6.  **Model Evaluation** — Assessing performance using R-squared and residual analysis.

---

## 🛠️ Tech Stack

- **Python 3**
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone [https://github.com/soumimukherjee22/Sales-Prediction-Python.git](https://github.com/soumimukherjee22/Sales-Prediction-Python.git)
cd Sales-Prediction-Python

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

# Launch the notebook
jupyter notebook Sales_Prediction.ipynb

## 👩‍💻 Author

**Soumi Mukherjee** — Data Analyst

[![Email](https://img.shields.io/badge/Email-soumi.mukherjee2003%40gmail.com-red?style=flat&logo=gmail)](mailto:soumi.mukherjee2003@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-soumimukherjeeofficial-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/soumimukherjeeofficial/)
[![GitHub](https://img.shields.io/badge/GitHub-soumimukherjee22-black?style=flat&logo=github)](https://github.com/soumimukherjee22)
