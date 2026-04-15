# Diabetes Prediction using Decision Tree Regressor

This project demonstrates the use of a **Decision Tree Regressor** to predict diabetes progression based on medical features.

---

## Project Overview

The goal of this project is to build a regression model that predicts a quantitative measure of diabetes progression using multiple input features such as:

- Age
- BMI (Body Mass Index)
- Blood pressure
- Serum measurements

Decision Trees are non-linear models that split data into regions based on feature values, making them useful for capturing complex relationships.

---

## What I Learned

Through this project, I practiced:

- Understanding Decision Tree Regression
- Working with structured medical datasets
- Splitting data into training and testing sets
- Training a Decision Tree model
- Making predictions
- Evaluating model performance
- Understanding overfitting in tree-based models

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Files in This Repository

- `Diabetes Prediction Using Decision Tree Regressor.ipynb` → Jupyter Notebook
- `README.md` → Project documentation

---

## Steps Performed

1. Loaded the diabetes dataset from sklearn
2. Converted it into a pandas DataFrame
3. Explored the dataset
4. Split features (X) and target (y)
5. Performed train-test split
6. Trained Decision Tree Regressor model
7. Made predictions on test data
8. Evaluated model using:
   - Mean Squared Error (MSE)
   - R² Score
9. Visualized predictions and model behavior

---

## Model Evaluation Metrics

- **MSE (Mean Squared Error)**: Measures average squared error
- **R² Score**: Measures how well the model explains variance

---

## Why This Project Matters

Decision Trees are powerful models that can capture non-linear relationships and are widely used in real-world ML systems. This project builds a strong foundation before moving to advanced models like Random Forest and Gradient Boosting.

---

## Future Improvements

- Apply pruning to reduce overfitting
- Tune hyperparameters (max_depth, min_samples_split)
- Compare with Random Forest Regressor
- Use cross-validation for better evaluation

---

## Author

Documenting my Machine Learning journey through hands-on projects and real implementations.
