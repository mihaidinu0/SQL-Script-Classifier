![Header](assets/header.png)

## Scope
This project is a simple classifier for SQL queries that classifies them into 2 categories: `clean` or `malicious`. 

## Live Demo
A live, user-friendly demo of the project will be available soon, at: https://sql-classifier.mihaidinu.com

## Data
The entire dataset contains 20,000 queries. The dataset is split into 3 parts: `train`, `test` and `validation`. The `train` and `validation` sets contain 10.000 queries each.
- __Train__ has 45.288 entries
- __Validation__ has 5.661 entries
- __Test__ has 5.661 entries

## Model
I have used a random forest classifier with 100 estimators. The model has an accuracy of 99.5% on the validation set.

## How to run
1. Clone the repository
2. Open in VS Code
3. Install Jupyter extension
4. Open `sql-classifier.ipynb`
5. Set the kernel version to `Python 3.9.13 64-bit` (other versions might work as well, this is the one I used)
6. Run all cells

