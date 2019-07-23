Set of perturbations on images from a camera embedded on a self-driving car
------------------------------------------------------------


* [Images](https://dropit.uni.lu/invitations?share=c54e0359be3e26a7a7c0) file contains all images with pertrubations of the camera embedeed on (on the right of) the self-driving car. Thus, the zip file contains both normal and abnormal images.


* We inject the following perturbations on rosbag file in **rosbag/**. Some of the perturbations are made manually.



| Scenario ID |Perturbation | Image |
|----|--------------------------|--------------------|
|1   |Insertion of a black image                     | frame000300.png    			 |
|2   |Insertion of a white image                     | frame000350.png    			 |
|3   |Blurred image                    | frame000400.png    			 |
|4   |Image from the past           | frame000450.png    			 | 
|5   |Successive same images   | frame000501.png until frame000505.png|
|6   |Flooding black images     | frame000550.png  to frame000560.png    |
|7   |Blur image (-blur 0x8)    | frame002000.png                        |
|8   |Modified image (Adding a black rectangle)           | frame002600.png                        |
|9   |Modified image (Adding a black rectangle on the traffic lights)| frame002700.png                        |
|10  |Modified image (replacing a red color by a green color in the traffic lights)| frame001470.png		         |
|11  |Modified image (in the traffic lights)   | frame001470.png                        |



Here is an example of scenarios used in the paper [1]



![Alt text](folder/scenario.png?raw=true "Scenario of perturbations")




* The original data (rosbag file) is from [Udacity](https://scottontechnology.com/exploring-udacity-40gb-driving-data/).
	* For exporting data from rosbag file. You can use the following links:
		* https://wiki.ros.org/rosbag/Tutorials/Exporting%20image%20and%20video%20data
		* https://gist.github.com/wngreene/835cda68ddd9c5416defce876a4d7dd9
		








------------------------------------------------------------

[1] Sofiane Lagraa, Maxime Cailac, Sean Rivera, Frédéric Beck, Radu State: Real-Time Attack Detection on Robot Cameras: A Self-Driving Car Application. IRC 2019: 102-109





 


