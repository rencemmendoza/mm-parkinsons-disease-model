# xgboost-parkinsons-disease-model
Parkinson's Disease Prediction using XGBoost

Overview:
This project uses an XGBoost model to predict Parkinson's disease in patients based on voice features. The model is trained with early stopping on a validation set to prevent overfitting and achieve high predictive performance.

Dataset:
The dataset contains various voice features extracted from patients, including: Pitch, Jitter, Shimmer and Other voice-related metrics.
The target column is status, indicating: 1, where patient has Parkinson's disease, and 0, where patient is healthy.
Only numerical voice features are used for training the model.

Model:
Algorithm: XGBoost Classifier
Training: Includes early stopping on a validation set
Performance: Achieves 95% accuracy

Visualizations:
At the end of the notebook, the model provides visualizations including:
Feature importance and Prediction performance metrics

What I Learned:
How to implement and tune XGBoost, including exploring its key parameters.
Performing train/test splits manually, gaining hands-on experience beyond school assignments.
Using feature importance visualization to understand which features impact predictions most.
Evaluating the model with predicted vs actual visualizations, improving insight into model performance.
