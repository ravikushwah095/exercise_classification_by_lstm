# 💪 Push-Up Exercise Classification using LSTM & MediaPipe

## 📌 Project Overview

This project focuses on automatically classifying push-up exercises as **Correct** or **Incorrect** using deep learning and human pose estimation techniques.

The system uses MediaPipe to extract body keypoints from exercise videos and applies an LSTM (Long Short-Term Memory) neural network to analyze temporal movement patterns. The model learns body motion sequences and identifies whether a push-up is performed with proper form.

This project demonstrates the application of Computer Vision and Deep Learning for AI-powered fitness tracking and automated exercise coaching.

---

## 🎯 Project Objective

The objective of this project is to develop an AI-based exercise classification system that can:

- Analyze human body movements from videos
- Extract pose landmarks using MediaPipe
- Learn temporal motion patterns using LSTM
- Classify push-ups into:
  - Correct Form
  - Incorrect Form

---

## 📂 Dataset

The dataset contains push-up exercise videos categorized into two classes:

### Classes

✅ Correct Push-Ups  
- Properly performed push-up movements

❌ Incorrect Push-Ups  
- Incorrect posture or movement patterns

---

## 📊 Dataset Processing

The raw videos were processed using **MediaPipe Pose Estimation** to extract body keypoints.

Generated data:

- Video sequences
- Human body landmarks
- `.npy` keypoint files

These processed sequences are used as input for the LSTM model.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- LSTM Neural Networks
- MediaPipe
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 🧠 Model Architecture

### Human Pose Extraction

**MediaPipe Pose**

- Detects human body landmarks
- Extracts joint coordinates
- Converts videos into numerical pose sequences

### Classification Model

**LSTM (Long Short-Term Memory Network)**

Why LSTM?

- Exercise movements are sequential
- Body posture changes over time
- LSTM captures temporal dependencies between frames

---

## 🔍 Project Workflow

1. Video Data Collection
2. Frame Processing
3. Pose Landmark Extraction
4. Keypoint Sequence Generation
5. Data Preparation
6. LSTM Model Training
7. Model Evaluation
8. Exercise Classification

---

## ⚙️ Data Preprocessing

Performed preprocessing steps:

- Video frame extraction
- Pose detection using MediaPipe
- Body keypoint extraction
- Sequence formatting
- Label encoding
- Training-validation split
- Data normalization

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Loss and Accuracy Curves

---

## 📊 Visualizations

The project includes:

- Sample Exercise Frames
- Pose Landmark Visualization
- Training Accuracy Curve
- Training Loss Curve
- Confusion Matrix
- Prediction Results

---

## 🔑 Key Features

✅ Human Pose-Based Exercise Analysis  
✅ Correct vs Incorrect Form Detection  
✅ Video Sequence Classification  
✅ LSTM Temporal Learning  
✅ AI Fitness Coaching Pipeline  
✅ Automated Movement Evaluation  

---

## 💼 Real-World Applications

### Fitness Applications
- Smart workout assistants
- Exercise tracking apps
- AI personal trainers

### Healthcare & Rehabilitation
- Physical therapy monitoring
- Recovery exercise assessment
- Posture correction systems

### Sports Science
- Athlete performance analysis
- Biomechanics research
- Training optimization

### Wellness Platforms
- Workplace fitness programs
- Health monitoring systems

---

## 📁 Project Structure

```
LSTM-PushUp-Classification/
│
├── Dataset/
│   ├── Correct/
│   └── Incorrect/
│
├── Keypoints/
│   └── .npy files
│
├── Models/
├── Notebook.ipynb
├── Results/
└── README.md
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/LSTM-PushUp-Classification.git
```

### Install Dependencies

```bash
pip install tensorflow mediapipe opencv-python numpy matplotlib scikit-learn
```

### Run Notebook

```bash
jupyter notebook
```

Execute all cells to process videos, train the LSTM model, and classify exercise movements.

---

## 📚 Skills Demonstrated

- Deep Learning
- Computer Vision
- Human Pose Estimation
- Sequence Modeling
- LSTM Networks
- MediaPipe
- Video Processing
- Movement Classification
- Fitness AI

---

## 🚀 Future Improvements

- Real-time webcam exercise detection
- Rep counting system
- Exercise quality scoring
- Multiple exercise classification
- Mobile application deployment
- Real-time AI fitness coach
- Transformer-based motion analysis

---

## 👨‍💻 Author

**Ravi Kushwah**

GitHub: https://github.com/ravikushwah095

⭐ If you found this project useful, consider giving it a star on GitHub!
