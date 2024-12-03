# ensemble-learnings
This project aims to predict driver attrition at Ola using machine learning techniques. The goal is to build a model that can help reduce churn by identifying at-risk drivers. Three machine learning algorithms were applied: XGBoost, Gradient Boosting, and Random Forest. 

Random Forest Model:
The primary goal of this study was to analyze the dataset to predict driver attrition at Ola using ensemble learning techniques. The task aimed to develop a robust predictive model that could help identify drivers at risk of attrition and provide actionable insights to reduce churn, ensuring sustainable operations and enhanced workforce management.
Accuracy: 92.87%
Precision: 97.41% (for class 1)
Recall: 92.05% (for class 1)
F1-score: 94.65%
Train Score: 92.72%
Test Score: 92.87%

Gradient Boosting Model:
The goal of this project was to build a predictive model using the Gradient Boosting Classifier to classify instances into two classes, with a primary focus on maximizing Recall.
Accuracy: 94.55%
Precision: 96.59% (for class 1)
Recall: 95.41% (for class 1)
F1-score: 96.00%
Train Score: 96.71%
Test Score: 94.55%

 XGBoost Model:

 The goal of this case study was to predict driver attrition at Ola using an XGBoost model, with an emphasis on reducing driver churn by leveraging predictive insights.
 
Accuracy: 93.92%
Precision: 96.27% (for class 1)
Recall: 94.80% (for class 1)
F1-score: 95.53%
Train Score: 94.96%
Test Score: 93.92%

Based on the recall metric, let's compare the three models:

XGBoost Model:

Recall: 0.948 (95 out of 100 instances of class 1 are correctly predicted)
Test Score: 93.92%
Gradient Boosting Model:
Recall: 0.954 (95.4 out of 100 instances of class 1 are correctly predicted)
Test Score: 94.55%
Random Forest Model:
Recall: 0.920 (92.0 out of 100 instances of class 1 are correctly predicted)
Test Score: 92.87%

Conclusion:
Since recall is the most important metric, we want a model that maximizes the true positives for class 1 (the target class). Based on recall:
Gradient Boosting Model has the highest recall (0.954) and also performs well on accuracy and precision.
XGBoost Model follows with a recall of 0.948, which is also very good.
Random Forest Model has the lowest recall (0.920), making it less optimal for this use case where recall is critical.
Best Model:
Gradient Boosting Model is the best model based on recall, followed closely by XGBoost.
