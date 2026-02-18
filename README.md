# **Machine Learning Coursework 1**

---

## **Task**
Predict a continuous target variable (`outcome`) from a given dataset, including preprocessing, feature engineering, and model selection, to produce a submission file (CSV) compatible with the test script.

---

## **Approach**
- Cleaned data and removed missing values.  
- Created a `volume` feature and removed highly correlated numeric features.  
- Encoded categorical variables in a way that preserves their significance.  
- Compared **Linear Regression**, **Random Forest**, and **MLP** models using **5-fold cross-validation**.  
- Tuned hyperparameters with **GridSearchCV** and retrained the final model on the full training dataset for submission.

---

## **Challenges**
- Aligning preprocessing between analysis (ordinal encoding) and submission (one-hot encoding).  
- Handling correlated features without losing predictive power.  
- Neural network convergence warnings, requiring consideration of iteration limits.

---

## **Reproducibility**
- Fixed random seeds and consistent preprocessing ensured reproducible results.  
- Final submission model trained on the full dataset and aligned with the evaluation script.
