

## Introduction
This project aims to design a system capable of detecting and tracking players, referees, and footballs in video footage using the YOLO (You Only Look Once) object detection framework. To enhance accuracy, the model will undergo training to optimize its performance. Additionally, the system will categorize players into teams by analyzing the colors of their jerseys through K-means clustering, a pixel-based segmentation technique. This classification will enable the calculation of a team’s ball possession percentage during a match.

To measure player movement accurately, optical flow analysis will be employed to account for camera motion between frames. Perspective transformation will then be applied to adjust for depth and scene perspective, allowing movement metrics (e.g., speed and distance covered) to be converted from pixel-based measurements to real-world units (meters). The project integrates computer vision and machine learning concepts, addressing practical challenges such as object tracking, color-based segmentation, and spatial analysis. It is designed to be accessible for learners new to machine learning while offering complexity and depth for more experienced engineers.



## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player
## INPUT

[Watch Input Video](https://drive.google.com/file/d/1JtNg_ClVSBWSepnU0VxE3kp4_9vlchZk/view?usp=drive_link)

## OUTPUT 

https://github.com/barnii77/footy-analytics/assets/output_video.mp4

[Watch Output Video ](https://drive.google.com/file/d/11ZPV1yx0iuBbvEYyaIxKs9nUBrxXk4Kb/view?usp=drive_link)

[Watch Output Screenshot](https://drive.google.com/file/d/1JWqvixvh3ksXC2AltVYCXCTPqrRf4u2t/view?usp=drive_link)

The output videos demonstrate:
- Player detection and tracking
- Team classification
- Ball possession tracking
- Speed and distance measurements
- Camera movement compensation
## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas