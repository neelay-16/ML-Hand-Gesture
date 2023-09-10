# ML-Hand-Gesture
Control your computer's volume with hand gestures using Python and OpenCV! This project utilizes the mediapipe library to detect hand gestures and the pycaw library to adjust the system's audio volume. In this README, we'll break down the code step by step and explain how it works.

# Prerequisites
Before you get started, make sure you have the following libraries installed:
OpenCV (cv2)
Mediapipe (mediapipe)
PyCaw (pycaw)
NumPy (numpy)
You can install these libraries using pip:

# Preview

https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/ae7ea60b-59c1-4ef4-b1af-ae34cd1dffbf


# Description
Initializing my webcam:

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/452f97a5-40e4-41aa-b2de-1a03d48deb5e)

Next,I am configuring hand detection using mediapipe library

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/e0a0d7ae-30b4-4a15-913f-65a449fe0fa9)


Further,I am going to access my system's speaker

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/53151f15-68a8-408d-ae53-50dad0d01250)

Initializing the variables for volume control

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/edc5f48b-e0fe-440d-a9df-080950b6d383)

Next,I start capturing a video through which hands will get detected

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/476766ec-53dd-4c36-93c3-61092ab1fcb7)


Now, I am processing the captured frame to detect hand landmarks

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/2ff1e592-948f-47a7-8190-898fb47b8425)


Now, if hands are detected, lets try to retrieve hand landmarks and draw connections between them

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/edf27774-df1c-479d-9604-81176cd462bc)


Now that we have drawn connections between fingers, lets try to control the volume by our fingers. We will increase and decrease the volume by calculation the distance between thumb and index finger tips

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/1e5d7499-9ae6-4863-bda2-591442627d9a)


To display that our system volume is getting decreased and increased, lets display the volume bar and percentage on the video feed:

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/15fa7abf-6e6a-4256-a16e-5a7a1287124f)


Lastly,I will tell my program to stop the video feed and exit the loop by pressing spacebar

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/e402193c-27dc-46e9-aaf2-7c055963d2fb)


Release the webcam and close the window when done:

![image](https://github.com/neelay-16/ML-Hand-Gesture/assets/135517502/589b52e6-813a-4a3c-b15f-2792cfcf17f6)




Feel free to use and modify this code for your own projects. Enjoy controlling your computer's volume with hand gestures!






















