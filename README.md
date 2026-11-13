# Exploratory Data Analysis (EDA) & Data Cleaning

## Project Objective
This project performs end-to-end data profiling, missing value imputation, duplicate removal, IQR outlier treatment, and exploratory data analysis (EDA) using Python, Pandas, Matplotlib, and Seaborn. The objective is to transform a noisy real-world dataset into a clean, analysis-ready dataset and extract visual insights.

## Repository Structure
```text
├── .gitignore                   # Ignores Jupyter checkpoints and temporary files
├── README.md                    # Project documentation and setup instructions
├── data/
│   ├── raw_dataset.csv          # Original uncleaned dataset (with missing values & duplicates)
│   └── cleaned_dataset.csv      # Cleaned and preprocessed dataset
├── notebooks/
│   └── eda_and_cleaning.ipynb   # Executed Jupyter Notebook with code, markdown notes, and charts
└── docs/
    └── summary_report.pdf       # Executive summary of methodology, key findings, and challenges
```

## Dataset Overview
- **Source:** Breast Cancer Wisconsin Diagnostic Dataset (`scikit-learn` / UCI Machine Learning Repository), prepared with realistic data quality anomalies (missing entries and duplicate rows) for end-to-end cleaning validation.
- **Dimensions:** 584 rows × 12 features (raw) → 569 unique rows × 12 features (cleaned).

## How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd eda-data-cleaning-project
   ```
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Launch Jupyter Notebook and open `notebooks/eda_and_cleaning.ipynb`:
   ```bash
   jupyter notebook
   ```
4. Run all cells sequentially (`Kernel -> Restart & Run All`) to reproduce the cleaning pipeline, charts, and `data/cleaned_dataset.csv`.
