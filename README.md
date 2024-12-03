﻿# ANN-Fire-Detection-Extinguisher-Project

 ## Summary of Workflow 

 In this project, Raspberry Pi sends the image it receives from the camera to the computer via port 5000, then the computer performs the necessary calculation and sends it back to Raspberry Pi via port 12345. Thanks to our model trained with Yolov8, the computer calculates the center position of the area where the flame is located with the image taken by the camera and sends it to Raspberry, which in turn sends it to the servos. When the servos complete their rotation towards the area where the flame is located, the water pump completes the process of extinguishing the flame by spraying water towards the flame.

#   F i r e - D e t e c t i o n - E x t i n g u i s h e r - P r o j e c t  
 #   F i r e - D e t e c t i o n - E x t i n g u i s h e r - P r o j e c t  
 