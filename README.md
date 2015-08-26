# humanoid-ros_indigo-ubuntu14.04.3

Installation
====

Install ros-indigo in ubuntu14.04
While Setting the keys(during ros-indigo installation) use the key command with -E 
for eg. `sudo -E apt-key adv --keyserver hkp://pool.sks-keyservers.net --recv-key 0xB01FA116` 
this we because we have proxy settings in VNIT.
Also while initializing rosdep use `sudo -E rosdep init`

Instructions
------------
run `git clone https://github.com/manishsaroya/humanoid.git` in your terminal
then:
`cd humanoid/humanoid_ws`
`source devel/setup.bash`
`catkin_make`

