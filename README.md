# 🚚 Supply Chain Demand Forecasting using Machine Learning

> An end-to-end Machine Learning project that predicts warehouse shipment demand to optimize inventory planning, reduce stock-outs, and improve supply chain efficiency.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-success)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 🚀 Repository Highlights

- End-to-End Machine Learning Pipeline
- Business-Oriented Supply Chain Forecasting
- Feature Engineering
- Data Leakage Prevention
- Multiple Regression Models
- Hyperparameter Tuning
- XGBoost as Final Model
- Actionable Business Recommendations

---

# 📑 Table of Contents

- Project Overview
- Business Problem
- Dataset
- Tech Stack
- Repository Structure
- Workflow
- Exploratory Data Analysis
- Data Preprocessing
- Model Development
- Hyperparameter Tuning
- Model Evaluation
- Results
- Business Insights
- Future Improvements
- Installation
- Usage
- Requirements
- Author
- License

---

# Project Overview

Efficient demand forecasting is critical for minimizing inventory costs while maintaining product availability.

This project develops an end-to-end machine learning solution that predicts warehouse-level shipment demand for an FMCG supply chain. Historical warehouse, logistics, environmental, and operational data were analyzed to build predictive regression models. Multiple algorithms were evaluated, and XGBoost was selected as the final model because it provided the best balance of predictive accuracy, robustness, and generalization.

---

# Business Problem

The company experiences frequent stock-outs in some warehouses and excess inventory in others due to inaccurate shipment planning.

The objective is to predict warehouse-level shipment quantities using machine learning, enabling better inventory allocation, lower logistics costs, and improved operational efficiency.

---

# Dataset

The dataset contains warehouse-level operational information including:

- Warehouse characteristics
- Capacity
- Geographic information
- Retail network
- Transportation issues
- Environmental conditions
- Infrastructure
- Certification
- Historical operational records

**Target Variable**

- Shipment Quantity / Product Weight

---

# Tech Stack

| Category | Tools |
|-----------|-------|
| Language | Python |
| Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistics | SciPy, Statsmodels |
| Machine Learning | Scikit-Learn, XGBoost |

---

# Repository Structure

```text
Supply-Chain-Demand-Forecasting/
├── Dataset/
├── Notebook/
├── Report/
├── Images/
├── README.md
└── requirements.txt
```

---

# Machine Learning Workflow

Business Understanding

↓

Data Understanding

↓

Exploratory Data Analysis

↓

Data Cleaning

↓

Feature Engineering

↓

Data Leakage Prevention

↓

Model Building

↓

Hyperparameter Tuning

↓

Model Evaluation

↓

Model Selection

↓

Business Recommendations

---

# Exploratory Data Analysis

Performed:

- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Correlation Analysis
- Outlier Detection
- Distribution Analysis

Key findings guided feature engineering and model development.

> Add screenshots:
>
> - Correlation Heatmap
> - Distribution Plots

---

# Data Preprocessing

- Missing value treatment
- Duplicate verification
- Data cleaning
- Feature engineering
- Encoding categorical variables
- Feature scaling where applicable
- Data leakage prevention
- Train-test split

---

# Model Development

Baseline Models

- Linear Regression
- Decision Tree Regressor
- KNN Regressor

Advanced Models

- Random Forest
- Gradient Boosting
- XGBoost

---

# Hyperparameter Tuning

Model optimization performed using:

- GridSearchCV
- RandomizedSearchCV

---

# Model Evaluation

Metrics:

- R² Score
- Adjusted R²
- MAE
- MSE
- RMSE

---

# Final Model

✅ XGBoost Regressor

Reasons:

- Highest predictive performance
- Strong generalization
- Captures nonlinear relationships
- Suitable for production-scale forecasting

---

# Business Insights

- Storage issues significantly impact shipment demand.
- Warehouse quality and certification influence operational efficiency.
- Environmental conditions affect warehouse performance.
- Ensemble learning outperformed traditional regression models.

---

# Business Recommendations

- Implement predictive shipment planning.
- Upgrade warehouse infrastructure.
- Improve warehouse maintenance.
- Deploy environmental monitoring systems.
- Integrate forecasting into ERP systems.
- Retrain the model periodically.

---

# Future Improvements

- Deploy using FastAPI
- Build Streamlit Dashboard
- Real-time Forecasting
- Docker
- CI/CD
- MLOps Pipeline
- AWS Deployment

---

# Installation

```bash
git clone https://github.com/your-username/Supply-Chain-Demand-Forecasting.git

cd Supply-Chain-Demand-Forecasting

pip install -r requirements.txt
```

---

# Usage

1. Open the notebook.
2. Run all cells.
3. Train models.
4. Compare results.
5. Review business insights.

---

# Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn
- XGBoost
- Statsmodels

---

# Author

**Akshay Hande**

Data Science | Machine Learning | Artificial Intelligence

- LinkedIn: *(Add your profile)*
- GitHub: *(Add your profile)*

---

# License

This repository is intended for educational and portfolio purposes.

---

# Conclusion

This project demonstrates an end-to-end machine learning workflow for supply chain demand forecasting. By combining business understanding, exploratory data analysis, feature engineering, predictive modeling, and actionable recommendations, the solution provides a scalable framework for improving warehouse shipment planning and inventory optimization.

---

⭐ If you found this repository useful, consider giving it a star.
