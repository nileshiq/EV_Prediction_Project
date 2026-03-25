# EV Prediction Project 🚗⚡

## 📌 Project Overview
The EV Prediction Project focuses on analyzing an Electric Vehicle dataset to build machine learning models that can predict vehicle energy efficiency ratings and key performance attributes. The goal is to leverage data-driven techniques to understand EV performance trends, pricing patterns, and efficiency factors that influence consumer and industry decisions.

## 🎯 Objectives
- Analyze EV specifications such as range, acceleration, battery efficiency, charging speed, and price.
- Perform data preprocessing and feature engineering to prepare structured data for modeling.
- Build and evaluate machine learning models for:
  - Energy efficiency classification
  - Price and range prediction (regression)
- Generate actionable insights for EV market segmentation and performance optimization.

## 📊 Dataset Description
The dataset contains technical and performance specifications of multiple electric vehicles, including:
- Brand and vehicle segment
- Battery efficiency (Wh/Km)
- Fast charging speed (Km/H)
- Range (Km)
- Acceleration (0–100 km/h)
- Top speed
- Seating capacity
- Price (Euro)
- Energy efficiency rating (target variable)

## ⚙️ Project Workflow
1. **Data Collection & Understanding**
   - Imported dataset and analyzed structure, data types, and distribution.
2. **Data Cleaning & Preprocessing**
   - Handled categorical encoding and feature formatting.
   - Converted object columns into numerical formats.
   - Checked for missing values and outliers.
3. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between range, efficiency, and price.
   - Identified trends across vehicle segments and brands.
4. **Feature Engineering**
   - Created derived metrics such as price-per-range ratio.
   - Selected relevant features for modeling.
5. **Model Building**
   - Implemented classification models (Random Forest, Logistic Regression) to predict energy rating.
   - Implemented regression models to estimate EV price and performance metrics.
6. **Model Evaluation**
   - Used accuracy, confusion matrix, MAE, RMSE, and R² score.
7. **Insights & Interpretation**
   - Identified key factors affecting EV efficiency and cost.
   - Highlighted performance clusters within the EV market.

## 🤖 Machine Learning Techniques Used
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting (optional enhancement)
- Linear Regression for numerical prediction

## 📈 Results
The models successfully predicted EV energy efficiency categories and key numerical attributes with reliable performance. Feature importance analysis revealed that battery efficiency, range, and charging speed are major contributors to overall vehicle performance.

## 🚀 Future Improvements
- Hyperparameter tuning and cross-validation
- Deployment using Flask / Streamlit
- Real-time EV recommendation system
- Integration with larger real-world datasets

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📚 Conclusion
This project demonstrates how machine learning can be applied to electric vehicle analytics to support intelligent predictions and strategic insights. It highlights the growing importance of data science in sustainable transportation and smart mobility solutions.
