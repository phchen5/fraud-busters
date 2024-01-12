# 🕵️ Fraud Busters: ML with Imbalanced Datasets

In this project, we'll be building a classification model that aims to detect fraud in credit card transactions. The analysis can be accessed [here](analysis/fraud-busters-ml-with-imbalanced-datasets.ipynb).

**Author**: Po-Hsun (Ben) Chen

## Summary

In this project, I developed a robust classification model to detect credit card fraud, leveraging machine learning techniques. The investigation delved into the complexities of imbalanced datasets, exploring effective strategies to address skewed class distributions and enhance the model's ability to identify fraudulent transactions, offering insights crucial for improving fraud detection systems in financial contexts.

## Data Source

The dataset used in this analysis contains 31 variables, including our target variable: `Class`. This variable takes on two values, `0` as 'Not Fraud' and `1` as 'Fraud'. The remaining variables consist of `Time`, `Amount` and 28 `V` variables. The `V` variables are the results of a PCA (Principal Component Analysis) transformation in order to protect customer information. You can access the dataset [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Dependencies

All required dependencies are listed in this [conda environment file](environment.yaml).

## How to Reproduce the Analysis

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/phchen5/fraud-busters.git
   cd fraud-busters
   ```

2. **Download the Dataset from the Source:**
   You may need to register for a Kaggle account. After you've downloaded the dataset, place the `creditcard.csv` file within a `data/` folder located in the root. You may also place it anywhere else in the repository as you like, just be sure to edit the data source path within the analysis.
3. **Set Up and Activate Environment:**

   ```bash
   conda env create -f environment.yaml
   conda activate fraud-busters
   ```

4. **Open the Notebook:**

   ```bash
   jupyter lab analysis/fraud-busters-ml-with-imbalanced-datasets.ipynb
   ```

5. **Run the Cells and Have Fun Exploring!**

## Files

- `analysis/fraud-busters-ml-with-imbalanced-datasets.ipynb`: Jupyter notebook containing the EDA code.
- `environment.yaml`: Conda environment file listing required dependencies.
