# 🍅 Tomato Leaf Disease Detection using CNN

## 📌 Project Description

This project uses a Convolutional Neural Network (CNN) built with PyTorch to classify tomato leaf images into three categories.

## 🏷️ Classes

* Healthy
* Early Blight
* Late Blight

## 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* CNN
* Google Colab
* Matplotlib

## 🔄 Project Workflow

```text
Tomato Leaf Image
       ↓
Image Preprocessing
       ↓
CNN Model
       ↓
Feature Extraction
       ↓
Classification
       ↓
Healthy / Early Blight / Late Blight
```

## 🧠 CNN Architecture

```text
Input Image (128 × 128 × 3)
        ↓
Conv2D (3 → 16)
        ↓
MaxPooling
        ↓
Conv2D (16 → 32)
        ↓
MaxPooling
        ↓
Flatten
        ↓
Fully Connected Layer
        ↓
3 Classes
```

## 📊 Model Accuracy

The model achieved approximately **86% training accuracy** during the initial experiment.

> Note: This accuracy was measured on the training dataset. A separate validation/test evaluation should be used for a reliable final performance measurement.

## 🚀 Future Improvements

* Add more tomato disease classes
* Add data augmentation
* Use train/validation/test split
* Improve model accuracy
* Deploy the model as a web application

## 📁 Project Files

```text
Tomato-Leaf-Disease-Detection-CNN/
│
├── Tomato_Disease_Detection.ipynb
└── README.md
```
