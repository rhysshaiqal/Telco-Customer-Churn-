# Telco Customer Churn Analysis

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on a customer churn dataset from a telecommunications company. The goal is to identify key factors that contribute to customer churn and provide actionable insights for improving customer retention.

## Dataset
- **Source:** Kaggle ([Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn))
- **Records:** 7,043 customers
- **Features:** Customer demographics, service usage, billing information, and churn status.

## Key Findings
1. **Contract Type:** Customers with month-to-month contracts churn the most.
2. **Monthly Charges:** Higher charges are correlated with increased churn.
3. **Tenure Impact:** Customers with shorter tenure are more likely to churn.
4. **Billing & Payment:** Electronic check payments show higher churn rates.

## Files in Repository
- `telco.ipynb` - Jupyter Notebook with the full analysis and visualizations.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` - The dataset used in the analysis.
- `README.md` - Project documentation (this file).

## Requirements
To run this project, install the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

## Running the Analysis
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd telco-churn-analysis
   ```
3. Open and run `telco.ipynb` in Jupyter Notebook or VS Code.

## Next Steps
- Develop a **predictive model** for churn classification.
- Implement **customer retention strategies** based on insights.

## Contributing
Feel free to fork this repository, make improvements, and submit a pull request!

## License
This project is licensed under the MIT License.

