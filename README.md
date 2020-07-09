# Lock/Unlock Ubuntu OS 

## Introduction
We can lock and unlock our Ubuntu system using face recognition(currently only on Ubuntu). 


## Requirements

Install below the required library in your local machine.

1) python 3.7
2) opencv 4.1.0
3) numpy 
4) face-recognition
5) sudo apt-get install gnome-screensaver  [ Used for screen locking functionality]
6) sudo apt-get install xdotool            [xdtools Lets you programatically simulate keyboard input and mouse activity]

1) **face_generate.py**
 It will detect your face and save it in the dataset folder and Create a folder with your Name eg: here "Vikash"
 
2) **face_train.py**
 This python Program will open the dataset folder and take your image from that and train your face using the K-nearest neighbor algorithm and face_recognition library.
 
3) **face_unlock.py**
 This is an important python file that will detect your face using the webcam and unlock the system.
