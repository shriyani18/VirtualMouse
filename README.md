

# 🖱️ Virtual Mouse using Hand Gesture Recognition

A real-time virtual mouse built using Python, OpenCV, and MediaPipe that allows users to control the cursor and perform clicks using hand gestures — no physical mouse required!

## 🚀 Features

- 🎯 Tracks hand landmarks in real-time using a webcam
- 🖐️ Moves cursor based on index finger position
- 👆 Clicks triggered by pinching (thumb & index close)
- 🧠 Built using OpenCV, MediaPipe, and PyAutoGUI

## 🛠️ Tech Stack

- Python 🐍
- OpenCV
- MediaPipe (for hand detection)
- PyAutoGUI (for mouse control)

## 📷 How It Works

- Capture webcam feed
- Detect hand landmarks using MediaPipe
- Track index and thumb positions
- Trigger `move` or `click` based on finger proximity

## 🔧 Installation

```bash
pip install opencv-python mediapipe pyautogui

