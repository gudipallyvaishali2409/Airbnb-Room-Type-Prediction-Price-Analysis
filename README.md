# 🏨 Airbnb Room Type Prediction & Price Analysis

## 📌 Project Overview

This project focuses on analyzing Airbnb open dataset and building Machine Learning models to predict room types based on different listing features such as pricing, reviews, availability, and neighborhood information.

The project includes data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, visualization, and machine learning model development using Python.

---

## 🎯 Objectives

* Analyze Airbnb listing trends and pricing patterns
* Perform data cleaning and preprocessing
* Visualize important insights from the dataset
* Build machine learning models for room type prediction
* Improve model performance using tuning and balancing techniques

---

## 📂 Dataset

* Airbnb Open Dataset
* Dataset contains:

  * Room Types
  * Pricing Information
  * Number of Reviews
  * Availability
  * Neighborhood Details
  * Host Information
  * Booking Details

---

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)
* Joblib

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection

* Loaded dataset using Pandas
* Explored dataset structure and statistics

### 2️⃣ Data Cleaning

* Removed duplicate values
* Handled missing values
* Renamed columns for consistency
* Dropped irrelevant columns

### 3️⃣ Exploratory Data Analysis (EDA)

Performed:

* Distribution analysis
* Box plots
* Histograms
* Scatter plots
* Pair plots
* Pie charts
* Confusion matrix visualization

### 4️⃣ Feature Engineering

Created additional features such as:

* Total Cost
* Minimum Nights & Reviews Interaction
* Price Buckets

### 5️⃣ Categorical Encoding

Used Label Encoding for:

* Room Type
* Neighborhood Group
* Instant Bookable
* Host Verification Status

### 6️⃣ Machine Learning Models

Implemented:

* Random Forest Classifier
* XGBoost Classifier
* Voting Classifier Ensemble

### 7️⃣ Hyperparameter Tuning

Used:

* RandomizedSearchCV
* Cross Validation

### 8️⃣ Handling Imbalanced Data

Applied:

* SMOTE (Synthetic Minority Oversampling Technique)
* Class Weight Balancing

### 9️⃣ Model Evaluation

Evaluated models using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation Accuracy

---

## 📊 Results

* Achieved approximately **82% Cross Validation Accuracy**
* Identified important factors affecting room type prediction
* Generated meaningful business insights using data visualization

---

## 📈 Important Visualizations

* Room Type Distribution
* Price Distribution
* Feature Importance Graph
* Confusion Matrix
* Price vs Reviews Scatter Plot
* Neighborhood Price Analysis

---

## 💾 Model Saving

The trained machine learning model was saved using Joblib:

```python
joblib.dump(best_model, "airbnb_model.pkl")
```

---

## 📁 Project Files

* Airbnb Analysis Notebook (`.ipynb`)
* Trained Model (`airbnb_model.pkl`)
* Dataset
* Visualizations
* README File

---

## 🚀 Future Improvements

* Deploy model using Streamlit or Flask
* Improve model accuracy
* Add interactive dashboard
* Integrate real-time Airbnb data

---

## 📚 Key Learnings

Through this project, I improved my understanding of:

* Data Cleaning
* Exploratory Data Analysis
* Machine Learning
* Feature Engineering
* Model Optimization
* Data Visualization
* Handling Imbalanced Datasets

---

## 👩‍💻 Author

Gudipally Vaishali
