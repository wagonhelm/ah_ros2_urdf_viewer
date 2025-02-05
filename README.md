# Ability Hand ROS2 URDF Viewer

This repo has a Docker Compose / Dockerfile which pulls the latest URDF from the 
ability-hand-api repository and converts it to a ROS2 friendly format, and 
launches it using RVIZ.

## Installing docker

### Linux

Docker installation instructions for various linux distributions can be found
[here](https://docs.docker.com/engine/install/) Ensure you do the 
[post installation instructions](https://docs.docker.com/engine/install/linux-postinstall/)


## Launch

### Linux

Navigate to the docker directory and enter the following command

xhost + && docker compose build && docker compose up

