# Object_Tracking_Deep_SORT_YOLOv8
Object Tracking with YOLOv5 and Deep SORT
This project is a real-time object tracking system using the YOLOv5 object detection model and the Deep SORT (Simple Online and Realtime Tracking) algorithm.
<h2 style="font-size: 24px;">Introduction</h2>
Object tracking is a crucial task in computer vision and has numerous applications in various fields, such as security and surveillance, traffic monitoring, and autonomous vehicles. YOLOv5 is a state-of-the-art object detection model that can detect and classify objects in real-time. Deep SORT, on the other hand, is a simple yet effective algorithm that performs online tracking by associating detections over time using a Kalman filter and the Hungarian algorithm.

This project combines these two algorithms to create a real-time object tracking system that can track multiple objects simultaneously. The YOLOv5 model is used to detect and classify objects in each frame of the video, while the Deep SORT algorithm tracks these objects across multiple frames, generating a unique ID for each object and predicting its future location.

<h2 style="font-size: 24px;">Requirements</h2>
Python 3.7 or higher</br>
PyTorch 1.7 or higher</br>
NumPy 1.19 or higher</br>
OpenCV 4.5 or higher</br>
CUDA 10.2 or higher (if using GPU)</br>

<h2 style="font-size: 24px;">Installation</h2>
Clone this repository

Install the required packages

You can download deep sort feature extraction model here https://drive.google.com/drive/folders/18fKzfqnqhqW3s9zwsCbnVJ5XF2JFeqMp

Run the script: python main.py

<h2 style="font-size: 24px;">Reference source</h2>
The Deep SORT repository from the official repository: https://github.com/nwojke/deep_sort</br>
The code I based it onhttps://github.com/computervisioneng/object-tracking-yolov8-deep-sort.git
