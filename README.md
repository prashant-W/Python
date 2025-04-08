# Household-Specific Poverty Level Prediction Using ML

## 🧠 Project Overview
This project focuses on predicting household-specific poverty levels using machine learning techniques. It is designed to assist policymakers and organizations in targeting assistance more effectively by identifying households most likely to fall below poverty thresholds.

---

## 📊 Objectives
- Predict poverty levels for individual households.
- Use demographic, economic, and infrastructure-related features for prediction.
- Provide interpretable insights for decision-making and targeting of resources.

---

## 🧱 Tech Stack
- **Programming Language**: Python
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: Scikit-learn, XGBoost, LightGBM
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC AUC

---

## 📂 Data Pipeline Overview
1. **Data Collection**: Collect data from census, surveys, or open sources.
2. **Preprocessing**: Handle missing values, encoding categorical data, normalization.
3. **Feature Engineering**: Derive meaningful features like household size, dependency ratio, education level, etc.
4. **Train-Test Split**: Stratified sampling to handle imbalanced data.
5. **Model Training**: Try multiple classifiers (Random Forest, Gradient Boosting, Logistic Regression).
6. **Hyperparameter Tuning**: Use GridSearchCV or Optuna for tuning.
7. **Model Evaluation**: Evaluate using cross-validation and test performance metrics.
8. **Interpretability**: Use SHAP/LIME for understanding feature importance.

---

## 📈 ML Workflow
- **Step 1**: Load and clean dataset
- **Step 2**: Exploratory Data Analysis (EDA)
- **Step 3**: Feature transformation and selection
- **Step 4**: Model building
- **Step 5**: Cross-validation and performance tracking
- **Step 6**: Interpret results and export predictions

---

## 🔍 Feature Examples
- Number of dependents
- Access to clean water
- Literacy level
- Employment status
- Household income
- Number of rooms
- Asset ownership (e.g., vehicles, electronics)

---

## 📌 Key Considerations
- **Imbalanced Classes**: Apply resampling methods (SMOTE, undersampling).
- **Geographical Variance**: Consider adding geospatial encoding.
- **Model Interpretability**: Essential for policy-level decisions.

---

## 📊 Example Output
| Household ID | Predicted Poverty Level | Probability |
|--------------|--------------------------|-------------|
| H001         | Below Poverty Line       | 0.89        |
| H002         | Above Poverty Line       | 0.23        |

---

## 🛠 Future Improvements
- Incorporate real-time data streams.
- Deploy as an API for integration with government platforms.
- Use ensemble models or neural networks for complex patterns.

---

## 🤝 Team Collaboration
This project is part of a collaborative effort, with roles distributed across:
- **Data Collection & Cleaning**
- **ML Modeling & Tuning**
- **Visualization & Dashboarding**
- **Deployment & Integration**

Version control handled via GitHub.

---



