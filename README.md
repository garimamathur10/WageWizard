# WageWizard 💼💵

**Predict your expected salary as a fresh graduate or early-career professional!**  
WageWizard leverages machine learning to estimate salaries based on education, experience, and role, providing **personalized insights and career guidance**.

_______________________________________________________________________________________________________________________________________________________________

## Overview
- End-to-end ML pipeline: **EDA → Preprocessing → Modeling → Deployment**  
- Interactive, **Streamlit-ready** tool for real-time salary predictions  
- Accurate salary predictions using **Random Forest Regressor** (R² = 0.98)

_______________________________________________________________________________________________________________________________________________________________

## Business Problem
Graduates and early-career professionals often face:  
- Unclear salary expectations  
- Anxiety about the job market  
- Lack of personalized guidance  

**WageWizard solves this by providing:**  
- Realistic salary ranges based on real-world data  
- Data-driven advice for profile improvement  
- An interactive tool to support career decisions

_______________________________________________________________________________________________________________________________________________________________

## Key Features
- **Supervised Regression Model**: Random Forest Regressor (R² = 0.98)  
- End-to-end pipeline from **EDA → Modeling → Deployment**  
- Streamlit-ready for **interactive salary predictions**  
- Provides **personalized insights** and recommendations

_______________________________________________________________________________________________________________________________________________________________

## How It Works
1. **Data Preparation**  
   - Dataset from Kaggle, cleaned and preprocessed  
   - Missing values handled, categorical features encoded, numerical features scaled  

2. **Exploratory Data Analysis (EDA)**  
   - Identified key salary drivers: experience, education, role  

3. **Model Building**  
   - Tested Linear Regression, XGBoost, and Random Forest  
   - Random Forest chosen for best performance (**R² = 0.98, MAE ≈ $2,880**)  

4. **Deployment**  
   - Model and preprocessor exported as `.pkl` files  
   - Ready for **integration with Streamlit** for interactive predictions
