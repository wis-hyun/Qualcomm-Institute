# Used Car Price Prediction – Qualcomm Institute 2025

**Team 2 – Qualcomm Overseas Research Program**  
**Project Title: Development of a Machine Learning-based Prediction Model for Used Car Listing Prices in Germany**

---

## Overview

This repository documents our team’s research and project conducted during the 2025 Qualcomm Institute Overseas Training Program.  
We focused on developing a machine learning-based model to predict the listing prices of used cars in Germany, aiming to support fair pricing and reduce information asymmetry between sellers, buyers, and dealers.

---

## Research Summary

### Problem Statement

The used car market in Germany exhibits significant information asymmetry. Sellers often list prices based on subjective criteria, and buyers lack reliable references for fair valuation. Our project aimed to build a predictive model using real market data to propose reasonable listing prices.

### Dataset & Preprocessing

- **Data Source**: Used car listings from the German automotive market.
- **Preprocessing Steps**:
  - Removed missing values and outliers.
  - Applied feature encoding (One-hot, Label Encoding, etc.).
  - Used feature importance analysis to select key predictors.

### Machine Learning Models

We tested two primary models:

1. **Multiple Linear Regression (MLR)**  
   - Pros: High interpretability  
   - Cons: Performed poorly for high-priced cars due to linearity assumptions  

2. **Random Forest (RF)**  
   - Pros: Captures nonlinear relationships and variable interactions  
   - Performed better than MLR, especially for luxury/high-priced vehicles  
   - Used k-fold cross-validation for generalization

### Results

- MLR showed good performance for low-to-mid priced vehicles but was less accurate for luxury car predictions.
- RF delivered consistently lower RMSE and was more robust for all price ranges.
- Final conclusion: The Random Forest model showed stronger potential for real-world application.

---

## Project Process Summary

### Program Details

- **Duration**: Jan 8 – Feb 16, 2025  
- **Location**: Qualcomm HQ (San Diego) & UCSD  
- **Tools**: KNIME (for data science workflows), Python (for research comparison)  
- **Purpose**: Combine AI learning with practical team-based model development

### Timeline

- **Week 1**: Team formation, topic selection  
- **Weeks 2–5**: Data processing, modeling with KNIME, weekly presentations  
- **Week 6**: Final presentation (hackathon-style competition)

### Project Highlights

- Conducted a full-cycle ML project using KNIME’s GUI-based tools  
- Iteratively improved models with expert feedback  
- Performed feature engineering and comparative modeling  
- Delivered high RMSE performance improvements with Random Forest

---

## Repository

Visit the project repository:  
👉 [https://github.com/wis-hyun/Qualcomm-Institute](https://github.com/wis-hyun/Qualcomm-Institute)

---

## License

This project is released under the MIT License.
