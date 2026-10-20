# World Happiness Report 2019 — Data Analysis & Predictive Modelling

An academic data analytics project exploring the relationships between socioeconomic indicators and happiness scores across 156 countries using Python.

The project combines exploratory data analysis (EDA), statistical visualisation and linear regression to examine factors associated with national happiness scores.

## Project Objectives

- Explore global happiness scores and identify patterns across countries.
- Analyse relationships between happiness scores and socioeconomic indicators.
- Visualise key findings using statistical plots and correlation analysis.
- Develop and evaluate a regression model to predict happiness scores.

## Technologies Used

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualisation:** Matplotlib, Seaborn
- **Machine Learning:** scikit-learn
- **Environment:** Jupyter Notebook

## Dataset

**Source:** [World Happiness Report 2019 — Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness)

The dataset contains records for 156 countries and includes:

- Happiness score
- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption

## Exploratory Data Analysis

The analysis included:

1. **Data Validation:** Checked for missing values and out-of-range values.
2. **Descriptive Statistics:** Examined distributions, averages and variations in happiness scores.
3. **Country Comparisons:** Compared the highest- and lowest-scoring countries.
4. **Correlation Analysis:** Investigated relationships between happiness scores and socioeconomic indicators.
5. **Data Visualisation:** Created histograms, scatterplots, regression plots and a correlation heatmap.

### Key Findings

- GDP per capita, social support and healthy life expectancy showed positive relationships with happiness scores.
- Countries with higher happiness scores generally had higher values for several socioeconomic indicators.
- Social support had the largest positive coefficient among the three predictors in the fitted regression model.

These findings describe associations and do not establish causation.

## Predictive Modelling

A multiple linear regression model was developed using three predictors:

- GDP per capita
- Social support
- Healthy life expectancy

The original coursework used an 80/20 training and testing split and evaluated predictions using mean squared error and R².

### Original Coursework Results

| Evaluation Metric | Result |
|---|---|
| Mean Squared Error (MSE) | 0.4637 |
| R² Score | 0.5545 |

The reported R² indicates that the original model explained approximately 55.45% of the variation in happiness scores within its test dataset.

**Note:** These are the original coursework results. The original preprocessing fitted the scaler before the train-test split; a corrected evaluation should fit preprocessing only on training data and report the updated results.

## Limitations

- The analysis uses data from a single year.
- The model includes only three predictive features.
- The observed relationships do not demonstrate causation.
- Additional socioeconomic and environmental indicators may help explain variation in happiness scores.

## Future Improvements

- Correct the model's preprocessing workflow to prevent data leakage.
- Compare additional regression algorithms.
- Explore more predictive features.
- Use cross-validation to evaluate model stability.

## Project Context

Individual Programming with Data Project
Bachelor of Science (Honours) in Computer Science
University of London
