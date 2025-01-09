# KUET Bitfest Datathon 2025: 7th Place Solution 🎉

This repository contains the Jupyter Notebook that secured **7th place** in the **KUET Bitfest Datathon 2025**. The notebook showcases an end-to-end approach for solving the competition's problem, which involved data preprocessing, exploratory analysis, feature engineering, and predictive modeling.

## Key Steps in the Notebook

### 1. **Setup and Libraries**
   - Installed essential libraries like `pandas`, `numpy`, `seaborn`, `matplotlib`, and `scikit-learn`.
   - Imported necessary modules for data manipulation, visualization, and machine learning.

### 2. **Data Loading**
   - Loaded competition datasets:
     - **Training data:** Used for model training.
     - **Test data:** Used for predictions and final evaluation.
   - Previewed and understood the datasets with functions like `info()` and `head()`.

### 3. **Exploratory Data Analysis (EDA)**
   - Analyzed the structure of the datasets.
   - Visualized relationships and distributions using `seaborn` and `matplotlib`.

### 4. **Feature Engineering**
   - Processed categorical and textual columns such as `skills_required`.
   - Used techniques like encoding and data cleaning to enhance model performance.

### 5. **Model Development**
   - Split the training data into training and validation sets using `train_test_split`.
   - Built predictive models using algorithms like:
     - Random Forest Regressor, Light-GBM
   - Tuned hyperparameters to improve accuracy and reduce overfitting.

### 6. **Evaluation and Results**
   - Validated model performance on a held-out dataset.
   - Generated predictions for the test data.
   - Submitted results, achieving **7th place in the leaderboard**.
