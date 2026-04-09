# 🌱 Crop Disease Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 🚀 Project Overview
This project focuses on detecting crop diseases from leaf images using deep learning techniques. The model is designed to help farmers identify plant diseases early and reduce crop loss, contributing to smarter agriculture.
💡 This model can assist farmers in early disease detection, reducing crop loss and improving yield.

---

## 🎯 Objective
To build an accurate and reliable image classification model that can identify diseases in crops using Convolutional Neural Networks (CNNs) and Transfer Learning.

---

## 📊 Dataset
- Total Images: 11,000+
- Classes:
  - Cashew
  - Cassava
  - Maize
  - Tomato

The dataset consists of real-world agricultural images of plant leaves categorized into different disease classes.

---

## 🧠 Model Architecture
- Base Model: VGG16 (Transfer Learning)
- Layers Used:
  - Convolutional Layers (Pre-trained)
  - Global Average Pooling
  - Dense Layer (512 units, ReLU)
  - Dropout (0.5)
  - Output Layer (Softmax)

---

## ⚙️ Techniques Used
- Data Preprocessing & Normalization
- Data Augmentation (Flip, Rotation, Zoom, Contrast)
- Class Weight Balancing
- Transfer Learning (VGG16)
- Model Checkpointing & Early Stopping
- Mixed Precision Training

---

## 📈 Performance
- Training Accuracy: ~98%
- Validation Accuracy: ~97.9%
- Test Accuracy: ~97.9%

The model shows strong generalization across unseen data.

---

## 📊 Evaluation Metrics
- Confusion Matrix
- Precision, Recall, F1-Score
- Classification Report

---

## 🔍 Explainable AI
Grad-CAM (Gradient-weighted Class Activation Mapping) is used to visualize which parts of the image the model focuses on while making predictions, improving transparency and trust.

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Google Colab

---

## 📸 Sample Outputs
![image alt](https://github.com/gowsikapr/Deep-Learning-Project/blob/b130adbd5a9cd64136e258ba5554432c6465a751/Screenshot%202026-04-09%20161237.png)

---

## 🔗 Project Link
[View Notebook](https://github.com/gowsikapr/Deep-Learning-Project/blob/main/Finalminiproject.ipynb)

---

## 🌾 Real-World Impact
This solution can help farmers detect plant diseases early, reduce crop damage, and improve agricultural productivity using AI-driven insights.

---

## 📌 Future Improvements
- Add more crop classes
- Deploy as a web/mobile application
- Integrate real-time disease detection
- Improve accuracy with larger datasets

---

## 🤝 Connect
I am actively seeking opportunities in AI / Machine Learning / Data Science.  
Feel free to connect and collaborate!
