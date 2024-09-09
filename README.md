# Bayesian Sports Analysis

## Overview
This project aims to build a Bayesian inference model to predict player performance in baseball using historical data. The goal is to forecast metrics such as batting averages for the upcoming season. The project includes an ETL pipeline for data processing, a Bayesian model for prediction, and a simple dashboard for visualization.

### Features
- ETL Pipeline: Load and preprocess historical baseball data.
- Bayesian Model: Predict player performance using a Bayesian inference approach.
- Dashboard: Visualize model predictions and allow user interaction.

## Project Structure
```
Bayesian-Sports-Analysis/
├── data/            # Raw and processed datasets
├── notebooks/       # Jupyter notebooks for model development
├── src/             # Python scripts for ETL and modeling
├── dashboard/       # Dashboard code for visualization
├── README.md        # Project documentation
├── requirements.txt # Dependencies
└── .gitignore       # Files to ignore
```

## Instructions

1. Setup the Environment
Clone the repo and install dependencies:
git clone https://github.com/tredavis/Bayesian-Sports-Analysis.git
cd Bayesian-Sports-Analysis
pip install -r requirements.txt

2. Data Preprocessing (ETL Pipeline)
The data preprocessing is done in src/etl_pipeline.py. This step involves loading, cleaning, and processing the dataset for modeling.

Run the ETL pipeline:
python src/etl_pipeline.py

3. Model Development
We use a Bayesian regression model to predict player performance. You can find the model development in src/model.py.

4. Dashboard
The dashboard is built using Dash/Streamlit to visualize predictions.

## Dataset
The dataset used is the Lahman Baseball Database, which contains historical player performance data and player demographics.

## Future Work
- Implement more features for the dashboard (e.g., advanced filtering).
- Explore other Bayesian models for different player metrics.

## License
MIT License