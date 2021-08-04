# realtime-drowsiness-detection-system
This is a real-time drowsiness detection system using visual behaviour and machine learning. I've done this project using OpenCV and Tkinter. Drowsy driving is one of the major causes of road accidents and death. Hence, detection of driver’s fatigue and its indication is an active research area. Most of the conventional methods are either vehicle based, or behavioural based or physiological based.
Few methods are intrusive and distract the driver, some require expensive sensors and data handling. Therefore, in this study, a low cost, real time driver’s drowsiness detection system is developed with acceptable accuracy. In the developed system, a webcam records the video and driver’s face is detected in each frame employing image processing techniques. Facial landmarks on the detected face are pointed and subsequently the eyeaspect ratio, mouth opening ratio and nose length ratio are computed and depending on
their values, drowsiness is detected based on developed adaptive thresholding.


install neccessary packages
pip install imutils
pip install face_recognition
pip install opencv-python
pip install threaded
pip install playsound
pip install scipy
pip install numpy


download shape_predictor_68_face_landmarks.dat and add it to your project folder.This file is a pre-trained model used for face recognition and facial landmarking.



