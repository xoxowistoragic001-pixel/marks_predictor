# Marks_predictor
Predicts student marks from daily study hours using Simple Regression in Python.

# Study Hours vs Marks Predictor
Predicts a student's marks (out of 100) from daily study hours using Simple Linear Regression in Python.

## Features

- Descriptive statistics of the dataset
- Correlation between hours and marks
- 75/25 train-test split
- Linear Regression model (slope and intercept)
- Evaluation with R2 score and Mean Absolute Error
- Prediction for a new student
- Regression line plot saved as an image

## Requirements

- Python 3
- NumPy
- Pandas
- Matplotlib
- scikit-learn

- pip install numpy pandas matplotlib scikit-learn


## Usage

- python marks_predictor.py

It also runs on Google Colab.

## How It Works

The model learns a straight line:
 (marks = slope * hours + intercept)

The slope shows how many extra marks one more study hour adds on average.

## Output

- Summary statistics and correlation
- Slope, intercept, R2 score and MAE
- Predicted marks for a new student
- `marks_predictor.png` (data points with the regression line)

## Limitations

- Small sample dataset (16 rows), so the test set has only 4 rows and R2 can vary
- Only one feature (study hours) is used

## Author

Muskan Azeem

