# Project Title: SkyWard Analytics - Flight Delay Prediction

## Overview
SkyWard Analytics is a comprehensive project aimed at predicting flight delays by analyzing transportation data integrated with external environmental factors like weather conditions and bird strikes. The project spans data from 2019 to 2023 and focuses on innovative data integration techniques to enhance predictive accuracy in airline operations.

![Bird Flight](images/Bird_Flight.webp)


## I) Baseline Transportation Data Analysis
### Data Source
- **Transportation Data:** Collected from the Bureau of Transportation Statistics, specifically for the month of September over five years (2019-2023).

### Methodology
1. **Exploratory Data Analysis (EDA):** Conducted detailed EDA to understand underlying patterns and anomalies.
2. **Data Pre-processing:** Cleaned and prepared the data, ensuring it was suitable for modeling.
3. **Feature Engineering:** Extracted and engineered features critical for predicting flight delays.
4. **Model Implementation:** Deployed Logistic Regression, Random Forest, and SVM to establish baseline predictions.
5. **Hyperparameter Tuning:** Optimized models to enhance performance.
6. **Accuracy Evaluation:** Re-assessed model accuracy post-tuning to ensure robustness.

## II) Creative Solution
### Data Integration
- **Additional Data Sets:** Incorporated weather and bird strike data from corresponding sources over the same five-year span.
- **Challenges & Solutions:** Developed and refined merge logic to integrate datasets effectively despite initial obstacles in identifying a suitable merge key.

### Implementation
1. **Data Merging:** Successfully merged transportation data with weather and bird strike data to create a comprehensive dataset.
2. **Repeat Analysis:** Applied the same EDA, preprocessing, feature engineering, modeling, tuning, and evaluation steps to the new combined dataset to assess improvements in predictive accuracy.
