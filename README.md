# Attendance System

This project is a facial recognition-based attendance system using OpenCV and Haar Cascade classifiers. It captures images, trains a model, and recognizes faces to mark attendance.

## Features
- Capture images for attendance records
- Train a face recognition model
- Recognize faces in real-time and mark attendance
- Check camera functionality

## Installation
### Prerequisites
Ensure you have Python installed along with the required dependencies.

### Install Dependencies
```bash
pip install opencv-python numpy pandas
```

## Files and Description
- **Capture_Image.py** – Captures images of students/employees for training.
- **Recognize.py** – Runs real-time face recognition and marks attendance.
- **Train_Image.py** – Trains the model with captured images.
- **Trainner.yml** – The trained model file.
- **check_camera.py** – Checks if the webcam is working correctly.
- **haarcascade_frontalface_default.xml** – Haar Cascade file for face detection.
- **homge.py** – (Needs clarification on purpose; please update as needed.)

## Usage
### 1. Capture Images
Run the following command to capture images for training:
```bash
python Capture_Image.py
```

### 2. Train Model
Train the face recognition model using:
```bash
python Train_Image.py
```

### 3. Recognize Faces and Mark Attendance
To recognize faces in real-time and mark attendance:
```bash
python Recognize.py
```

### 4. Check Camera
Before running recognition, check if the camera is working:
```bash
python check_camera.py
```

## Contributing
Feel free to submit issues or pull requests to improve the project.



