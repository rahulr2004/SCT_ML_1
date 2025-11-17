# SCT_ML_1
SkillCraft ML Task 01 — House Price Prediction (Linear Regression)

## Author
Rahul R — GitHub: @rahulr2004

## Dataset
Kaggle: House Prices - Advanced Regression Techniques  
Link: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Files in this repo
- `SCT_ML_Task1.ipynb` — Google Colab notebook (full pipeline)
- `predictions_lr.csv` — Actual vs Predicted (Linear Regression)
- `actual_vs_predicted_lr.png` — Evaluation plot
- `linear_reg_model_lr.joblib` — Trained Linear Regression model
- `linear_reg_model_log.joblib` — (Optional) model trained on log(target)
- `random_forest_model.joblib` — (Optional) Random Forest model
- `README.md` — this file

## How to run (Google Colab)
1. Open `SCT_ML_Task1.ipynb` in Colab.
2. Upload your `kaggle.json` when prompted (Kaggle API token).
3. Run cells in order (Runtime → Run all).
4. Download `predictions_lr.csv` and `actual_vs_predicted_lr.png` for submission.

## Notes
- Features used: `sqft` = GrLivArea, `bedrooms` = BedroomAbvGr, `bathrooms` = FullBath + 0.5*HalfBath.
- Optional improvements: feature engineering, log-transform of target, regularized regression, tree-based models.
