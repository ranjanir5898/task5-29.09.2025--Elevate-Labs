# task5-29.09.2025--Elevate-Labs
Exploratory Data Analysis (EDA)
# Titanic Dataset Analysis

This project performs exploratory data analysis (EDA) on the Titanic passenger dataset to uncover factors influencing survival.

## Overview
This project performs exploratory data analysis on Titanic passenger data to uncover insights into survival rates by factors such as sex, passenger class, age, and fare.

## Dataset
Contains 891 passenger records with attributes like Age, Sex, Fare, Pclass, and survival labels.

## Key Steps
- Loaded data and examined structure and missing values.
- Imputed missing Age by median per class; filled missing Embarked and Cabin values.
- Visualized data distributions, survival counts by sex/class, age vs survival, and fare vs age.
- Generated correlation heatmap of numeric features.

## Insights
- Women had higher survival rates.
- First-class passengers and those paying higher fares more likely survived.
- Younger passengers showed better survival odds.
- Strong correlations between class, fare, and survival.

## What I Did

- Loaded and examined the dataset for structure and missing values.
- Cleaned the data by filling missing ages (median by class), embarks (mode), and cabin info (marked unknown).
- Created visualizations including histograms, boxplots, scatterplots, and countplots to explore distributions and relationships.
- Analyzed survival rates by sex, passenger class, age, and fare.
- Generated a correlation heatmap to identify key relationships among numeric variables.
- Summarized findings showing survival is strongly linked to sex, class, age, and fare.

This analysis helps understand the socio-economic and demographic factors that affected survival during the Titanic disaster.

## How to Run

1. Install dependencies: `pip install pandas matplotlib seaborn`
2. Run the Jupyter notebook in this repo to reproduce the analysis.
