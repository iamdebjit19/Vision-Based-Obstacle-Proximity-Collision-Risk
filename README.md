# Vision-Based Obstacle Proximity & Collision Risk Estimation

## Overview
This project implements a vision-based system to estimate obstacle proximity and assess collision risk using monocular camera input. The system detects objects, tracks their spatial position relative to the ego vehicle, and identifies potential collision zones.

## Technologies Used
- Python
- OpenCV
- YOLO (Object Detection)
- NumPy
- Matplotlib
- Jupyter Notebook

## Pipeline
1. Input video/frame acquisition
2. Object detection using deep learning
3. Obstacle proximity estimation (image-based heuristics)
4. Collision zone definition
5. Collision risk assessment

## Results
The system successfully identifies obstacles within the ego vehicle’s forward path and highlights potential collision risks in real-world driving scenarios.

## Limitations
- Monocular depth ambiguity
- False positives near ego-vehicle boundaries
- No sensor fusion (LiDAR / Radar)

## Future Work
- Ego-motion compensation
- TTC-based risk reasoning
- Sensor fusion

## Author
Debjit Ghosh

