# Customer Segmentation Analysis

## 📌 Overview

This project predicts customer personality using Machine Learning.
It helps businesses like malls and stores to understand customer behavior and segment them accordingly.

---

## ⚙️ Tech Stack

* Python
* Scikit-learn
* Flask / FastAPI
* Docker
* MongoDB

---

## 📊 Models Used

* K-Means (Clustering)
* Logistic Regression (Classification)
* GridSearchCV for Hyperparameter Tuning

---

## 📁 Project Structure

```
src/ → ML pipeline code  
notebooks/ → EDA & training  
templates/ → Frontend UI  
app.py → Main application  
```

---

## 🚀 How to Run

### 1. Clone Repository

```
git clone <your-repo-link>
cd Customer-Personality
```

### 2. Create Environment

```
conda create --prefix venv python=3.10 -y
conda activate venv/
```

### 3. Install Requirements

```
pip install -r requirements.txt
```

### 4. Run Application

```
python app.py
```

### 5. Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🐳 Run with Docker (Optional)

### Build Image

```
docker build -t customer-app .
```

### Run Container

```
docker run -p 5000:5000 customer-app
```

---

## 📈 Features

* End-to-End ML Pipeline
* Customer Segmentation
* Web-based Prediction UI
* Docker Support

---

## 📌 Conclusion

This project demonstrates a complete machine learning workflow from data processing to deployment.
