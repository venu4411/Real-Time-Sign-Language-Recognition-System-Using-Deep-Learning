@@ -1,2 +1,165 @@
# Real-Time-Sign-Language-Recognition-System-Using-Deep-Learning
Developed a real-time sign language recognition system using CNN, RNN, and LSTM to translate gestures into text/speech, enabling communication between deaf and hearing individuals. Integrated OpenCV and MediaPipe for gesture tracking and deep learning for accurate translation.


---

# 🖐️ Real-Time Sign Language Recognition System Using Deep Learning

## 📌 Project Overview

This project is a **Real-Time Sign Language Recognition System** that translates hand gestures into **text and speech** using deep learning techniques. It helps bridge the communication gap between **deaf and hearing individuals**.

The system leverages **Computer Vision + Deep Learning** by integrating:

* OpenCV (real-time video processing)
* MediaPipe (hand tracking)
* CNN + RNN + LSTM (gesture recognition & sequence learning)

---

## 🚀 Features

* 🎥 Real-time gesture detection using webcam
* ✋ Accurate hand tracking using MediaPipe
* 🧠 Deep learning-based gesture classification
* 🔤 Converts gestures into text output
* 🔊 Optional text-to-speech conversion
* ⚡ Fast and efficient prediction

---

## 🛠️ Tech Stack

### 👨‍💻 Languages

* Python

### 📚 Libraries & Frameworks

* OpenCV
* MediaPipe
* TensorFlow / Keras
* NumPy
* Pandas
* pyttsx3 (for speech)

---
<img width="1920" height="1080" alt="Screenshot 2026-04-13 221540" src="https://github.com/user-attachments/assets/e13c8878-1cd2-4ad8-8061-85e3a2c4d248" />

## 📂 Project Structure

```
Real-Time-Sign-Language-Recognition-System/
│
├── cnn8grps_rad1_model.h5       # Trained deep learning model
├── data_collection_binary      # Binary dataset collection
├── data_collection_final       # Final dataset
├── final_pred                  # Prediction scripts
├── prediction_wo_gui           # CLI-based prediction
├── AtoZ_3.1                    # Dataset (A-Z gestures)
├── From_table_of_content_report_s2t.docx
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/venu4411/Real-Time-Sign-Language-Recognition-System-Using-Deep-Learning/
cd Real-Time-Sign-Language-Recognition-System-Using-Deep-Learning
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

### 3️⃣ Activate Environment

* Windows:

```bash
venv\Scripts\activate
```

* Mac/Linux:

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install opencv-python mediapipe tensorflow numpy pandas pyttsx3
```

---

## ▶️ How to Run

### Run Prediction (Without GUI)

```bash
python prediction_wo_gui/main.py
```

OR (based on your folder structure)

```bash
python final_pred/predict.py
```

---

## 🧠 Model Details

* **CNN** → Feature extraction from hand gestures
* **RNN/LSTM** → Sequence learning for dynamic gestures
* **Input** → Hand landmarks / image frames
* **Output** → Predicted alphabet/word

---

## 📊 Workflow

1. Capture video using webcam
2. Detect hand landmarks using MediaPipe
3. Preprocess input data
4. Feed into trained deep learning model
5. Predict gesture
6. Convert to text / speech

---

## 🎯 Applications

* Assistive technology for deaf & mute individuals
* Real-time communication tools
* Educational tools for learning sign language
* Human-computer interaction

---

## 🔮 Future Improvements

* Add full sentence prediction
* Improve accuracy with larger datasets
* Deploy as web/mobile application
* Multi-language support
* GUI interface

---


## 👨‍💻 Author

**Siliveru Venu**
B.Tech CSE 

---
