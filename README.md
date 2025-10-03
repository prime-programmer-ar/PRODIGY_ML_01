# Prodigy InfoTech ML Internship - Task 01
# By: Zain Qamar

## House Price Prediction Model

### Project Overview

This project builds a linear regression model to predict house sale prices based on key features like living area, bedrooms, and bathrooms. It fulfills **Task 01** of the Prodigy InfoTec Machine Learning Internship.

---

### Workflow

1.  **Data Preparation:** The script loads the `train.csv` dataset, handles missing values in bathroom-related columns, and engineers a combined `TotalBath` feature.

2.  **Model Training:** It selects `GrLivArea`, `BedroomAbvGr`, and `TotalBath` as features, splits the data (80% train, 20% test), and trains a Scikit-learn Linear Regression model.

3.  **Evaluation:** The model's performance on the test set is evaluated using Mean Absolute Error (MAE) and R-squared (R²) metrics.

4.  **Visualization:** A scatter plot is generated to visually compare the model's predicted prices against the actual sale prices.

---

### Performance Results

*   **Mean Absolute Error (MAE):** `$34,395.80`
*   **R-squared (R²):** `0.6579`

This shows the model explains about 65.8% of the price variance, with an average prediction error of around $34k.



### How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/prime-programmer-ar/PRODIGY_ML_01
    cd your-repo
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Prepare the dataset:**
    *   Ensure the `train.csv` file is located at `dataset/train.csv`.

4.  **Execute the script:**
    ```bash
    python your_script_name.py
    ```
---

### Libraries Used
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn