#Hama-docker

## Hama
Apache Hama is a general BSP computing engine on top of Hadoop, which was established in 2012 as a Top-Level Project of The Apache Software Foundation. It provides High-Performance computing engine for performing massive scientific and iterative algorithms on existing open source or enterprise Hadoop cluster, such as Matrix, Graph, and Machine Learning.[detail. https://hama.apache.org/](https://hama.apache.org/) 

## Pull the image from registry.hub.docker.com
The image is also released as an Docker image from Docker's automated build repository 
- you can always pull or refer the image when launching containers.
```
$ docker pull hoseog/hama-docker
```

## (optional)Download the source files
* [github. https://github.com/hoseoglee/hama-docker](https://github.com/hoseoglee/sirius-docker)
```
$ git clone https://github.com/hoseoglee/hama-docker.git
```

## (optional)Build the image
If you'd like to try directly from the Dockerfile you can build the image as:
```
$ docker build -tag hama-docker .
```

##Start a container
In order to use the Docker image you have just build or pulled use:
```
$ docker run -it --name hama-docker hama-docker /bin/bash
```

##Testing ()

