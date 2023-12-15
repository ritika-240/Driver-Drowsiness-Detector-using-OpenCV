# Driver-Drowsiness-Detector-using-OpenCV

1. Developed a real time drowsiness detector using OpenCV, Image Processing and ML; based on the eye aspect ratio and yawning of the driver. Preprocessed each frame of the video stream, applied the Haar-Cascade model for facial detection, and utilized the Dlib library to generate facial landmarks.

2. By analyzing the relative positions of these landmarks, the eye aspect ratio was calculated and compared against a threshold value. Further determined an acceptable number of consecutive frames exhibiting drowsiness to trigger wake-up alerts using the espeak library.

3. Additionally, the system took into account yawning as an indicator of drowsiness, with the threshold value determined through trial and error. Alarms were implemented using threading for seamless system operation.
