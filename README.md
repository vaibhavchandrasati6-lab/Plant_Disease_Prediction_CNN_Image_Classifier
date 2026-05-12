# 🌱 Plant Disease Detection Using CNN

## 📌 Project Overview

This project is a Deep Learning-based Plant Disease Detection System built using a Convolutional Neural Network (CNN). The model is trained on the PlantVillage dataset to classify plant leaf images into multiple disease categories.

The project uses image preprocessing, data augmentation, and CNN architecture to identify diseases from plant leaf images with high accuracy.

---

# 🚀 Features

* Image classification using CNN
* Multi-class plant disease prediction
* Data preprocessing and normalization
* Model training and validation
* Accuracy and loss visualization
* Dataset handling using ImageDataGenerator

---

# 📂 Dataset

Dataset used:

* PlantVillage Dataset from Kaggle

Dataset contains:

* 38 classes
* Healthy and diseased plant leaves
* Thousands of plant leaf images

Kaggle Dataset:

[https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)

---

# 📊 Data Preprocessing

The following preprocessing steps were applied:

* Image resizing to 224×224
* Pixel normalization using rescale=1./255
* Train-validation split
* Batch processing using ImageDataGenerator

---

# 🏗️ CNN Architecture

The CNN model includes:

* Conv2D layers
* MaxPooling2D layers
* Flatten layer
* Dense layers
* ReLU activation
* Softmax output layer

Optimizer Used:

* Adam

Loss Function:

* categorical_crossentropy

---

# 📷 Sample Workflow

1. Load Dataset
2. Preprocess Images
3. Create Data Generators
4. Build CNN Model
5. Train Model
6. Evaluate Performance
7. Visualize Accuracy & Loss

---


# 📸 Project Output

The model predicts plant diseases from leaf images and visualizes:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss

---

# 💡 Learning Outcomes

This project helped in understanding:

* Convolutional Neural Networks (CNN)
* Image Classification
* Deep Learning Workflow
* Data Augmentation
* Model Evaluation
* TensorFlow/Keras

---

# 📌 Future Improvements

* Use Transfer Learning (EfficientNet/ResNet)
* Deploy using Streamlit
* Add real-time image upload
* Improve accuracy with data augmentation
* Add Grad-CAM visualization
