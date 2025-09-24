# 📱 Mobile Phone Price Prediction using Machine Learning  

## 📌 Overview  
The **Mobile Phone Price Prediction System** is a machine learning-based project that predicts the price range of a mobile phone based on its specifications such as RAM, battery power, processor speed, camera quality, and other features.  

This project helps both customers and sellers to understand the pricing strategy and make smarter decisions when buying or selling smartphones.  

---

## ⚙️ Features  
- Predicts mobile phone price range (e.g., low, medium, high, very high).  
- Handles raw data preprocessing and feature engineering.  
- Compares multiple ML models for best accuracy.  
- Provides clear data visualization for insights.  
- Can be deployed using **Flask/Streamlit** for interactive prediction.  

---

## 📊 Dataset  
- **Source**: Kaggle Mobile Price Classification dataset.  
- **Attributes (Sample):**  
  - Battery Power (mAh)  
  - RAM (MB)  
  - Internal Storage  
  - Processor Speed (GHz)  
  - Primary & Secondary Camera (MP)  
  - Screen Resolution & Pixel Density  
  - 4G/3G/WiFi Support  
  - Price Range (Target Variable: 0 = Low, 1 = Medium, 2 = High, 3 = Very High)  

---

## 🛠 Tech Stack  
- **Programming Language**: Python 🐍  
- **Libraries/Frameworks**:  
  - Data Processing → Pandas, NumPy  
  - Visualization → Matplotlib, Seaborn  
  - Machine Learning → Scikit-learn  
  - Model Deployment → Flask / Streamlit  
- **Version Control**: Git & GitHub  

---

## 🔎 Machine Learning Models Used  
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- Gradient Boosting / XGBoost  

The best-performing model is selected based on evaluation metrics like **Accuracy, Precision, Recall, and F1-Score**.  

---

## 🚀 Installation & Usage  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/yourusername/mobile-price-prediction.git
cd mobile-price-prediction
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook (for training & testing)  
```bash
jupyter notebook Mobile_Price_Prediction.ipynb
```

### 4️⃣ Run Web Application  
If deployed using **Flask**:  
```bash
python app.py
```
Visit: `http://127.0.0.1:5000/`  

If deployed using **Streamlit**:  
```bash
streamlit run app.py
```

---

## 📈 Results  
- Achieved **Accuracy ~ 85–90%** (depending on dataset & features).  
- Random Forest and Gradient Boosting provided the best classification results.  

---

## 📌 Future Enhancements  
- Add deep learning models for better predictions.  
- Build a mobile-friendly prediction app.  
- Include real-time smartphone data from APIs/web scraping.  
- Add Explainable AI (XAI) to interpret predictions.  

---

## 🤝 Contributing  
Contributions are welcome! Feel free to open an **issue** or submit a **pull request**.  

---

## 📜 License  
This project is licensed under the **MIT License** – free to use and modify.  

---

## 👨‍💻 Author  
Developed by **[Your Name]**  
- 🌐 GitHub: [yourusername](https://github.com/yourusername)  
- 🔗 LinkedIn: [yourprofile](https://linkedin.com/in/yourprofile)  
