# 🏠 House Price Prediction using Artificial Intelligence

## AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

<div align="center">

### 📊 End-to-End Data Analytics + Artificial Intelligence Project

Student:Pandhula Sinduja 
Roll No.:160723733125
Branch:Computer Science and Engineering  
College:Methodist College of Engineering and Technology

</div>

---

## 🌟 Project Overview

This project develops an end-to-end **House Price Prediction** workflow using the Ames Housing / Kaggle **House Prices: Advanced Regression Techniques** dataset.

The solution combines:

- 📥 Data collection and loading
- 🧹 Data-quality analysis
- 🔎 Exploratory Data Analysis
- 🛠️ Missing-value handling
- 🔤 Categorical encoding
- 🤖 Multiple regression models
- 📏 MAE, RMSE, R² and RMSLE evaluation
- 📈 Visual analytics
- 🏠 House-price prediction

### 📌 Dataset at a glance

| Item | Value |
|---|---:|
| Training houses | **1,460** |
| Explanatory variables | **79** |
| Prediction target | **SalePrice** |
| ML task | **Regression** |

![Dataset Scale](assets/dataset_scale.png)

---

## 🎯 Objectives

1. Understand a real-world housing dataset.
2. Detect missing values and data-quality issues.
3. Explore relationships between property features and sale prices.
4. Prepare numerical and categorical features for machine learning.
5. Train multiple regression algorithms.
6. Compare model performance using standard regression metrics.
7. Produce reproducible price predictions and visual insights.

---

## 🔄 Project Workflow

![Project Workflow](assets/workflow.png)

**Data Collection → Data Quality → EDA → Preprocessing → Model Training → Evaluation → Prediction**

---

## 🏗️ System Architecture

![System Architecture](assets/architecture.png)

The architecture separates the project into five logical layers:

| Layer | Main Work |
|---|---|
| Input | House attributes and historical sale prices |
| Analytics | Missing values, distributions and correlations |
| Preprocessing | Imputation, encoding and target transformation |
| Machine Learning | Three regression models |
| Output | Evaluation metrics, visualizations and predicted prices |

---

## 📊 Exploratory Data Analysis

The Jupyter Notebook generates the following data-driven visualizations when executed:

### 1. SalePrice Distribution
Shows the distribution and skewness of house sale prices.

### 2. Missing-Value Analysis
Identifies columns containing missing observations.

### 3. Living Area vs SalePrice
Examines the relationship between `GrLivArea` and `SalePrice`.

### 4. Correlation Heatmap
Highlights relationships among important numerical variables.

> The notebook contains the actual dataset-based graphs and generates them automatically when **Run All** is executed.

---

## 🤖 Machine Learning Models

![Model Portfolio](assets/model_portfolio.png)

The project compares:

### 1. Linear Regression
Used as a simple and interpretable baseline.

### 2. Random Forest Regressor
An ensemble of decision trees capable of modeling nonlinear relationships.

### 3. Gradient Boosting Regressor
Builds trees sequentially to improve prediction performance.

---

## 📏 Evaluation

![Evaluation Metrics](assets/evaluation_metrics.png)

The notebook calculates:

MAE — Mean Absolute Error
RMSE — Root Mean Squared Error
R² — Coefficient of Determination
RMSLE — Root Mean Squared Logarithmic Error

The model comparison table is generated automatically during notebook execution, so performance values are not hard-coded.

---

## 🧹 Data Preprocessing

The project uses an automated Scikit-learn preprocessing pipeline:

```text
Numerical Columns
      ↓
Median Imputation
      ↓
Machine Learning Model

Categorical Columns
      ↓
Most-Frequent Imputation
      ↓
One-Hot Encoding
      ↓
Machine Learning Model
```

The target `SalePrice` is transformed using:

```python
np.log1p(SalePrice)
```

Predictions are converted back with:

```python
np.expm1(prediction)
```

---

## 📈 Expected Notebook Outputs

When the notebook is executed, it creates:

- Dataset preview
- Dataset shape and data types
- Missing-value table
- Missing-value bar chart
- SalePrice histogram
- Living-area vs price scatter plot
- Correlation heatmap
- Model comparison table
- Model comparison chart
- Actual vs predicted price plot
- Feature-importance chart
- Sample prediction table

---

## 💼 Real-World Applications

This type of analytics solution can support:

- 🏠 Preliminary property valuation
- 📊 Real-estate analytics
- 💰 Housing-market research
- 📈 Investment analysis
- 🔍 Property-feature analysis
- 📌 Data-driven decision support

The model is an analytical estimate and should not be treated as a professional property valuation.

---

## ▶️ How to Run

### Step 1 — Install dependencies

```bash
pip install -r requirements.txt
```

### Step 2 — Start Jupyter

```bash
jupyter notebook
```

### Step 3 — Open

```text
House_Price_Prediction_IBM_Internship.ipynb
```

### Step 4 — Run all cells

Use:

Kernel → Restart & Run All

### VS Code

1. Open the project folder in VS Code.
2. Install the Python and Jupyter extensions.
3. Open the `.ipynb` file.
4. Select Python 3 kernel.
5. Run all cells.

---

## 📁 Submission Structure

```text
IBM_House_Price_Prediction_Submission/
│
├── 📓 House_Price_Prediction_IBM_Internship.ipynb
├── 📄 requirements.txt
├── 📘 RamavathChandu_HousePricePrediction_ProjectReport.docx
├── 📖 README.md
│
└── assets/
    ├── workflow.png
    ├── architecture.png
    ├── dataset_scale.png
    ├── model_portfolio.png
    └── evaluation_metrics.png
```

---

## 📚 Dataset Source

Kaggle – House Prices: Advanced Regression Techniques

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

The notebook also includes a public CSV fallback for reproducibility.

---

## 🚀 Future Enhancements

- Hyperparameter tuning
- Cross-validation
- XGBoost / LightGBM / CatBoost comparison
- SHAP explainability
- Streamlit dashboard
- Cloud deployment
- Model monitoring and data-drift detection

---

## 👨‍💻 Student

Pandhula Sinduja
B.Tech – Computer Science and Engineering  
Methodist College of Engineering and Technology  
Roll No.: 160723733125

---

<div align="center">

### ⭐ IBM SkillsBuild Data Analytics with AI Internship 2026

**House Price Prediction | Data Analytics |  Artificial Intelligence
</div>
