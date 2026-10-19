# SAEINDIA Self-Driving Car Challenge — Team AVIDA

[![Competition](https://img.shields.io/badge/SAEINDIA-Self--Driving%20Car%20Challenge-00529B)](https://saeiss.org/)
[![Achievement](https://img.shields.io/badge/Result-2nd%20of%2012%20Teams-14804A)](#competition-highlight)
[![Team](https://img.shields.io/badge/Team-AVIDA-6F42C1)](#team-and-competition)

This repository documents **Team AVIDA's** work in the **SAEINDIA Southern Section Self-Driving Car Challenge 2021–2022**. The challenge brought together computer vision, deep learning, simulator-based driving, vehicle detection, and state-estimation concepts through six projects.

> **Competition result: 2nd place out of 12 teams** 🏆

Team AVIDA participated as a 10-student team from the **National Institute of Technology Agartala (NIT Agartala)**. The challenge ran from September 2021 to May 2022 and included project code, technical reports, and presentation posters across six project tracks.

## Competition highlight

- **Competition:** SAEINDIA Southern Section Self-Driving Car Challenge (2021–2022)
- **Team:** AVIDA — *Autonomous Vehicle in Intelligence Driving and Assistance*
- **Institution:** National Institute of Technology Agartala
- **Team ID:** `SDCC2021001`
- **Duration:** September 2021 – May 2022
- **Achievement:** **2nd place among 12 participating teams**

## Projects in this repository

The challenge consisted of six projects. The sections below summarize each project's objective and the main methods covered in its materials. Follow the project links to explore the available code, reports, and posters.

| # | Project | Overview | Main concepts / tools | Project files |
|---|---|---|---|---|
| 1 | **Lane Finding Basic** | Detect lane lines in camera images or video and estimate the vehicle's position relative to the lane. | Python, OpenCV, NumPy, thresholding, perspective transformation, lane-pixel identification, lane curvature and center offset. | [Open project 1](https://github.com/krushnakant-borude/SAE-Self-Car-Driving-Competition/tree/master/%231) |
| 2 | **Traffic Sign Classifier** | Train a classifier to recognize road signs from images and predict the class of new sign images. | Python, TensorFlow/Keras, convolutional neural network (CNN), German Traffic Sign Recognition Benchmark (GTSRB), 43 classes and 50,000+ images. | [Open project 2](https://github.com/krushnakant-borude/SAE-Self-Car-Driving-Competition/tree/master/%232) |
| 3 | **Behavioral Cloning** | Learn driving behavior from example simulator frames and predict steering actions from front-camera images. | CNN-based end-to-end learning, simulator data collection, preprocessing, training/validation, and model optimization. | [Open project 3 materials](https://github.com/krushnakant-borude/SAE-Self-Car-Driving-Competition/tree/master/%233/Report) |
| 4 | **Advanced Lane Finding** | Detect lane boundaries in more challenging images and estimate lane curvature and vehicle offset. | Camera calibration, distortion correction, color and gradient thresholding, bird's-eye perspective transform, lane-boundary fitting. | [Open project 4 materials](https://github.com/krushnakant-borude/SAE-Self-Car-Driving-Competition/tree/master/%234/Report) |
| 5 | **Vehicle Detection** | Identify and highlight vehicles in road-camera frames or video. | OpenCV, image preprocessing, grayscale/thresholding, cascade classifier and Haar-feature-based detection. | [Open project 5](https://github.com/krushnakant-borude/SAE-Self-Car-Driving-Competition/tree/master/%235) |
| 6 | **Extended Kalman Filter (EKF)** | Explore state estimation for a moving object using simulated sensor measurements. | EKF prediction and update steps, measurement correction, uncertainty/covariance, and simulated RADAR/LiDAR data. | [Open project 6 materials](https://github.com/krushnakant-borude/SAE-Self-Car-Driving-Competition/tree/master/%236/Report) |

## My contribution

My primary presentation project was the **Traffic Sign Classifier**. My work included implementing and refining a Python/TensorFlow–Keras CNN using the German Traffic Sign Recognition Benchmark (GTSRB), training and evaluating the model, testing predictions on traffic-sign images, and presenting the project to the judges.

I also contributed to **lane-finding and vehicle-detection workflows** using OpenCV and NumPy. This included image thresholding, perspective transforms, estimating lane curvature and vehicle offset, and working with cascade-based vehicle detection. The other project folders document the broader scope of Team AVIDA's challenge work; contributions varied by project.

## Technology and topics

- **Programming and libraries:** Python, NumPy, OpenCV, TensorFlow, Keras
- **Computer vision:** image preprocessing, thresholding, perspective transforms, lane detection, vehicle detection
- **Deep learning:** CNN-based traffic-sign classification and simulator-based behavioral cloning
- **Autonomous-driving concepts:** lane geometry, steering prediction, object detection, and Kalman-filter-based state estimation
- **Dataset:** German Traffic Sign Recognition Benchmark (GTSRB) for traffic-sign classification

## Repository contents

The repository is organized around the six challenge projects. Depending on the project folder, you will find source code, a technical report, a presentation poster, or a combination of these resources. Project-specific setup steps and dependencies may differ, so review the files and report within the relevant folder before running code. Any external datasets or pretrained assets may need to be obtained separately according to the instructions and terms of their original sources.

## Acknowledgements and references

Thanks to **SAEINDIA Southern Section**, our project mentor, and the Team AVIDA members for the learning opportunity and collaboration throughout the challenge. Individual project reports and posters contain references to datasets, articles, tutorials, and other resources used during development.

This repository is shared for learning and portfolio documentation. Please consult the relevant project references and the original licenses/terms before reusing third-party code, datasets, or other assets.
