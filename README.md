# LearningDocker
The included Dockerfile pulls the latest centos image, installs Spring XD (including
dependencies) and starts the XD singlenode.

To invoke from the directory where Dockerfile is located:\n
  docker build -t \e<tagname\e> .
  
For example:\n
  docker build -t whewatt/centosspringxd .