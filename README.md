# 🌧️ Rainfall Prediction in Australia 🌦️

This project focuses on predicting whether it will rain tomorrow using various machine learning algorithms based on historical weather data in Australia. The dataset includes various meteorological features, and multiple classification models have been built and evaluated to identify the most accurate predictor of rainfall.

## 🚀 Project Overview

Rainfall prediction is crucial in agriculture, resource management, and everyday planning. In this project, machine learning models are trained using features like temperature, humidity, wind speed, and previous rainfall to predict the likelihood of rain on the following day. The models have been evaluated using several performance metrics to determine the best performing model.

## 📊 Models Implemented

The following machine learning models were applied to predict rainfall:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Support Vector Machine (SVM)**

## 🧮 Evaluation Metrics

Each model has been evaluated based on the following metrics to measure its performance:

- **Accuracy**: Measures how often the model makes correct predictions.
- **Jaccard Index**: Evaluates the overlap between the predicted and actual classes.
- **F1-Score**: The harmonic mean of precision and recall, balancing false positives and false negatives.
- **Log Loss**: (For Logistic Regression only) Measures how well the predicted probabilities align with actual outcomes.

## 📈 Results Summary

| Model               | Accuracy | Jaccard Index | F1-Score | Log Loss  |
|---------------------|----------|---------------|----------|-----------|
| Logistic Regression | 83.66%   | 0.6562        | 0.7828   | 0.3805    |
| KNN                 | 81.83%   | 0.6076        | 0.7397   | N/A       |
| Decision Tree       | 74.96%   | 0.5478        | 0.6951   | N/A       |
| SVM                 | 72.21%   | 0.3611        | 0.4193   | N/A       |

### Key Takeaways:

- **Logistic Regression** performed best across all metrics, making it the most reliable model for predicting rainfall.
- **K-Nearest Neighbors (KNN)** also performed well but slightly lagged behind Logistic Regression.
- **Decision Tree** and **SVM** models had lower performance and may require further tuning to improve their accuracy and generalization.

## 🧠 Insights

- **Data Preprocessing**: The dataset was cleaned, missing values were handled, and categorical features were encoded to be suitable for machine learning models.
- **Feature Engineering**: Additional features like wind direction, temperature, and rainfall history were used to improve prediction accuracy.
- **Model Comparison**: The models were compared using multiple metrics to provide a well-rounded evaluation of their performance.

**Data**: The dataset is sourced from the Australian Bureau of Meteorology, and it's preprocessed within the notebook.

## 🛠️ Tools and Libraries

- **Python**
- **Pandas** for data manipulation and cleaning
- **Scikit-learn** for machine learning algorithms
- **Matplotlib** and **Seaborn** for data visualization
