# Unemployment Analysis in India

This project analyzes unemployment trends in India using Python. The analysis focuses on how unemployment changed before and during the COVID-19 pandemic by exploring national, regional, and urban/rural trends.

The notebook demonstrates a complete data analysis workflow, including data cleaning, visualization, statistical analysis, and drawing meaningful insights.

---

## Dataset

The project uses the **Unemployment in India** dataset (`Unemployment_in_India.csv`).

The dataset includes:
- Unemployment Rate
- Employment
- Labour Participation Rate
- Region (State/UT)
- Area (Rural or Urban)
- Date (May 2019 to June 2020)

---

## What the Notebook Does

The notebook follows these steps:

1. Import the required Python libraries.
2. Load and clean the dataset.
3. Explore unemployment trends over time.
4. Compare unemployment before and during COVID-19.
5. Analyze rural and urban unemployment.
6. Identify the states most affected by the pandemic.
7. Examine seasonal unemployment patterns.
8. Compare unemployment with labour participation rates.
9. Analyze employment trends.
10. Visualize unemployment across regions using a heatmap.
11. Summarize key findings and policy implications.

---

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## Requirements

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn
```

---

## How to Run

1. Download or clone this project.
2. Place `Unemployment_in_India.csv` in the same folder as `Unemployment_Analysis.ipynb`.
3. Open the notebook.

```bash
jupyter notebook Unemployment_Analysis.ipynb
```

4. Run all cells from top to bottom.

---

## Analysis Includes

The notebook explores:

- Overall unemployment trends
- COVID-19's impact on unemployment
- Rural vs Urban comparison
- State-wise unemployment analysis
- Seasonal unemployment patterns
- Labour participation trends
- Employment trends
- Regional unemployment heatmaps

---

## Results

The analysis shows that:

- Unemployment remained relatively stable before COVID-19.
- A sharp increase occurred during the national lockdown in 2020.
- Urban areas experienced a larger increase in unemployment than rural areas.
- Some states were affected much more severely than others.
- Employment declined significantly during the lockdown period.
- Heatmaps and visualizations clearly highlight regional differences and the nationwide impact of the pandemic.

---

## Workflow

```text
Load Data
    ↓
Clean Data
    ↓
Explore Data
    ↓
Visualize Trends
    ↓
Analyze COVID-19 Impact
    ↓
Compare Regions
    ↓
Generate Insights
```

---

## Project Goal

The goal of this project is to demonstrate an end-to-end exploratory data analysis (EDA) workflow using real-world unemployment data. It highlights how data visualization and statistical analysis can be used to understand the economic impact of major events such as the COVID-19 pandemic.
