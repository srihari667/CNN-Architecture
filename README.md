# 📘 CNN Architecture – DS-AG-021

This repository contains solutions for the **CNN Architecture (Code: DS-AG-021)**.
It covers theoretical explanations and practical implementations using **TensorFlow/Keras** and **PyTorch**, as required in the assignment PDF.

---

## 📄 **Assignment Overview**

The assignment includes:

### ✅ **Theory Questions**

1. Role of filters & feature maps in CNNs
2. Padding & stride
3. Receptive field
4. Effect of filter size & stride on parameters
5. Comparison of LeNet, AlexNet & VGG

### 🧪 **Practical Tasks**

6. Build & train a CNN on **MNIST** (Keras)
7. Preprocess CIFAR-10 & build CNN (Keras)
8. Train CNN on MNIST using **PyTorch**
9. Use **ImageDataGenerator** for custom dataset classification
10. Build & deploy a **Chest X-Ray classifier** (Normal vs Pneumonia) + **Streamlit Web App**

---


## 🧰 **Technologies Used**

* **Python 3**
* **TensorFlow / Keras**
* **PyTorch**
* **NumPy, Pandas, Matplotlib**
* **Streamlit**
* **ImageDataGenerator**
* **Colab GPU**


---

## 🩻 **Chest X-Ray Classification (Normal vs Pneumonia)**

The final task includes:

### **✔ Data Preparation**

* Loading original Chest X-Ray dataset
* Applying augmentation
* Cleaning & normalizing pixel values

### **✔ CNN Model Training**

* Binary image classification
* Early stopping + learning-rate scheduling
* Performance metrics (accuracy, AUC, confusion matrix)

### **✔ Deployment via Streamlit**

```
streamlit run app/app.py
```

The app allows users to **upload an X-Ray image** and get **real-time predictions**.

---

## 📊 **Results**

* Achieved high accuracy on MNIST & CIFAR datasets
* Successfully trained a binary classifier for Pneumonia detection
* Built a working Streamlit web application

---

