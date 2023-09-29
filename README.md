# Crime Data Analysis and Prediction

## Team 16
- Veenadharini Shukla - NUID: 002704948
- Diya Baldota - NUID: 002747966

## Datasource
- [Download Dataset](https://www.kaggle.com/datasets/chaitanyakck/crime-data-from-2020-to-present?resource=download)

## Introduction

### Background
Crime rates in cities like Los Angeles have been steadily rising, posing a threat to public safety and straining law enforcement resources. Traditional reactive policing methods have limitations in preventing future crimes. To address this, data-driven approaches, including machine learning, are being used to analyze past crime data for proactive prevention.

### Motivation
Our project aims to contribute to creating safer communities in Los Angeles by using data analysis and machine learning to understand crime patterns and identify factors contributing to crime. We believe that data-driven insights can enhance law enforcement strategies and improve public safety.

### Aim
1. **Analyzing the LA Crime Dataset:** We will explore crime patterns in Los Angeles, examining crime types, distribution across time, and geographical areas.
2. **Identifying Factors Contributing to Crime:** We will analyze socio-economic, demographic, and environmental factors correlated with crime rates.
3. **Predicting Likelihood of Crimes:** Machine learning models will estimate the likelihood of specific crimes occurring in different areas.
4. **Time Series Analysis:** We will use time series analysis to predict crime trends over time.

## Methodology

### Data Acquisition and Pre-Processing
- Downloaded LA Crime dataset from Kaggle, merged two CSV files into one.
- Explored dataset's structure, data types, and meanings of attributes.
- Cleaned data by handling missing values, removing duplicates, and standardizing data types and formats.

### Exploratory Data Analysis
1. **Crime Occurred by Day of the Week:** Visualized crime counts by day of the week.
2. **Crime Occurred over the Years:** Plotted crime trends over the years.
3. **Types of Crimes Committed:** Displayed the top 20 crime types by count.
4. **Gun-Related Crimes over the Years:** Analyzed trends in gun-related crimes.
5. **Top 20 Crime Occurrences by Premises:** Explored crime occurrences in the top 20 premises.
6. **Word Cloud of Weapon Descriptions:** Visualized frequent terms in weapon descriptions.
7. **Victim Sex Distribution:** Created a pie chart of victim gender distribution.
8. **Age Distribution by Top 20 Crimes:** Examined age distribution for the top 20 crime types.
9. **Heat Map for Area Wise Distribution:** Visualized crime density on a Folium map.

### Feature Engineering
- Performed feature engineering, including creating a 'Time Slot' column for time-based analysis.

### Model Selection
- Evaluated four models: Logistic Regression, Random Forest Classifier, Decision Tree Classifier, and Gaussian Naive Bayes.
- Logistic Regression had the highest accuracy score of 0.972.

### Time Series Analysis
- Utilized Prophet and ARIMA models to predict crime trends over time.

## Description of the Dataset
The dataset contains crime data from 2010 to 2019 and from 2020 to the present. It includes attributes like DR Number, Date Occurred, Crime Type, Victim Information, Location, and more.

## Conclusion
Our project analyzed LA crime data, identified factors contributing to crime, predicted crime likelihood, and conducted time series analysis. Logistic Regression was the best-performing model. Our work contributes to enhancing public safety in Los Angeles.

## References
- [Kaggle Crime Dataset](https://www.kaggle.com/datasets/chaitanyakck/crime-data-from-2020-to-present?resource=download)
- [Data Source](https://data.lacity.org/d/63jg-8b9z/visualization)
- [GitHub Repository](https://github.com/SlicerBX/crime-data-analysis-and-prediction-in-LA/blob/main/Crime_Prediction_and_Classification_in_LA_Master.ipynb)
- [ARIMA Time Series Forecasting](https://www.researchgate.net/publication/224346385_Forecasting_crime_using_the_ARIMA_model)
