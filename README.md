# A-TIG-my-master-student-Seyyed-Moein-Fareqi
This repository contains the complete code and workflow used in my latest article, developed and executed in Google Colab
# 📘 WAAM Modeling with XGBoost, Ridge & Uncertainty Quantification

This repository contains the **complete code and workflow** from my latest article, fully executed and validated in **Google Colab**.  
It integrates **data preprocessing, exploratory data analysis (EDA), machine learning (Ridge & XGBoost), hyperparameter optimization, explainability (SHAP), and uncertainty quantification** for WAAM process modeling.

---

## 🔧 Features
- **Preprocessing**: Robust scaling, categorical encoding, and train/validation/test splitting  
- **EDA**: Correlation heatmaps, scatter plots, boxplots, feature–target relationships  
- **Baseline Model**: Ridge regression for benchmarking  
- **Advanced Model**: XGBoost with **Optuna** for hyperparameter optimization  
- **Model Evaluation**: R², RMSE, MAE across splits with publication-ready visualizations  
- **Explainability**: SHAP feature importance analysis  
- **Uncertainty Quantification**: Quantile regression with 90% prediction intervals  
- **Comparison**: Baseline Ridge vs optimized XGBoost  

---

## 📂 Repository Contents
- `kiana_with_uncertainty_final(new visual).py` → Main Colab-compatible script  
- `results.xlsx` → Example dataset (sample input)  
- `baseline_ridge_results.csv` → Baseline Ridge regression performance  
- `xgb_optuna_best_params.csv` → Best hyperparameters (Optuna results)  
- `xgb_final_results.csv` → Final evaluation metrics  
- `model_comparison_metrics.png` → Ridge vs XGBoost comparison figure  
- Additional 📊 **figures and tables** (heatmaps, radar charts, SHAP plots, uncertainty intervals)  

---

## 🚀 Usage

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

2. Install dependencies

The code is Colab-ready, but you can also run locally:

pip install -r requirements.txt


(requirements.txt should include: xgboost, scikit-learn, optuna, shap, pandas, numpy, matplotlib, seaborn, openpyxl, scipy, joblib)

3. Run the notebook/script

Upload the sample dataset (results.xlsx) and execute:

python kiana_with_uncertainty_final(new\ visual).py

4. Outputs

The code generates:

Metrics CSV files (baseline_ridge_results.csv, xgb_final_results.csv, etc.)

High-resolution PNG figures (correlation heatmaps, performance plots, SHAP summaries, uncertainty intervals)

Best hyperparameter sets (xgb_optuna_best_params.csv)

🏆 Results

XGBoost (Optuna-tuned) consistently outperformed Ridge regression across all targets.

Uncertainty quantification provided robust 90% prediction intervals with high coverage.

SHAP analysis revealed the most influential features for each output variable.

📖 Notes

All experiments were double-checked and executed in Google Colab.

Example results are included for easier replication and demonstration.

Users can replace the dataset (results.xlsx) with their own experimental data for custom modeling.

📬 Contact

For questions, suggestions, or collaboration, feel free to open an issue or reach out.
