# Unemployment Analysis with Python

## Project Overview
This project analyzes unemployment trends in India using Python. It explores unemployment rates across different regions and areas, examines trends over time, and investigates changes during the COVID-19 period.

## Objectives
- Analyze unemployment rates across different regions in India.
- Compare unemployment rates between Rural and Urban areas.
- Visualize unemployment trends over time.
- Investigate changes in unemployment during the COVID-19 period.
- Identify monthly patterns and relationships between employment indicators.

## Dataset
The project uses the **Unemployment in India** dataset.

The dataset contains the following columns:
- `Region`
- `Date`
- `Frequency`
- `Estimated Unemployment Rate (%)`
- `Estimated Employed`
- `Estimated Labour Participation Rate (%)`
- `Area`

After cleaning, the dataset contains 740 rows.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Data Understanding
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. COVID-19 Impact Analysis
6. Data Visualization
7. Interpretation of Results

## Data Cleaning
- Cleaned column names by removing extra whitespace.
- Handled missing numerical values using median imputation.
- Removed rows with missing categorical information.
- Converted the `Date` column into datetime format.
- Extracted `Year` and `Month` features.
- Created a `COVID_Period` feature to distinguish Pre-COVID and COVID-period observations.

## Exploratory Data Analysis
The project includes:
- Unemployment rate distribution histogram.
- Rural vs Urban unemployment boxplot.
- Average unemployment rate by area.
- Regional unemployment analysis.
- Unemployment trends over time.
- Monthly unemployment patterns.
- Regional and monthly unemployment heatmap.
- Correlation analysis of unemployment, employment and labour participation.

## COVID-19 Impact Analysis
The dataset was divided into two periods:
- **Pre-COVID:** Before March 2020
- **COVID Period:** March 2020 onward

The average unemployment rate was:
- Pre-COVID: 9.51%
- COVID Period: 17.77%
- Difference: 8.26 percentage points
- Relative increase: 86.86%

These results describe the difference observed in the dataset and do not independently establish causation.

## Key Findings
- The unemployment-rate distribution is right-skewed, with a small number of high-value observations.
- The average unemployment rate is higher in Urban areas than in Rural areas in this dataset.
- Average unemployment rates vary across regions.
- A sharp increase in unemployment is visible during April and May 2020.
- The unemployment rate declined in the subsequent months shown in the dataset.
- The correlation between estimated unemployment rate and estimated employed is weakly negative.

## Project Structure
```text
CodeAlpha_Unemployment_Analysis/
├── data/
│   ├── Unemployment in India.csv
│   └── unemployment_cleaned.csv
├── notebook/
│   └── Unemployment_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Conclusion
This project explores unemployment trends in India using data analysis and visualization techniques. It identifies regional and area-wise differences, examines changes over time, and highlights the increase in unemployment observed during the COVID-19 period.

## Author
**Muiz Takey**  
BE Computer Engineering (AI & ML)