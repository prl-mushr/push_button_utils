# Push Button Utils for MuSHR.
A simple ROS node to interface with the GPIO bumper button at the front of the car.

### Push button utils API

Topic | Type | Description
------|------|------------
`/bumper_button/push_button_state`|[std_msgs.Bool](http://docs.ros.org/api/std_msgs/html/msg/Bool.html)|Whether the button on the front of the car is depressed or not.
