# Telecom Customer Churn Prediction

This project analyzes customer churn behavior in an Iranian telecom company using classification models. We aimed to predict which customers are likely to churn based on usage data, service types, and demographic features.

## Dataset
- **Source:** [Iranian Churn Dataset - UCI Repository](https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset)
- **Size:** 3,150 rows × 13 features
- **Target:** Churn (`1`) vs. Not Churn (`0`)

## Objectives
- Perform exploratory data analysis (EDA) on telecom usage patterns.
- Build classification models to predict churn.
- Compare model performance using key metrics: accuracy, recall, F1-score.

## Models Used
- K-Nearest Neighbors (KNN)
- Random Forest (RF)

## Key Findings
- Complaints, inactivity, and low usage frequency were strong indicators of churn.
- KNN yielded higher recall, making it preferable for capturing at-risk customers.
- Prepaid customers had a significantly higher churn rate than those on contractual plans.

## Files
- `churn-prediction-notebook.html`: The full data processing and modeling notebook.
- `churn-analysis-report.pdf`: Final report with visualizations, findings, and evaluation.
- `data/`: Original dataset.

## Author
**Thi Ngan Ha Do**  
[GitHub](https://github.com/thinganhado) | [LinkedIn](#)  
