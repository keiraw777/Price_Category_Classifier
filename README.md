# Airbnb Price Category Classifier

A machine learning project that predicts whether an Airbnb listing is **high priced** or **low priced** based on features like accommodations, host info, and location.

## What it does

- Loads and cleans Airbnb listings data (drops unneeded text columns, imputes missing values, one-hot encodes categorical features)
- Trains a **Logistic Regression** model and tunes it with grid search
- Trains a **Neural Network** (Keras) with 3 hidden layers
- Compares both models using Accuracy and F1 Score

## Files

- `SuperhostClassifier.ipynb` — main notebook with all the code
- `airbnbListingsData.csv` — Airbnb listings dataset
- `censusData.csv` — supporting census data

## Installation

1. Make sure you have **Python 3.11.15** installed.
2. In VS Code, create a virtual environment and select it as your Jupyter kernel.
3. Install the required packages:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn tensorflow ipykernel
```

## How to run

1. Open `Price_Category_Classifier.ipynb` in VS Code.
2. Select your venv as the kernel.
3. Run all cells from top to bottom.

## Results

At the end of the notebook, you'll see a side-by-side table comparing the Logistic Regression and Neural Network models on Accuracy and F1 Score.# Price_Category_Classifier_ML
# Price_Category_Classifier
