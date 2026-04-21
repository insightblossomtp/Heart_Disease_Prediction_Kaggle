❤️ Heart Disease Prediction — Learning ML End-to-End

📌 Project Context

This project was built as part of my journey into machine learning, with the goal of understanding how to go from raw data to a complete ML pipeline.

Instead of focusing only on model performance, the emphasis was on:

* Learning core ML concepts through implementation
* Understanding model behavior (overfitting, generalization)
* Applying proper evaluation techniques used in real-world problems

⸻

🎯 Objective

Predict the probability of heart disease.

* Problem type: Binary Classification
* Evaluation metric: ROC-AUC

⸻

🧠 What I Learned

This project reflects a progression from basic understanding to structured ML thinking:

1. Data Preparation

* Splitting data using stratified sampling
* Handling categorical vs numerical features
* Avoiding data leakage

2. Feature Engineering & Transformation

* One-Hot Encoding for categorical variables
* Feature scaling for numerical variables
* Using ColumnTransformer to build reusable preprocessing pipelines

3. Model Building

* Implemented Logistic Regression as a baseline model
* Compared with Random Forest to understand model complexity

4. Model Evaluation

* Learned why accuracy is not enough
* Used:
    * ROC-AUC 
    * Precision, Recall, F1-score
    * Confusion Matrix

5. Understanding Overfitting

* Observed Random Forest overfitting 
* Understood why simpler models can generalize better if there exists a linear relationship

6. Kaggle Workflow

* Generated predictions on unseen test data
* Created submission file using predicted probabilities
* Understood public vs private leaderboard evaluation

⸻

Kaggle Submission

* Public Score: 0.95089
* Private Score: 0.95254
