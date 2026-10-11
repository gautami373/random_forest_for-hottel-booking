# random_forest_for-hottel-booking
random forest



# Predictive Classification Using Random Forest Ensembles

## Hotel Booking Cancellation Prediction

### Project Overview
This project uses a Random Forest Classifier to predict whether a hotel booking will be canceled or not. It uses Python and machine learning techniques to analyze hotel booking data.

### Objectives
- Understand and analyze the hotel booking dataset.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and duplicate records.
- Convert categorical data into numerical data.
- Train a Random Forest classification model.
- Evaluate model performance.
- Identify important features affecting booking cancellations.

### Dataset
**Dataset Name:** Hotel Booking Demand Dataset

**File Name:** `hotel_bookings.csv`

**Target Variable:** `is_canceled`

- `0` — Booking not canceled
- `1` — Booking canceled

The dataset must be uploaded before running the notebook.

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

### Project Workflow
1. Import required libraries.
2. Load and inspect the dataset.
3. Remove duplicate records.
4. Handle missing values.
5. Perform exploratory data analysis.
6. Separate input features and target variable.
7. Encode categorical variables.
8. Split data into training and testing sets (80:20).
9. Train the Random Forest Classifier.
10. Evaluate model predictions.
11. Visualize feature importance and the ROC curve.

### Machine Learning Algorithm
**Random Forest Classifier**

The model uses multiple decision trees to classify hotel bookings as canceled or not canceled.

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Score
- ROC Curve

### Project Structure
```text
hotel-booking-random-forest/
│
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── hotel_booking_random_forest.ipynb
└── reports/
    └── project_report.pdf
```

### How to Run the Project
1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload `hotel_bookings.csv`.
4. Run the notebook cells in order.
5. Check the evaluation metrics and visualizations.

### Expected Outcome
The project aims to build a classification model that predicts hotel booking cancellations and identifies features associated with cancellation behavior.

Actual performance results should be added after running the model.

### Limitations
- Model performance depends on the dataset quality.
- Results may vary with different model settings.
- Predictions are based on the available historical booking information.

### Author
**Gautami Balaso Kamble**

Department of Computer Science and Engineering  
Tatyasaheb Kore Institute of Engineering and Technology (TKIET), Warananagar

unlox.com internship training task in AI
