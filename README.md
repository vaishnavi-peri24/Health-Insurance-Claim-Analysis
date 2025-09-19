# Insurance Claim Fraud Detection

This project analyzes and predicts fraudulent insurance claims using a real-world dataset. It includes data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling.

## Project Structure

- `Claim_insurance project`: Main Python analysis and modeling script
- `insurance_claims.csv`: Dataset containing insurance claim records
- `.vscode/settings.json`: VS Code workspace settings

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Synthetic text feature generation for NLP
- Train-test split for model evaluation
- Machine learning pipeline with XGBoost
- Model explainability with SHAP

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- shap

Install dependencies with:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap
```

## Usage

1. Place `insurance_claims.csv` in the project directory.
2. Run the main script:
   ```sh
   python "Claim_insurance project"
   ```
3. Visualizations and model results will be displayed in the output.

## Dataset

The dataset contains columns such as:
- Customer demographics
- Policy details
- Incident and claim information
- Target variable: `fraud_reported` (Y/N)

## License

This project is for educational purposes.