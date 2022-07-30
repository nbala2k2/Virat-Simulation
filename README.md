# Virat-Simulation

### Steps:
  * `catkin_make`
  * `source devel/setup.bash`
  * `roslaunch pothole_detector display.launch` : to lauch the display.launch file
  * add `export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:$(rospack find pothole_detector)/models` to the end of `~/.bashrc`
  * topic name /virat/camera/image_raw
