# Feature Engineering

A collection of Jupyter notebooks covering essential feature engineering techniques for machine learning. This repository is created for learning purposes and anyone can use it to learn feature engineering concepts.

## 📚 Overview

Feature engineering is a crucial step in the machine learning pipeline. This repository provides hands-on examples and implementations of various feature engineering techniques.

## 📖 Topics Covered

### 1. Handling Missing Values
**Notebook:** `1-Handling_Missing_Values.ipynb`

Learn techniques to handle missing data in datasets:
- Understanding missing data mechanisms:
  - Missing Completely at Random (MCAR)
  - Missing at Random (MAR)
  - Missing Not at Random (MNAR)
- Row and column deletion methods
- Imputation techniques:
  - Mean imputation (for normally distributed data)
  - Median imputation (for data with outliers)
  - Mode imputation (for categorical values)
- Practical examples using Titanic dataset

### 2. Handling Imbalanced Datasets
**Notebook:** `2-Handling_Imbalanced_DataSet.ipynb`

Methods to address class imbalance in classification problems:
- Understanding imbalanced datasets and their impact
- Upsampling (increasing minority class datapoints using `sklearn.utils.resample`)
- Downsampling (decreasing majority class datapoints)
- Practical implementation with synthetic datasets

### 3. SMOTE (Synthetic Minority Over-sampling Technique)
**Notebook:** `3-Smote.ipynb`

Learn SMOTE for handling imbalanced datasets:
- Understanding SMOTE technique
- Implementation using `imblearn.over_sampling.SMOTE`
- Creating synthetic samples through interpolation
- Visualizing results with scatter plots

### 4. Handling Outliers
**Notebook:** `4-Handling_Outliers.ipynb`

Techniques for detecting outliers:
- 5 Number Summary (Minimum, Q1, Median, Q3, Maximum)
- Interquartile Range (IQR) calculation
- Lower and upper fence calculation
- Box plot visualization using Seaborn

### 5. Data Encoding
**Notebooks:** `5.1-DataEncoding.ipynb` and `5.2-Target_Guided_OE.ipynb`

Encoding categorical variables into numerical format:
- **One-Hot Encoding (Nominal Encoding)**: Converting categories to binary vectors
- **Label Encoding**: Assigning unique numerical labels to categories
- **Ordinal Encoding**: Encoding categories with intrinsic order/ranking
- **Target Guided Ordinal Encoding**: Encoding based on mean/median of target variable
- Practical examples using custom datasets and tips dataset from Seaborn

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd Feature_Engineering
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open any notebook and start learning!

## 📦 Dependencies

All required dependencies are listed in `requirements.txt`:
- `ipykernel` - Jupyter kernel
- `numpy` - Numerical computing
- `pandas` - Data manipulation
- `matplotlib` - Data visualization
- `seaborn` - Statistical visualization
- `requests` - HTTP library
- `bs4` - Beautiful Soup for web scraping
- `scikit-learn` - Machine learning library
- `imblearn` - Imbalanced-learn for handling imbalanced datasets

## 🎯 Usage

Each notebook is self-contained and can be run independently. The notebooks are organized in a suggested learning sequence:

1. **1-Handling_Missing_Values.ipynb** - Start with missing value treatment
2. **2-Handling_Imbalanced_DataSet.ipynb** - Learn upsampling and downsampling
3. **3-Smote.ipynb** - Understand SMOTE technique
4. **4-Handling_Outliers.ipynb** - Detect outliers using IQR and box plots
5. **5.1-DataEncoding.ipynb** - Encode categorical data
6. **5.2-Target_Guided_OE.ipynb** - Apply target-guided encoding

Feel free to experiment with the code and apply these techniques to your own datasets!

## 🤝 Contributing

This is a learning repository, and contributions are welcome! If you have:
- Improvements to existing notebooks
- Additional feature engineering techniques to add
- Bug fixes or corrections
- Better examples or explanations

Please feel free to open an issue or submit a pull request.

**Happy Learning! 🚀**
