# A1

## A simple web server using Nginx running in a Docker container.

## Instructions on running the docker container:
1.	Open a terminal and go to the folder (e.g. A1) containing dockerfile, index.html and nginx.conf
2.	Enter    “docker build . -t my-server”  to build 
3.	After that, enter “docker run -it --rm -p 8081:80 my-server”  to run
4.	While the web server is running, open a browser and go to “localhost:8081”
5.	A web page with “Hello World” will appear
