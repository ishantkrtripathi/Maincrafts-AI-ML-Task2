# Maincrafts-AI-ML-Task2
Task 2: Model Optimization &amp; Comparison
# Model Optimization & Comparison (ML - Task 2)

This repository contains my project submission for **Task 2** of my AI & Machine Learning Internship at **Maincrafts Technology**. Building on top of Task 1, this assignment focuses on data preprocessing (Feature Scaling) and comparing multiple regression algorithms.

## What's New in Task 2?
* **Feature Scaling:** Applied `StandardScaler` to normalize the input features so that no single feature dominates the model due to its scale.
* **Multi-Model Pipeline:** Instead of just one model, I trained and evaluated three different algorithms: Linear Regression, Ridge Regression, and a Decision Tree Regressor.
* **Model Comparison:** Evaluated all models objectively using Root Mean Squared Error (RMSE) and R-squared ($R^2$) Score to choose the best one.

---

## Performance Comparison Matrix

| Model | RMSE | R² Score | Rationale / Behavior |
| :--- | :---: | :---: | :--- |
| **Linear Regression** | ~0.7455 | ~0.5755 | Serves as our baseline model. |
| **Ridge Regression** | ~0.7455 | ~0.5755 | Added L2 regularization, showing stable weights similar to baseline. |
| **Decision Tree** | ~0.7360 | ~0.5860 | Performed slightly better by capturing non-linear splits in data. |

### Key Insight:
The **Decision Tree Regressor** achieved a lower RMSE and a higher R² score compared to the linear models. This proves that housing data has non-linear relationships that straight-line equations cannot fully capture.

---

## Technologies & Tools Used
* Python 3
* Jupyter Notebook / Google Colab
* Scikit-Learn (Pre-processing & Models)
* Pandas & NumPy
* Matplotlib (For Performance Validation Plots)

## Learning Outcomes
This task helped me understand:
1. Why feature scaling is critical before feeding data into ML algorithms.
2. How to train and compare multiple models side-by-side.
3. How to justify model selection using measurable evaluation metrics (RMSE, R²).

## Author
Ishant Kumar  
B.Tech AI & ML Student
