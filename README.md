A comprehensive collection of machine learning projects focused on exploratory data analysis, predictive modeling, and business intelligence. This repository showcases various techniques including regression, classification, and feature engineering.
**Project Overview**
This repository contains five core tasks (4/5 completed) that demonstrate a progression from data visualization to complex predictive systems.

| Task # | Project Title                            | Model Type      | Core Technologies                 | Status |
| **01** | [Exploratory Data Analysis](./Task-01/)  | Visualization   | Pandas, Seaborn, Matplotlib       |  Done  |
| **02** | [Credit Risk Prediction](./Task-02/)     | Classification  | Scikit-Learn, Logistic Regression |  Done  |
| **03** | [Customer Churn Analysis](./Task-03/)    | Classification  | Random Forest, Feature Importance |  Done  |
| **04** | [Insurance Claim Prediction](./Task-04/) | Regression      | Linear Regression, MAE/RMSE       |  Done  |

##  Technical Implementation Details

### Task 1: Iris Dataset Exploratory Analysis
**Goal:** Understanding the fundamental structure of biological data through visualization.

*   **Methodology:** Utilized `pandas` for data inspection (`.shape`, `.head()`) and statistical summarization.
*   **Visualizations:** 
    *   **Scatter Plots:** Observed the clustering of species based on sepal and petal dimensions.
    *   **Histograms:** Visualized the frequency distribution of physical traits.
    *   **Box Plots:** Implemented to identify outliers in features like sepal width.
*   **Tools:** `Python`, `Pandas`, `Matplotlib`, `Seaborn`.


###  Task 2: Credit Risk Prediction
**Goal:** Binary classification to determine loan default probability.

*   **Data Strategy:** Managed missing values and performed feature scaling on income and loan amounts.
*   **Modeling:** Trained a **Logistic Regression** model to classify applicants based on risk factors.
*   **Evaluation:** Used a **Confusion Matrix** to analyze True Positives and Accuracy scores to validate model reliability.
*   **Key Insight:** Visualized how education levels and income brackets directly correlate with loan approval rates.

---

###  Task 3: Customer Churn Prediction (Banking)
**Goal:** Predict customer attrition using behavioral and demographic data.

*   **Pre-processing:** Applied **One-Hot Encoding** for Geography and **Label Encoding** for Gender.
*   **Modeling:** Implemented a Supervised Classification model to identify at-risk customers.
*   **Feature Importance:** Conducted a deep dive to identify that **Age** and **IsActiveMember** status are the primary drivers of churn.
*   **Skills:** Advanced Encoding, Supervised Learning, Model Interpretability.

### Task 4: Medical Insurance Claim Prediction
**Goal:** Predict continuous numerical values (Insurance Charges) using lifestyle data.

*   **Regression Analysis:** Built a **Linear Regression** model to forecast estimated medical charges.
*   **Correlation Study:** Created visualizations demonstrating how **Smoking Status** combined with **BMI** creates a non-linear spike in costs.
*   **Performance Metrics:** Evaluated the model using **MAE** (Mean Absolute Error) and **RMSE** (Root Mean Squared Error).
*   **Skills:** Statistical Regression, Error Evaluation, Multi-variate Visualization.


