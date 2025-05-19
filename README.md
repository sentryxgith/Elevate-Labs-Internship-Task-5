# Elevate-Labs-Internship-Task-5

# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview

This project explores the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data?select=train.csv) to uncover key patterns and insights about passenger survival. The analysis includes data cleaning, visualization, and interpretation of important features such as gender, class, age, and fare.

---

## Steps Performed

- **Data Loading & Inspection:**  
  Loaded the dataset, checked data types, and identified missing values.
- **Univariate Analysis:**  
  Explored distributions of categorical and numerical variables (e.g., Sex, Pclass, Age, Fare).
- **Bivariate & Multivariate Analysis:**  
  Examined survival rates by gender and class, correlations between features, and relationships between age, fare, and survival.
- **Visualization:**  
  Created bar plots, histograms, boxplots, scatterplots, pairplots, and correlation heatmaps using matplotlib and seaborn.
- **Summary of Findings:**  
  Documented key insights and trends observed in the data.

---

## Key Insights

- **Most passengers are in 3rd class.**
- **Passengers in 1st class had the highest survival rate, while 3rd class had the lowest.**
- **Females had higher survival rates than males.**
- **Younger passengers had higher survival probability.**
- **Passengers with higher fare had better survival odds.**
- **Age and Fare distributions are slightly skewed.**
- **There is a strong negative correlation between passenger class and fare, and a moderate positive correlation between fare and survival.**

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sentryxgith/Elevate-Labs-Internship-Task-5.git
   ```
2. Download `train.csv` from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data?select=train.csv) and place it in the project directory.
3. Open `Titanic_EDA_Task5.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to reproduce the analysis and visualizations.
5. (Optional) Export the notebook as a PDF report.

---

## Files

- `Titanic_EDA_Task5.ipynb` – Jupyter Notebook with all code, charts, and observations
- `Titanic_EDA_Task5.pdf` – PDF report (exported from notebook)
- `README.md` – This documentation

---

## Credits

- **Dataset:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data?select=train.csv)
- **Analysis & Visualizations:** Suraj Rajvanshi
