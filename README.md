# Image Classification with CNNs and MLPs

This repository contains Machine Learning pipelines for multi-class image classification tasks using Convolutional Neural Networks (CNN) and Multi-Layer Perceptrons (MLP). 

## 📌 Project Overview
The goal of this project is to build, train, and evaluate neural networks on standard computer vision datasets. It also includes a custom preprocessing pipeline to test the trained models on real-world, hand-drawn, or internet-sourced images.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Image Processing:** OpenCV (cv2)
* **Data Visualisation:** Matplotlib, Seaborn

## 📊 Results
* **MNIST (Handwritten Digits):** Custom MLP architecture achieved **97.39% accuracy** on the test set. Successfully classified custom hand-drawn images.
* **Fashion-MNIST (Clothing Items):** MLP achieved **88.77% accuracy**.
* **CIFAR-10 (RGB Objects):** CNN architecture (with Convolutional, MaxPooling, and Dropout layers to prevent overfitting) achieved **73.65% accuracy**.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook in the `notebooks/` directory to see the training process and custom image predictions.
