# District-Level Prediction of Child Stunting and Wasting in India

## Overview
Child malnutrition remains a critical public health challenge in India. This project utilizes machine learning and meta-heuristic optimization techniques to predict the district-level prevalence of child stunting (chronic undernutrition) and wasting (acute undernutrition) using data from the National Family Health Survey (NFHS-5).

## Data & Methodology
* **Dataset:** NFHS-5 (2019-20) District Fact Sheet covering 706 districts and 109 indicators.
* **Feature Selection:** Pearson correlation analysis and LASSO regression.
* **Models Deployed:** Linear Regression, Random Forest XGBoost and SVR,
* **Optimization:** Particle Swarm Optimization (PSO) for hyperparameter tuning.

## Key Findings
* **Wasting Predictability:** Short-term nutritional deprivation (wasting) was predicted with higher accuracy (R² ~ 0.78) compared to stunting (R² ~ 0.63).
* **Important Predictors:** Maternal nutrition (BMI and anaemia), sanitation, women's education, and child anaemia emerged as the most significant predictors. 
* **Model Performance:** While ensemble models achieved high training accuracy, Linear Regression proved highly stable, and PSO provided consistent improvements in generalization.

## Repository Contents
* `codes_nfhs5.ipynb` - Source code for data preprocessing, feature selection, and model training.
* `report.pdf` - Full project report detailing the theoretical framework, EDA, and policy implications.
