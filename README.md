You can use any operating system according to your desire. I've implemented this project using RHEL.

In containerization world we need a docker image to launch any container. By this docker image the container can be launched within a second.

To start docker on you OS use "systemctl  start docker" command or "systemctl enable docker", in case you don't want to manually start docker after every time you boot your OS.

For this project you will need two docker images, one of WordPress and another one of MySQL, which can be downloaded from public repository by following command-
        "docker pull wordpress"
        "docker pull mysql"
        
To run the docker-compose.yml available in this repository, you need to setup docker compose on your OS.
        https://docs.docker.com/compose/install/
From this URL you can find the command to install docker compose according to the OS that you are using.

It is a good practice to always make a sperate directory for your docker-compose.yml file, move to this location. Finally use "docker-compose up" to run the file.

Now both the containers of WordPress as well as MySQL will be launched with connectivity.

Use "docker-compose stop" to stop the environment.
