# ml

Machine learning practice projects, built in Jupyter notebooks. Each project lives in its own folder and runs top to bottom.

## Projects

### Iris flower classification

`iris-flower-classification/iris_flower_classification.ipynb` — classifies iris flowers into their species from sepal and petal measurements, using the classic iris dataset (loaded from a CSV by the notebook).

### Credit card fraud classification

`creditcard-fraud-classification/creditcard_fraud_classifier.ipynb` — trains a classifier to flag fraudulent credit card transactions. The dataset is not in this repo; that folder's `readme.md` links to the Kaggle download (Credit Card Fraud Detection by MLG-ULB).

## Why this repo exists

I am learning machine learning by building small, complete projects end to end — load the data, train a model, evaluate it — instead of only reading theory. This repo is where those projects live.

## Tech used

- Python
- Jupyter Notebook
- scikit-learn, pandas, seaborn

## Features

- Two complete, self-contained notebook projects: one classification basics, one imbalanced real-world dataset.
- Everything runs locally in a notebook; no servers, no API keys.

## Installation

```bash
git clone https://github.com/pratham-jain33/ml.git
cd ml
pip install jupyter scikit-learn pandas seaborn
```

For the fraud project, also download the dataset from Kaggle (link in `creditcard-fraud-classification/readme.md`) and place it where the notebook expects it.

## How to use

```bash
jupyter notebook
```

Open either project's `.ipynb` file and run the cells from the top. Each notebook loads its data, trains its model, and prints the evaluation at the end.
