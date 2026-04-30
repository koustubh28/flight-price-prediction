# ✈️ Flight Price Prediction

## 📌 Overview

This project focuses on predicting flight ticket prices using machine learning techniques. It involves data cleaning, feature engineering, and building a basic regression model to estimate ticket prices based on various factors.

---

## 🎯 Problem Statement

Predict the price of a flight based on features such as:

* Airline
* Source & Destination
* Duration
* Total Stops
* Date & Time of journey

This is a **regression problem**.

---

## 📊 Dataset

* ~10,000 records
* Cleaned and preprocessed dataset
* No missing values

### Key Features:

* `Total_Stops`
* `Duration_total_min`
* `Arrival_hour`, `Arrival_minute`
* `Departure_hour`, `Departure_minute`
* Encoded Airline, Source, Destination

### Target:

* `Price`

---

## 🧹 Data Preprocessing

* Removed unnecessary columns (`Additional_Info`, `Year`)
* Converted duration to total minutes
* Extracted time-based features (hour, minute)
* One-hot encoded categorical variables

---

## ⚙️ Model Used

### Random Forest Regressor

* Handles non-linear relationships
* Works well with tabular data

---

## 📈 Model Performance

* **R² Score:** ~0.80+
* **RMSE:** ~1800–2200

---

## 📉 Regression Plot Insight

* Predictions align well with actual values
* Model performs best for mid-range prices
* Underestimates high-price flights
* Errors increase for extreme values

---

## 🧠 Key Learnings

* Feature engineering significantly improves performance
* Duration and airline are major price drivers
* Data imbalance affects predictions for high values

---

## 💻 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib

---

## 👨‍💻 Author
Koustubh Muktibodh

## 👨‍💻 Mentor
Krish Naik

---

## ⭐ If you found this useful

Give this repo a star ⭐
