# Human Pose Detector using OpenCV and MediaPipe

## Overview

This project is a real-time Human Pose Detection system developed using Python, OpenCV, and MediaPipe.  
The application captures live video through a webcam and detects human body landmarks such as shoulders, elbows, knees, hands, and facial points.

The detected landmarks are connected to form a skeletal structure, enabling real-time body movement tracking and pose estimation.

---

## Features

- Real-time human pose detection
- Detects full body landmarks
- Live webcam feed processing
- Draws pose connections and keypoints
- Lightweight and fast performance
- Simple and beginner-friendly implementation

---

## Technologies Used

- Python
- OpenCV
- MediaPipe

---

## Project Structure

```text
Human-Pose-Detector/
│
├── pose_detector.py
├── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Human-Pose-Detector.git
```

### 2. Move into Project Folder

```bash
cd Human-Pose-Detector
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Required Libraries

```text
opencv-python
mediapipe
```

---

## How to Run

```bash
python pose_detector.py
```

After running the program:

- Webcam will open automatically
- Human body landmarks will be detected
- Pose skeleton will be displayed in real time

Press `q` to exit the application.

---

## Applications

- Fitness and exercise tracking
- Gesture recognition
- Sports movement analysis
- Human-computer interaction
- Surveillance systems

---

## Future Improvements

- Multi-person pose detection
- Pose classification
- Exercise repetition counter
- AI-based activity recognition

---

## Output

The system displays:

- Real-time webcam feed
- Body keypoints
- Skeletal pose connections

---

## Author

Developed as a computer vision mini project using Python and OpenCV.
