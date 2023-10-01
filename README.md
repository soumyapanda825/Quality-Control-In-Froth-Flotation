# Iron Purity Prediction Using Machine Learning

This project focuses on predicting the quality of iron ore obtained through the Froth Flotation mineral extraction process, specifically the impurity level, represented as a percentage of silica, in iron ore after purification.

**Exploratory Data Analysis (EDA):** We conducted extensive EDA to understand the dataset's characteristics. The diagram below shows data distributions, correlations, and key insights.

**Machine Learning Models:**

1. **Logistic Regression:** We started with Logistic Regression as a baseline model, achieving an r2 score of 0.5 on the test data.

![image](https://github.com/soumyapanda825/Quality-Control-In-Froth-Flotation/assets/81625214/82044a2b-f55d-409e-84a6-6f5ae751875b)

2. **Random Forest:** To improve accuracy, we implemented Random Forest with hyperparameter tuning. It significantly outperformed Logistic Regression, achieving an r2 score of 0.82 on the test data.

![image](https://github.com/soumyapanda825/Quality-Control-In-Froth-Flotation/assets/81625214/356a4136-75b9-4f3f-8acb-f58e66ec7eaf)

**Model Comparison Table:**

| Model             | r2 Score |
|-------------------|----------|
| Logistic Regression | 0.5      |
| Random Forest       | 0.82     |

The project repository contains code and resources, including the hyperparameter-tuned Random Forest model, for replication and further exploration.

**Conclusion:** This project demonstrates the effectiveness of machine learning in predicting impurity levels in iron ore, vital for quality control in mining. The Random Forest model's high accuracy makes it a valuable tool for the industry.

