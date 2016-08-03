LAPPS-CONTAINER

Docker image builder using ansible-container used to spin up containers that hold lappsgrid technologies in them.

`ansible-contaier`

In order to use this project you first need to install ansible-container. In order to do so please clone the ansible-container repository and run `python ./setup.py install` I recommend you sandbox this installation in a virtual machine (It makes installing its requirements easier i.e upgrading setuptools). Afterwards you are free to clone this project and use it to spin up any of the lappsgrid images

In order to spin up a specific image cd to that image's directory i.e `cd galaxy-lapps`
and run `ansible-container build` in order to build the image.

The service takes a little while to start up please be patient.

Afterwards in that same directory you can then run `ansible-container run` in order to run the image. 
