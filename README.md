# CNN-Gesture-Detection 🖐️  
A real-time gesture detection system built with convolutional neural networks (CNNs) that recognises hand gestures and enables touchless interaction.

## 🔍 Project Overview  
This system uses live webcam input to detect and classify hand gestures. It builds encodings of hand pose and trains a CNN model to recognise a set of predefined gestures. Once recognised, gestures can be mapped to commands (e.g., swipe left/right, play/pause), making it ideal for applications like touchless UI control, presentations, or accessibility solutions.

## ✨ Key Features  
- Real‐time gesture detection from webcam feed  
- Gesture recognition without physical contact — useful for hygiene, accessibility and hands-free control  
- Simple interface to visualise webcam feed and show detected gesture labels  
- Easy to extend: add new gestures, map gestures to custom commands

## 🧩 How It Works  
1. Collect and preprocess hand gesture images from webcam or dataset  
2. Encode gestures and train a CNN model to classify them  
3. live webcam feed and use the trained model for gesture recognition  
4. Can Map recognised gestures to user-defined commands (Not done yet)

## 📦 Tech Stack  
- Python (core programming language)  
- OpenCV for webcam capture and image processing  
- TensorFlow / Keras for CNN model training and inference  
- NumPy for data manipulation

## 🚀 Getting Started  
To run this project locally:  
```bash
git clone https://github.com/sh-momina/CNN-Gesture-Detection.git  
cd CNN-Gesture-Detection  
