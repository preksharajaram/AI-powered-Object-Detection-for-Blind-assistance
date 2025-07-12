AI-Powered Object Detection for Blind Assistance 👁️🤖
🔍 Overview
AI-Powered Object Detection for Blind Assistance is an intelligent assistive system designed to help visually impaired individuals recognize and navigate their surroundings with greater confidence. The solution leverages YOLOv8 for real-time object detection and communicates the identified objects via audio feedback, enabling safer and more independent movement.

🛠️ Features
✅ Real-time object detection using YOLOv8

✅ Uses phone camera (IP webcam) for input

✅ Text-to-speech feedback for identified objects

✅ Simple and intuitive Streamlit-based web app

✅ Trained and tested using Kaggle & Google Colab

✅ Lightweight and accessible interface for everyday use

🔧 Tech Stack
Frontend: Streamlit

Backend: Python

Model: YOLOv8 (Ultralytics)

Training Platform: Google Colab, Kaggle

Camera: IP Webcam (mobile device)

Audio: pyttsx3 / gTTS for text-to-speech

🚀 How It Works
Start the web app (streamlit run app.py)

Connect the phone camera as an IP webcam

Objects in the camera feed are detected in real-time

Detected objects are read aloud to the user instantly

📁 Project Structure
bash
Copy
Edit
📦 AI-Powered-Object-Detection-for-Blind-Assistance
├── app.py                  # Main Streamlit app
├── detect.py               # Object detection logic
├── model/                  # YOLOv8 model files
├── requirements.txt        # Dependencies
├── utils/                  # Utility scripts (camera feed, audio, etc.)
├── README.md               # Project documentation
🔉 Sample Use Case
A visually impaired person opens the app

The app starts the mobile camera stream

It detects objects like "chair", "person", "door", "bottle"

The app gives audio feedback: "Chair ahead", "Person to your left"

📦 Installation
bash
Copy
Edit
git clone [https://github.com/yourusername/AI-Powered-Object-Detection-for-Blind-Assistance.git](https://github.com/preksharajaram/AI-powered-Object-Detection-for-Blind-assistance.git)
cd AI-Powered-Object-Detection-for-Blind-Assistance
pip install -r requirements.txt
streamlit run app.py
📢 Acknowledgements
Ultralytics YOLOv8

Streamlit

Google Colab

Kaggle Datasets

💡 Future Enhancements
GPS integration for outdoor navigation

Voice command support

Obstacle distance estimation

Wearable camera hardware integration
