🚀 Face & Gender Detection Using Deep Learning & OpenCV

Before starting anything download the model - https://github.com/eveningglow/age-and-gender-classification/blob/master/model/gender_net.caffemodel

This project demonstrates how to build a real-time face detection and gender classification system using OpenCV, cvlib, and a pre-trained deep learning model. The system detects human faces in images, classifies each as Male or Female, and annotates the results with bounding boxes and confidence scores — all in real time.

🔍 Key Features:
✅ Face Detection using cvlib
✅ Gender Classification using a Caffe-based Deep Neural Network
📏 Automatic image resizing for optimal performance
🎯 Annotated output with bounding boxes and confidence scores
🖥 Real-time visualization using OpenCV

🛠 Tech Stack:
Python
OpenCV
cvlib
Pre-trained GenderNet model (gender_net.caffemodel)

📸 Sample Output
(Attach an image or GIF of the project in action)


🧠 How It Works
An input image (or real-time webcam feed) is passed to the system.
Faces are detected using cvlib.detect_face().
Each detected face is cropped and passed through the GenderNet model.
The model returns a gender prediction and confidence score.
Results are displayed with OpenCV, showing labels and boxes around each face.


This project was a hands-on exercise in combining computer vision and deep learning for real-world applications. It showcases the power of pre-trained networks and simple OpenCV pipelines to build smart systems efficiently. I'm always open to feedback and collaboration. Feel free to fork, star ⭐, or raise issues!
