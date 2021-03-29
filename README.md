# TE-opencv-faces
Team Edge facial recognition project using Open CV. 
This project is based on the Instructables tutorial by [Marcelo Rovai](https://www.instructables.com/Real-time-Face-Recognition-an-End-to-end-Project/) - 
[Real-Time Face Recognition: An End-to-End Project](https://www.instructables.com/Real-time-Face-Recognition-an-End-to-end-Project/)

All projects are built using [OpenCV](https://opencv.org/) and other libraries.

This project consists of 4 main Python scripts. 

1. **face_detector.py** : The basic project that tracks faces and places a frame during a live stream. 
2. **face_recognizer.py** : Used to capture different faces. Places 30 images in the faces_dataset given one numerical index by Terminal input (0,1,2 ...)
3. **face_training.py** : Once there are faces in the faces_dataset folder, Run this app to Train your model. This is done once you have captured all the faces you wish to recognize. If you add more users in step 2, you must retrain by running this script again.
4. **face_recognition_final.py** : The final face recognizer app that will place a name label based on the face, along with a confidence score. You must define the list of users before running, as well as have the trainer create the .yaml file in step 3. 

### Install dependencies
Make sure to install OpenCV. Follow this tutorial to get started:
