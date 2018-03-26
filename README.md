# TrueShot

Goal:
Analyze images taken in burst mode and return the best image. Compare the images based on two parameters
-Blur detection
-Face and Eye detection

Platforms and Programming models used:
1.Android application
2.GPU – Grayscalling an image
3.Multithreading – Multiple threads for Image blur detection and eye detection	
4.OpenCV4AndroidSDK
5.HaarCascade classifiers for face and eye detection

Limitations:
1.Our approach does not work for all rotations. Sometimes if faces are tilted or turned the algorithm may fail to detect them.
2.Eye Detections is not accurate.


