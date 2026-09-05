# Repository Structure

The repository is organized as follows:

```text
blue-ridge-digital/
│
├── README.md
│
├── data/
│   │
│   ├── raw/
│   │   ├── accounting/
│   │   │   ├── monthly_income_statement_2023_2025.xlsx
│   │   │   ├── monthly_balance_sheet_2023_2025.xlsx
│   │   │   ├── monthly_cash_flow_statement_2023_2025.xlsx
│   │   │   ├── general_ledger_2023_2025.csv
│   │   │   └── chart_of_accounts.csv
│   │   │
│   │   ├── revenue/
│   │   │   ├── customer_master.csv
│   │   │   ├── monthly_customer_revenue_2023_2025.csv
│   │   │   └── subscriptions_2023_2025.csv
│   │   │
│   │   ├── payroll/
│   │   │   ├── employee_roster.csv
│   │   │   └── monthly_payroll_2023_2025.csv
│   │   │
│   │   ├── operations/
│   │   │   └── monthly_operating_metrics_2023_2025.csv
│   │   │
│   │   └── budget/
│   │       └── 2026_budget.xlsx
│   │
│   ├── processed/
│   │   ├── historical_financials.xlsx
│   │   ├── normalized_income_statement.xlsx
│   │   └── kpi_dataset.csv
│   │
│   └── assumptions/
│       ├── forecast_assumptions.xlsx
│       └── scenario_assumptions.xlsx
│
├── docs/
│   ├── 00_project/
│   ├── 01_architecture/
│   ├── 02_assumptions/
│   ├── 03_methodology/
│   └── 04_model_guide/
│
├── model/
│   └── Blue_Ridge_Digital_Financial_Model.xlsx
│
├── reports/
│   └── Management_Recommendation.pdf
│
└── images/
    ├── executive_dashboard.png
    ├── cash_flow_forecast.png
    └── scenario_analysis.png
```

# Architecture

The architecture of the repository is designed to separate raw data, processed data, and assumptions, while also providing clear documentation and model outputs. The main components are:

- `data/`: Contains all data used in the project, organized into raw, processed, and assumptions subdirectories.
- `docs/`: Contains documentation for the project, including project overview, architecture, assumptions, methodology, and model guide.
- `model/`: Contains the financial model used for analysis.
- `reports/`: Contains client facing outputs, such as generated reports, and business recommendations.
- `images/`: Contains visualizations and images used in the documentation and reports.
- `README.md`: Provides an overview of the repository and its structure.

## Data Directory

The `data/` directory is structured to separate raw data, processed data, and assumptions:

- `raw/`: Contains the original, unprocessed data, organized by category such as accounting, revenue, payroll, operations, and budget.  This simulates the raw data as it would be received from a fictional company.
- `processed/`: Contains data that has been cleaned, transformed, or aggregated for analysis.
- `assumptions/`: Contains forward-looking inputs Northline uses for forecasts/scenarios, such as revenue growth rates, expense projections, and budgetary constraints, typically stored in spreadsheet format (e.g., `.xlsx`).
