# 🎵 Music Popularity Prediction (AI/ML Project)

This project focuses on predicting the **popularity of songs** using various musical features such as tempo, energy, danceability, and more. It leverages regression models like **Random Forest Regressor** and **Linear Regression** to forecast popularity scores based on audio metadata.

---

## 📊 Objective

To build a machine learning model that can **predict the popularity of songs** based on their features. This can help music producers, marketers, and platforms make informed decisions about song releases, promotions, and recommendations.

---

## 🧠 Machine Learning Approach

- **Problem Type**: Regression
- **Models Used**:
  - Random Forest Regressor 🌲
  - Linear Regression 📈
- **Evaluation Metrics**:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² Score

---

## 🗃️ Dataset

- **File**: `Spotify_data.csv`
- **Rows**: 227+
- **Columns**: 22 including:
  - Popularity (target)
  - Tempo, Energy, Danceability, Valence, Loudness, etc.
  - Metadata like Track Name, Artist, Album ID, etc.

---

## 🛠️ Steps Involved

1. **Data Loading**: Importing the dataset using Pandas.
2. **Preprocessing**:
   - Cleaning column names
   - Removing irrelevant features (IDs, names)
   - Handling missing values
3. **Exploratory Data Analysis**:
   - Correlation heatmap
   - Feature importance plot
4. **Model Training**:
   - Splitting data into train/test
   - Training and evaluating models
5. **Results**:
   - Random Forest outperformed Linear Regression
   - MAE and R² indicate strong prediction ability

---

## 📈 Feature Importance

Key features affecting popularity:
- Danceability
- Energy
- Loudness
- Tempo
- Valence

---


