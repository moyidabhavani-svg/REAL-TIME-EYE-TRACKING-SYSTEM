# REAL-TIME-EYE-TRACKING-SYSTEM
## Overview
The **Real-Time Eye Tracking System** is an MCA final-year project designed to detect and track a user's eye movements using computer vision and artificial intelligence techniques. The system captures live video from a webcam, identifies facial landmarks, tracks eye positions, and estimates the user's gaze direction in real time.

This project is especially useful for assisting physically challenged individuals, enabling hands-free computer interaction, and improving accessibility. It can also be applied in healthcare, education, human-computer interaction, gaming, and driver monitoring systems.

## Features
- Real-time eye detection and tracking
- Face detection using computer vision
- Eye landmark detection
- Gaze direction estimation
- Live webcam processing
- User-friendly interface
- Fast and accurate tracking
- Low-cost implementation using a standard webcam

## Technologies Used
- Python
- OpenCV
- MediaPipe
- NumPy
- PyAutoGUI (for cursor control)
- Tkinter (optional GUI)
 -Visual Studio Code
- Git

## System Requirements

### Hardware
- Intel Core i3 or higher
- 4 GB RAM (8 GB recommended)
- HD Webcam
- Windows 10/11
- Internet connection (for installing dependencies)

### Software
 Python 3.10 or later
- Visual Studio Code
- OpenCV
- MediaPipe
- NumPy
- PyAutoGUI
- pip

## Project Structure

```
Real-Time-Eye-Tracking-System/
│
├── dataset/
├── models/
├── src/
│   ├── main.py
│   ├── eye_tracking.py
│   ├── face_detection.py
│   ├── gaze_estimation.py
│   └── utils.py
│
├── requirements.txt
├── README.md
└── assets/
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/username/Real-Time-Eye-Tracking-System.git
```

2. Move into the project folder:

```bash
cd Real-Time-Eye-Tracking-System
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Run the project:

```bash
python main.py
```

## Working

1. The webcam captures live video.
2. Face detection identifies the user's face.
3. Eye landmarks are detected using MediaPipe.
4. Eye movement is analyzed frame by frame.
5. The system estimates the gaze direction.
6. The detected eye movement can be used to control applications or assist users.

## Applications
- Assistive technology for physically disabled people
- Hands-free computer control
- Healthcare monitoring
- Driver drowsiness detection
- Virtual reality (VR)
- Gaming
- Human-computer interaction
- Educational research

## Future Enhancements
- Blink detection
- Eye-controlled virtual keyboard
- Wheelchair control using eye gaze
- Voice assistant integration
- Mobile application support
- Deep learning-based gaze estimation
- Multi-user tracking

## Advantages
- Contactless interaction
- Real-time performance
- Easy to use
- Cost-effective
- High accuracy
- Improves accessibility
- Portable and scalable

## Limitations
- Performance depends on lighting conditions.
- Requires a functioning webcam.
- Accuracy may reduce if the face is partially covered.
- Rapid head movements can affect tracking.

## Conclusion
The Real-Time Eye Tracking System demonstrates how computer vision and artificial intelligence can be used to create an intelligent, accessible, and efficient human-computer interaction system. The project provides a practical solution for eye movement tracking and has significant applications in healthcare, accessibility, education, and smart automation.

