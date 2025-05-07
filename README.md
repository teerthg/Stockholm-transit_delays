# 🚍 Predicting Transit Delays in Stockholm

## 👤 Author
**Teerth Gupta**  
Master's Student in Statistics and Data Science  
Uppsala University, Sweden

---

## 📌 Project Overview

This project aims to predict whether a bus or train in Stockholm will be delayed based on factors such as route, stop, weekday, weather, and traffic conditions. It showcases a real-world application of Machine Learning in the context of urban transportation — a highly relevant domain for data science roles in Sweden's public sector and smart city initiatives.

---

## 📁 Dataset Summary

A synthetic dataset of 1,000 transit records with the following features:

| Column         | Description                              |
|----------------|------------------------------------------|
| `route_id`     | Transit route (e.g., B55, T14)           |
| `stop_name`    | Name of stop (e.g., Slussen)             |
| `day_of_week`  | Day of the week                          |
| `temperature`  | Temperature in Celsius                   |
| `precipitation`| Amount of rain/snow                      |
| `traffic_level`| Scale from 1 (low) to 3 (high)           |
| `is_delayed`   | Target: 1 if delayed, 0 if on time       |

---

## 🚀 ML Workflow

1. **Load and Explore Data**  
   Basic checks for missing values, class balance, and data types.

2. **Preprocessing**  
   - One-hot encoding of categorical variables  
   - Removal of missing/extreme values

3. **Train-Test Split**  
   80/20 split using `train_test_split`

4. **Model Training**  
   - `RandomForestClassifier` from `scikit-learn`  
   - Evaluated using `classification_report`

5. **Feature Importance**  
   Visualized to understand key contributors to transit delays

---

## 🧠 Technologies Used

- Python 3.x
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn

---

## 📂 Folder Structure

```
transit-delay-prediction/
│
├── data/
│   └── stockholm_transit_delays.csv
├── notebooks/
│   └── model_and_eda.ipynb
├── README.md
└── requirements.txt
```

---

## 📈 Sample Insight

> "Most delays occurred on route T19 during high traffic hours in rainy conditions."

---

## 💼 Job Relevance

This project aligns with roles in:
- Transport analytics
- Smart city initiatives
- Public sector data science
- Urban mobility optimization

---

## 📝 License

Open for academic and non-commercial use.

## Contact Information
- Name-Teerth Gupta
- LinkedIn-https://www.linkedin.com/in/teerth-gupta-52a248243/
- Email-teerthgupta19@gmail.com
