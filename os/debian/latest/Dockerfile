# get latest stable debian release image -- see https://hub.docker.com/_/debian/
from debian:latest

# maintainer email
MAINTAINER Tim Siwula <tcsiwula@gmail.com>

# add some labels
LABEL "rating"="five stars" "class"="first class"

# by defualt, docker runs all processes as root within the container
USER root

ADD VERSION .
