# Drowsiness_Detection

A real time driver drowsiness detection system has been designed and implemented on Rpi using OpenCV, dlib and Python.

## Applications
This can be used by riders who tend to drive for a longer period of time that may lead to accidents.

## Code Requirements
The example code is in Python ([version 2.7](https://www.python.org/download/releases/2.7/) or higher will work).

## Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy

## Description
The objective of the project is to alarm the driver and the family members sitting remotely in case the person was found to close eyes for more than 2 seconds. An automatic alert will be sent to the family members by using Twilio api request.

<img src="https://github.com/kapilahuja11/Drowsiness_Detection/blob/main/eye1.jpg">

## Condition

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

## Relationship

<img src="https://github.com/kapilahuja11/Drowsiness_Detection/blob/main/eye2.png">

## Summing up

<img src="https://github.com/kapilahuja11/Drowsiness_Detection/blob/main/eye3.jpg">

For more information, [see](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

## Execution
To run the code, type `python Drowsiness_Detection.py`

