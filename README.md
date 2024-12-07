# Cost-Sharing-Analysis-and-MOOP-Exclusion-Prediction

## Team Members
- **Shubham Manoj Gengaje:** Data Preprocessing, Model Development
- **Sunil Kumar Madara:** Visualization, Feature Engineering, Dashboard Development

## Overview
This project aims to address key challenges in healthcare cost transparency by analyzing cost-sharing structures and predicting Maximum Out-of-Pocket (MOOP) exclusions. Using machine learning, we provide insights to help patients select better healthcare plans and policymakers design fairer systems.

## Objectives
- **Cost-Sharing Analysis:** Evaluate how copayments and coinsurance differ across providers and service types.
- **MOOP Exclusion Prediction:** Use machine learning to predict factors influencing MOOP exclusions.

## Dataset
- **Size:** 1M+ rows, ~450 MB
- **Key Variables:**
  - Cost-sharing (e.g., `CopayInnTier1`, `CoinsOutofNet`)
  - Service details (e.g., `BenefitName`, `QuantLimitOnSvc`)
  - Exclusion indicators (e.g., `IsExclFromInnMOOP`, `IsExclFromOonMOOP`)

## Key Results
### Machine Learning Models:
- **Random Forest Regressor:** R² = 0.965, MSE = 98.13
- **Gradient Boosting Regressor:** R² = 0.94, MSE = 167.73

### MOOP Exclusion Prediction:
- **Accuracy:** 85% (Random Forest), **AUC:** 0.99
- **Key Predictors:** `LimitQty`, `IsEHB_Yes`

## Visualizations
- Cost-sharing trends across services
- Feature importance charts for MOOP prediction
- Model performance evaluation (e.g., learning curves, ROC curves)

## Recommendations
- **Patients:** Select plans with minimal MOOP exclusions and extensive in-network coverage.
- **Policymakers:** 
  - Standardize cost disclosures.
  - Cap out-of-network emergency costs.
  - Use predictive insights for equitable structures.

## References
- Centers for Medicare & Medicaid Services
- Kaiser Family Foundation
- Breiman, L. (2001). "Random Forests"

_For more details, view the full project report._
