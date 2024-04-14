In both scenarios, you've applied different models to the same dataset, one with SMOTE and one without. Let's compare the performances of each model between the two scenarios:

**Logistic Regression:**
- Without SMOTE:
  - Accuracy: 0.9417
  - ROC AUC Score: 0.5000
- With SMOTE:
  - Accuracy: 0.4267
  - ROC AUC Score: 0.5613

**SVM (RBF Kernel):**
- Without SMOTE:
  - Accuracy: 0.9417
  - ROC AUC Score: 0.5000
- With SMOTE:
  - Accuracy: 0.5135
  - ROC AUC Score: 0.6680

**Random Forest:**
- Without SMOTE:
  - Accuracy: 0.9710
  - ROC AUC Score: 0.7509
- With SMOTE:
  - Accuracy: 0.9961
  - ROC AUC Score: 0.9871

**Gradient Boosting:**
- Without SMOTE:
  - Accuracy: 0.9925
  - ROC AUC Score: 0.9360
- With SMOTE:
  - Accuracy: 0.9108
  - ROC AUC Score: 0.8752

**K-Nearest Neighbors:**
- Without SMOTE:
  - Accuracy: 0.9433
  - ROC AUC Score: 0.5366
- With SMOTE:
  - Accuracy: 0.8310
  - ROC AUC Score: 0.9101

Comparing the performances between the two scenarios, it seems that Random Forest and Gradient Boosting models perform consistently well in both cases, with Random Forest showing slightly better performance in terms of accuracy and ROC AUC score. 

In summary, Random Forest appears to be the most robust model for this dataset, showing high accuracy and ROC AUC score regardless of whether SMOTE is applied or not.
