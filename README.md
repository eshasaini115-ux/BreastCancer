# 🧠 Breast Cancer Classification using Neural Network

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Accuracy](https://img.shields.io/badge/Accuracy-96%25-success)

---

## 📌 Project Overview

This project builds a **Neural Network (NN)** model to classify breast cancer tumors as:

- 🔴 **Malignant (0)** → Cancerous  
- 🟢 **Benign (1)** → Non-cancerous  

The model is trained on the **Breast Cancer Wisconsin Dataset** and achieves high accuracy using deep learning techniques.

---

## 📂 Dataset Details

- 📊 Total Samples: **569**
- 🧬 Features: **30 numerical features**
- 🎯 Target Classes:
  - Malignant (0): 212
  - Benign (1): 357
- ❌ Missing Values: None

---

## ⚙️ Tech Stack

- 🐍 Python  
- 🔢 NumPy  
- 🧾 Pandas  
- 📊 Matplotlib  
- 🤖 Scikit-learn  
- 🧠 TensorFlow / Keras  

---

## 🔄 Workflow

---

## 🧠 Neural Network Architecture

---

## 🔧 Model Configuration

- ⚡ Optimizer: **Adam**
- 📉 Loss Function: **Sparse Categorical Crossentropy**
- 📊 Metrics: **Accuracy**

---

## 📈 Model Performance

| Metric              | Value  |
|--------------------|--------|
| Training Accuracy  | ~97%   |
| Test Accuracy      | ~96%   |

---

## 📊 Visualization

The project includes:
- Accuracy vs Epoch graph  
- Loss vs Epoch graph  

These help analyze:
- Model learning behavior  
- Overfitting/underfitting  

---

## 🔮 Prediction System

The model predicts probabilities for both classes:

```python
prediction = model.predict(input_data)
label = np.argmax(prediction)
git clone https://github.com/your-username/breast-cancer-nn.git
cd breast-cancer-nn

pip install numpy pandas matplotlib scikit-learn tensorflow

python main.py

breast-cancer-nn/
│
├── Breast_Cancer_Classification_with_Neural_Network.ipynb
├── main.py (optional script version)
├── README.md
├── requirements.txt
└── images/
    ├── accuracy.png
    └── loss.png


---
