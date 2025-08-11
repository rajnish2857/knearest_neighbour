# Decision Tree and Random Forest Classification

This Jupyter Notebook (`descisiontree_randonfores.ipynb`) demonstrates classification using Decision Tree and Random Forest algorithms, including model pruning, feature importance, and cross-validation.

## Contents

- **Data Loading & Preprocessing:**  
  Loads `dataset.csv`, removes duplicates, and splits data into features (`X`) and target (`y`).

- **Decision Tree Classifier:**  
  - Trains a basic Decision Tree.
  - Evaluates train and test accuracy.
  - Visualizes the tree.
  - Applies pruning (`max_depth=3`) and re-evaluates accuracy.

- **Random Forest Classifier:**  
  - Trains a Random Forest with 100 trees.
  - Evaluates train and test accuracy.
  - Computes feature importances.

- **Model Evaluation:**  
  - Compares pruned Decision Tree and Random Forest accuracy.
  - Uses `cross_val_score` for 5-fold cross-validation on both models.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Place `dataset.csv` in the project directory.
2. Open and run `descisiontree_randonfores.ipynb` in Jupyter Notebook or VS Code.
3. Follow the notebook cells for step-by-step model training and evaluation.

## Notes

- The notebook demonstrates both overfitting and pruning for Decision Trees.
- Random Forest feature importances are displayed for interpretability.
- Cross-validation provides a robust estimate of model performance.
