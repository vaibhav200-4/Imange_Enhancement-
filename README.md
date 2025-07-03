# 🖼️ Image Enhancer using CNN Autoencoder (DIV2K)

A deep learning project that enhances low-quality images using a Convolutional Neural Network (CNN) based Autoencoder model trained on the DIV2K high-resolution image dataset.

---

## 📌 Overview

This project builds and trains an image enhancer model using a CNN Autoencoder architecture. The model learns to reconstruct high-quality images from their low-resolution, degraded counterparts. 

While simple autoencoders typically blur details, this project serves as a foundational demonstration of image enhancement workflows using deep learning.

---

## 📊 Features

- 📥 Load and preprocess high-res DIV2K images  
- 🖼️ Simulate low-res images by downsampling and resizing
- 🔍 Train a CNN Autoencoder to reconstruct higher-quality images
- 📈 Visualize original, degraded, and enhanced images side-by-side
- 🌐 Deploy a Gradio-based web interface for live image enhancement

---

## 📚 Tech Stack

- **TensorFlow / Keras**
- **Python 3.x**
- **Gradio** for web deployment
- **DIV2K dataset** for high-res training images
- **NumPy, PIL, Matplotlib** for image preprocessing and visualization

---

## 📦 Project Structure

