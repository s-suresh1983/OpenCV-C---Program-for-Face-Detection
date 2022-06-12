# OpenCV C++ Program for Face Detection
 This program uses the OpenCV library to detect faces in a live stream from webcam or in a video file stored in the local machine
This program uses the OpenCV library to detect faces in a live stream from webcam or in a video file stored in the local machine. This program detects faces in real time and tracks it. It uses pre-trained XML classifiers for the same. The classifiers used in this program have facial features trained in them. Different classifiers can be used to detect different objects.
Requirements for running the program:
1) OpenCV must be installed on the local machine.
2) Paths to the classifier XML files must be given before the execution of the program. These XML files can be found in the OpenCV directory “opencv/data/haarcascades”.
3) Use 0 in capture.open(0) to play webcam feed.
4) For detection in a local video provide the path to the video.(capture.open(“path_to_video”)).
