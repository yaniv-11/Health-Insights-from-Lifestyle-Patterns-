# Health-Insights-from-Lifestyle-Patterns-
Health Insights from Lifestyle Patterns: A Machine Learning and Statistical Study

This project involves a comprehensive statistical and machine learning-based analysis of a health dataset containing 100,000 records and 49 features. The objective is to identify how lifestyle and physiological factors influence health outcomes and derive actionable insights through hypothesis testing, feature importance analysis, and data visualization.

## 📌 Project Overview

- **Dataset Size**: 100,000 rows × 49 features  
- **Target Variable**: `health_status` (1 = healthy, 0 = unhealthy)  
- **Features**: Physiological (e.g., heart rate, BMI, glucose), Lifestyle (e.g., sleep, stress, alcohol, diet)

## 🔍 Goals

- Preprocess and explore the dataset using statistical and visual methods
- Perform hypothesis testing (T-test, Chi-Square) on key variables
- Use machine learning (Random Forest, Logistic Regression) to rank feature importance
- Identify lifestyle habits most correlated with health status
- Visualize findings using Power BI

---

## ⚙️ Technologies Used

- **Python**: Pandas, NumPy, Scikit-learn, SciPy, Seaborn, Matplotlib
- **Statistical Tests**: T-Test, Chi-Square, Logistic Regression
- **ML Model**: Random Forest Classifier
- **Visualization**: Power BI, Correlation Heatmaps, Distribution Plots
- **Tools**: Jupyter Notebook, Git, CSV file operations

---

## 🧪 Key Analysis Steps

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical variables using Label Encoding
- Applied Z-score normalization for feature scaling
- Detected and analyzed outliers using distribution plots

### 2. Feature Importance
- Trained a Random Forest model to evaluate the importance of each feature in predicting health
- Generated a ranked list of contributing factors

### 3. Correlation Analysis
- Created a heatmap to visualize feature relationships
- Analyzed potential multicollinearity and cluster trends

### 4. Hypothesis Testing

| Feature         | Test Used    | P-value | Conclusion                        |
|----------------|--------------|---------|----------------------------------|
| sugar_intake   | T-Test       | 0.8997  | No significant relation          |
| work_hours     | T-Test       | 0.0006  | Significant impact on health     |
| daily_steps    | T-Test       | 0.1263  | No significant relation          |
| smoking_level  | Chi-Square   | 0.6406  | No significant relation          |

### 5. Group-Level Logistic Regression
Grouped factors into:
- Sleep & Stress
- Diet & Physical Activity
- Substance Use (Alcohol + Smoking)

✅ **Significant groups**: Sleep patterns, Stress levels, Physical activity  
❌ **Non-significant**: Substance use in isolation

---

## 📊 Visualizations
Interactive dashboards and charts were developed using **Power BI** to present:
- Feature distributions
- Health trends by demographic or lifestyle habits
- Correlation maps

---

## ✅ Conclusions

- **Work Hours**: Statistically significant correlation with health status  
- **Lifestyle Groups**: Sleep quality, stress, and diet showed stronger predictive power than individual features  
- **Model-Driven Insights**: Random Forest and logistic regression confirmed trends not evident through p-values alone

---

## 📁 Repository Structure

