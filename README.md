# Data-Analytic-Project
# 🏥 County Health Rankings Data Analysis

This project performs an exploratory data analysis (EDA) on the **County Health Rankings** dataset, which includes health-related metrics at the county level in the United States.

## 📊 Project Goals

- Load and explore the dataset
- Handle missing data
- Understand distributions and correlations
- Visualize key health measures (e.g., Violent Crime Rate)
- Analyze trends over time

## 📁 Dataset

**Filename:** `County_Health_Rankings.csv`  
**Rows:** 303,864  
**Columns:** 14

### Key Columns:
- `State`, `County`: Location identifiers
- `Measure name`: Health metric (e.g., Adult Obesity, Smoking Rate)
- `Raw value`: Main value analyzed
- `Data Release Year`: Year of data availability
- `Numerator`, `Denominator`: Raw components of some measures
- `Confidence Interval`: Lower/Upper bound estimates

> ⚠️ Note: The dataset contains missing values and requires cleaning.

## 🧪 Features of the Analysis

- Summary statistics of each column
- Visualization of missing data
- Top health measures by average raw value
- Trends over years for selected metrics
- Correlation heatmaps for numerical columns
- Export of cleaned dataset

## 📈 Visualizations

- Count of records by year
- Distribution plots of specific health measures
- Time series trend plots
- Correlation heatmaps

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/county-health-analysis.git
   cd county-health-analysis
   Install dependencies (optional via requirements.txt)

2 .install dependencies (optional via requirements.txt)

pip install -r requirements.txt

3.Launch Jupyter Notebook:


✅ Output
Cleaned dataset: Cleaned_County_Health_Rankings.csv

Visual summaries in notebook

Insightful trends and distributions

📌 TODO
Add predictive modeling (e.g., regression)

Cluster counties by health similarity

Interactive dashboard using Plotly or Streamlit
