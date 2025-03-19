# Sales Forecasting Across Multiple Retail Stores

## 📌 Project Overview
This project aims to build an accurate **Sales Forecasting System** for **Rossmann Pharmaceuticals** using Machine Learning (ML) and Deep Learning techniques. The system predicts future sales for multiple retail stores over a 6-week period.

## 🚀 Key Features
✅ Predicts sales trends using historical data.  
✅ Utilizes both **Random Forest** and **LSTM Models** for enhanced accuracy.  
✅ Web interface for easy prediction and visualization.  
✅ Tracks model performance using **MLFlow**.  

## 📂 Dataset Description
The dataset includes the following key features:
- **Sales:** Daily turnover for stores.  
- **Customers:** Number of visitors per day.  
- **Promo & Promo2:** Indicators for active promotions.  
- **StateHoliday & SchoolHoliday:** Impact of holidays on sales.  
- **StoreType & Assortment:** Store categories and product variety.  
- **Competition Details:** Distance to competitors and promo intervals.  

## 🔎 Data Preprocessing
- Handled missing values and outliers.  
- Extracted key date features (e.g., weekday, month-end).  
- Scaled data using **StandardScaler** for better model convergence.  

## 🧠 Models Used
### **1. Random Forest Regressor**
- Implemented using **Sklearn Pipelines**.  
- Feature Importance analysis improved model insights.  

### **2. LSTM Model (Deep Learning)**
- Designed using **TensorFlow/Keras**.  
- Applied feature scaling with data transformed into supervised format.  
- Enhanced performance with **time-series sliding window technique**.  

## 🌐 Web App Deployment
- Built a user-friendly interface using **Flask** and **Streamlit**.  
- Enables users to:
  - Upload CSV files.  
  - View predicted sales and customer numbers.  
- Integrated **MLFlow** for tracking model versions and metrics.  

## 📊 Results & Insights
- Achieved improved forecasting accuracy by incorporating:
  ✅ **Promo effects**  
  ✅ **Seasonal trends**  
  ✅ **Competitor distance impact**  

## 📋 How to Run the Project
1. **Clone the Repository**  
```bash
git clone https://github.com/your-username/rossmann-sales-forecast.git
cd rossmann-sales-forecast
```

2. **Install Dependencies**  
```bash
pip install -r requirements.txt
```

3. **Run the Flask/Streamlit App**  
```bash
streamlit run app.py
```

4. **Visit the Web App**  
Open your browser and go to `http://localhost:8501`

## 📂 Project Structure
```
|-- data
|   |-- train.csv
|   |-- test.csv
|-- models
|   |-- random_forest_model.pkl
|   |-- lstm_model.h5
|-- notebooks
|   |-- EDA.ipynb
|   |-- Model_Building.ipynb
|-- app.py
|-- requirements.txt
|-- README.md
```

## 🔧 Dependencies
- **Python 3.10**
- **TensorFlow/Keras**
- **Scikit-learn**
- **Pandas, NumPy**
- **Flask/Streamlit**
- **MLFlow**

## 💻 Contributors
- **Yatendra Singh** - [LinkedIn](https://www.linkedin.com/in/yatendrasingh)

## 📄 License
This project is licensed under the **MIT License**.

---
For questions or issues, please raise an issue in the repository or contact [Yatendra Singh](mailto:your.email@example.com).

