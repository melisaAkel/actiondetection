# 🤖 Sign Language Recognition with LSTM & Mediapipe

Welcome to the Sign Language Recognition project! This project utilizes Mediapipe for detecting hand landmarks and a Long Short-Term Memory (LSTM) neural network to recognize sign language gestures in real-time. 🎉

## 🚀 Project Overview

This project is designed to recognize and classify three basic sign language gestures: "Hello", "Thank You", and "I Love You". It captures sequences of hand landmarks from a webcam, processes the data, and uses a trained LSTM model to predict the sign language gesture. 

## 📂 Project Structure

- **MP_Data/**: Directory where the captured landmark data sequences are stored.
- **Logs/**: Directory for storing TensorBoard logs during training.
- **action.h5**: The trained LSTM model file.

## 📦 Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7+
- TensorFlow
- OpenCV
- Mediapipe
- Scikit-Learn
- Matplotlib

You can install all required libraries using:

pip install tensorflow opencv-python mediapipe scikit-learn matplotlib

## 🛠️ How It Works

1. **Data Collection**: The project captures hand, face, and pose landmarks using Mediapipe, and stores them as sequences.
2. **Model Training**: The sequences are used to train an LSTM model to recognize patterns corresponding to specific sign language gestures.
3. **Real-Time Prediction**: The trained model is then used to recognize gestures in real-time from webcam input.


## 🙏 Credits

This project was inspired by and based on the tutorial by Nick Nochnack. Check out his YouTube video and repository for more detailed guidance:

- **YouTube Tutorial**: [Nick Nochnack's Action Detection for Sign Language](https://www.youtube.com/watch?v=doDUihpj6ro)
- **GitHub Repository**: [Nick Nochnack's ActionDetectionforSignLanguage](https://github.com/nicknochnack/ActionDetectionforSignLanguage)


