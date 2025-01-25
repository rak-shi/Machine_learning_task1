# Gesture Recognition, Lip Tracking, and Data Augmentation

This repository contains the project for **gesture recognition**, **lip tracking**, and **data augmentation** using **MediaPipe** and **TensorFlow**.

## Project Overview
- **Gesture Recognition**: Detects hand gestures (e.g., the "OK" gesture) using hand landmark detection.
- **Lip Tracking**: Uses MediaPipe's face mesh to track lip movements and extract cropped images of the lips from video frames.
- **Data Augmentation**: Applies various transformations like rotation, shifting, and flipping to generate a more diverse dataset for training.

## Files Included
- `gesture_recognition/` - Contains scripts for detecting and processing hand gestures.
- `lip_tracking/` - Contains scripts for detecting face landmarks and tracking lip movements in video frames.
- `data_augmentation/` - Contains scripts for augmenting the gesture and lip tracking images.
- `Document.pdf` - The final report with detailed explanations, results, and analysis of the project.
## Acknowledgements
- MediaPipe: Used for lip tracking and face mesh analysis.
- TensorFlow: Used for data augmentation and deep learning models.
- OpenCV: Used for reading and processing images and videos.
## Output Structure
  /gesture_recognition
    ├── gesture_detection.py
    └── utils.py
/lip_tracking
    ├── extract_frames.py
    ├── lip_tracking.py
    └── utils.py
/data_augmentation
    ├── augment_data.py
    ├── visualize_augmented.py
    └── utils.py
/outputs
    ├── cropped_lips/
    ├── augmented_lips/
    └── visualizations/
/Document.pdf





