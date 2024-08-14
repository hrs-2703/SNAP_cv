# Real-Time Face Detection with Dynamic Overlays

This project is a fun and interactive Python application that uses OpenCV to perform real-time face detection and allows users to apply dynamic overlays on detected faces. Users can switch between different overlay images using numeric key presses.

## Features

- **Real-Time Face Detection**: Detects faces in a live video feed from your webcam.
- **Dynamic Overlays**: Apply different overlays (e.g., sunglasses, hats) on detected faces based on key presses.
- **Mirror View**: The video feed is flipped horizontally to provide a mirror-like experience.



## Installation

1. **Clone the repository:**
  using git clone

2. Install dependencies:
Make sure you have Python 3. x installed. Then, install the required Python packages using pip
install opencv-python opencv-python-headless cv zone

3. Download Haar Cascade:
The project uses OpenCV's pre-trained Haar Cascade for face detection. Make sure it's available in your environment:
import cv2
print(cv2.data.haar cascades)
https://github.com/opencv/opencv/tree/master/data/haarcascades

5. Run the script:
python face_detection_overlay.py
