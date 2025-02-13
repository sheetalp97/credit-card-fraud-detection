# Credit Card Fraud Detection

## Overview

This project implements machine learning models to predict fraudulent credit card transactions. The goal is to identify fraudulent transactions from a dataset containing credit card transaction details. This project was completed as part of the Capstone Project for the Post Graduate Diploma in Data Science (2020).

## Data Description

The dataset contains credit card transactions made by European cardholders over a period of two days in September 2013. Due to confidentiality, the original features have been transformed using Principal Component Analysis (PCA). The dataset includes numerical input variables (`V1` to `V28`), `Time` (seconds elapsed between each transaction and the first transaction), `Amount` (transaction amount), and `Class` (1 for fraudulent, 0 for genuine).

**Important:** The dataset is too large to be directly included in this repository. You can download it from the following Google Drive link:

[**https://drive.google.com/file/d/1SqzYLSnLeyFINyJvtdCsbXVJxejU1Xym/view?usp=sharing**]

## Technologies Used

*   **Python:**
    *   NumPy
    *   Pandas
    *   Matplotlib
    *   Seaborn
    *   Scikit-learn (sklearn)
    *   imblearn (for handling imbalanced data)
    *   XGBoost
*   **Google Colab:** For exploratory data analysis, model building, and experimentation.

## Setup/Installation

1.  **Clone the repository:**

    ```
    git clone https://github.com/sheetalp97/credit_card_fraud_detection
    cd credit-card-fraud-detection
    ```

2.  **Download the Dataset:**

    *   Download the dataset (`creditcard.csv`) from the [**https://drive.google.com/file/d/1SqzYLSnLeyFINyJvtdCsbXVJxejU1Xym/view?usp=sharing**].
    *   Place the `creditcard.csv` file in the same directory as the Colab notebook or upload it to your Google Drive.

3.  **Open in Google Colab:**

    *   Upload the `Credit_Card_Fraud_Detection_Project_Notebook.ipynb` file to your Google Drive.
    *   Open the file with Google Colab (`Open with > Google Colaboratory`).

## Usage

1.  **Open the `Credit_Card_Fraud_Detection_Project_Notebook.ipynb` in Google Colab.**
2.  **Run the cells in the notebook sequentially.** Ensure that you have the necessary libraries installed. Colab typically includes most common data science libraries, but if any are missing, install them using `pip install` within a Colab cell (e.g., `!pip install xgboost imblearn`).
3.  **Data Location:** Modify the notebook to correctly load the data. Update the file paths in the notebook to point to the location of `creditcard.csv`. If you uploaded the file to Google Drive, you'll need to update the path to your CSV file accordingly.

    ```
    # Then, update the path to your CSV file:
    data = pd.read_csv('/content/drive/My Drive/creditcard.csv') # Or wherever you put it
    ```

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.
