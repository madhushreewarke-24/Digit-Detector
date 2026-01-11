## Object-Detection-Using-Tensorflow
In this project, I did Object Detection with TensorFlow, and the idea was to educate a computer in identifying and detecting objects in images.
Here I have performed detection of  single digit number that is identify the number and position in the image. This topic object detection is now an integral part of our everyday lives—from security cameras and autonomous vehicles to healthcare and intelligent devices.
I developed our model with TensorFlow, trained it with data sets, and tuned it so that it could recognize multiple objects simultaneously with good precision. It wasn't always a smooth process, though—there were issues such as working with large data sets and ensuring that the system was both fast and accurate. But issues like that served to show us how machine learning works in reality. This project was about seeing just how powerful and helpful AI can actually be.

## Objective 
1. To train an object detection system that is capable of identifying and detecting 
several objects within images  through the use of TensorFlow. 
2. To implement deep learning methods (like transfer learning) for enhancing 
detection accuracy and efficiency. 
3. To build a system that achieves a compromise between speed and accuracy, such 
that it is applicable to real-time systems. 
4. To acquire hands-on experience in preparing datasets, training, and fine-tuning 
machine learning models. 
5. To analyze real-world implementations of object detection in fields such as 
surveillance, autonomous vehicles, healthcare, and smart devices. 
6. To learn about challenges like dealing with big datasets, overfitting, and model 
optimization, and identify implementable solutions for them.

## Methodology 
1. Problem Identification & Tool Selection – Identified object detection objectives and 
chose TensorFlow due to its deep learning capabilities. 
2. Dataset Preparation – Gathered images, scrubbed data, and annotated with bounding 
boxes for training purposes from Kaggle (MNIST dataset of handwritten digits). 
3. Model Selection – Employed transfer learning using pre-trained models  
4. Training & Fine-Tuning – Trained on the dataset, tuned hyperparameters to enhance 
accuracy. 
5. Testing & Evaluation – Tested with images and evaluated based on accuracy, 
precision, and inference speed. 
6. Deployment – Implemented the system for real-time object detection with bounding 
boxes. 
7. Analysis – Reviewed strengths, weaknesses, and challenges to gain practical insights 
into AI applications.


# 🧠 Handwritten Digit Object Detection (Full Stack AI)

A full-stack AI web application that detects and classifies handwritten digits using a CNN-based deep learning model built with TensorFlow. The system also predicts the bounding box of the digit using object detection techniques.

---

## 🚀 Features

- ✍️ Draw any digit using mouse
- 🧠 AI predicts digit + bounding box
- 📊 Shows prediction confidence
- 🕒 Keeps prediction history
- ⚡ Fast React + Vite frontend
- 🔥 Flask backend API
- 🤖 CNN model trained on MNIST

---

## 🏗️ Tech Stack

**Frontend:**
- React + Vite
- HTML5 Canvas
- CSS3

**Backend:**
- Python
- Flask
- TensorFlow / Keras

**Model:**
- CNN for classification
- Bounding box regression

---

## 📁 Project Structure

---

## ⚙️ How To Run Locally

### 1️⃣ Backend

```bash
cd backend
pip install flask tensorflow opencv-python flask-cors numpy
python app.py

Backend will run on:
👉 http://127.0.0.1:5000

cd frontend
npm install
npm run dev

Frontend will run on:
👉 http://localhost:5173
```
📸 Screenshots

<img width="1919" height="905" alt="Screenshot 2026-01-11 200448" src="https://github.com/user-attachments/assets/1d3e9812-b615-4de5-807e-3237c5e8d675" />

<img width="1919" height="906" alt="Screenshot 2026-01-11 200400" src="https://github.com/user-attachments/assets/86354633-5c26-499e-b432-35c53c8b65ca" />

##🧪 Model Details

Dataset: MNIST
Input size: 75×75
Output:
Digit class (0–9)
Bounding box (x1, y1, x2, y2)

🎯 Use Cases

Educational AI demos
Computer Vision learning
AI-based drawing recognition
Resume & portfolio project

👩‍💻 Author

Madhushree Warke
Computer Engineering Student
Aspiring AI/ML Engineer
