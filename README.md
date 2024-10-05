# Diabetes Prediction

This notebook explores the prediction of diabetes using a dataset of medical predictor factors and outcome.

## Data

The dataset used is `diabetes.csv`, which contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 or 1)

## Methodology

1. **Data Loading and Exploration:**
   - The dataset is loaded using pandas.
   - Initial exploration is done using `df.head()`, `df.info()`, and `df.describe()`.
   - The distribution of the `Outcome` variable is checked.
2. **Data Visualization:**
   - Scatter plots are used to visualize the relationship between `Glucose` and `Age`, and `BloodPressure` and `Age`.
3. **Data Cleaning:**
   - Rows with `Glucose` or `BloodPressure` values of 0 are removed.
4. **Model Training:**
   - The data is split into training and testing sets using `train_test_split`.
   - Logistic Regression and Decision Tree Classifier models are trained on the training data.
5. **Model Evaluation:**
   - The accuracy of the models is evaluated using `lr.score` and `cl.score` on the test data.

## Results

Execute the code yourself to see the output and compare the accuracy of the Logistic Regression and Decision Tree Classifier models.
