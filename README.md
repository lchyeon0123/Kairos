```
cd LCH/src
roscore --> 1 terminal
python3 marker_detection.py --> 2 terminal
python3 teleop.py --> 3 terminal
rviz --> 4 terminal
```

The recognized ArUCo Marker and the robot's path can be visualized in real time to monitor the robot's condition and environment. Use OpenCV's drawDetectedMarkers and drawAxis functions to display the recognized markers and robot's position on the screen.  
Below is the actual screen of the webcam.

<img src="https://github.com/lchyeon0123/Kairos/assets/99176235/24b4bf44-f8c0-4340-992e-f4c05a59a61b">  



Converts the processed image into a ROS Image message and publishes it through the ROS topic. Such information can be visualized in real time through rviz, allowing intuitive visibility of the robot's location and driving path.  
Below is the actual screen of rviz.

<img src="https://github.com/lchyeon0123/Kairos/assets/99176235/1f56e26a-aa8a-42f9-b802-822759cb32e8" width="400" height="200">
