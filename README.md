# ✋💡 Hand Gesture Brightness Control

This project is a real-time hand gesture recognition system that adjusts screen brightness based on the distance between the **thumb** and **index finger tips**. Using a webcam and the **MediaPipe** library for hand tracking, the system detects hand landmarks, calculates the distance between specific finger tips, and adjusts the screen brightness accordingly via the `screen-brightness-control` library. The live feed, including hand landmarks and brightness information, is displayed using **OpenCV**.

---

## 🔧 Features

- 👋 Detects hand landmarks in real time using MediaPipe
- 📏 Measures the distance between thumb and index finger
- 💡 Adjusts screen brightness dynamically based on distance
- 🎥 Live webcam feed with visual indicators of detection and brightness level
- 🔄 Smooth and intuitive hand-gesture-based interaction

---

## 🛠️ Tech Stack

- **Python 3.x**
- [OpenCV](https://opencv.org/)
- [MediaPipe](https://google.github.io/mediapipe/)
- [screen-brightness-control](https://pypi.org/project/screen-brightness-control/)

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/HandGestureBrightnessControl.git
cd HandGestureBrightnessControl
```
###2. Create and Activate Virtual Environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```
###3. Install Dependencies
```bash
pip install opencv-python mediapipe screen-brightness-control
```
📸 Demo Output
![img2 (2)](https://github.com/user-attachments/assets/4c606a14-feff-4ffc-ae91-1e201221ea52)
![img1 (2)](https://github.com/user-attachments/assets/74150fbf-33e4-4688-bafc-5ddbff1d6d22)

Brightness Control Interface
