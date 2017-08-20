[![Build Status](https://travis-ci.org/phenompeople/apache-tomcat.svg?branch=master)](https://travis-ci.org/phenompeople/apache-tomcat)
[![Docker Automated build](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)](https://travis-ci.org/phenompeople/apache-tomcat)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Apache Tomcat


Dockerfiles for building a apache tomcat base images.

The images are available directly from [phenompeople organization] (https://hub.docker.com/u/phenompeople/)

These images are built based on **phenompeople/centos-sunjre:latest**


### Supported tags and respective `Dockerfile` links

#### phenompeople/centos-tomcat

* **`8.0.45` 	([8.0.45/Dockerfile](https://bitbucket.org/phenompeople/apache-tomcat/src/master/8.0.45/Dockerfile))**
* **`8.0.43` 	([8.0.43/Dockerfile](https://bitbucket.org/phenompeople/apache-tomcat/src/master/8.0.43/Dockerfile))**
* **`latest` 	([8.0.43/Dockerfile](https://bitbucket.org/phenompeople/apache-tomcat/src/master/8.0.43/Dockerfile))**
* **`services` ([8.0.43/Dockerfile](https://bitbucket.org/phenompeople/apache-tomcat/src/master/8.0.43/Dockerfile))**

### Ports Exposed from tomcat container 
```
Connector Port    : 8080
Shutdown port     : 8005
AJP Port          : 8009
Redirect Port     : 8443

```
#### Pre-Requisites

- install docker-engine [https://docs.docker.com/engine/installation/](https://docs.docker.com/engine/installation/)

## Maintainers

* Rajesh Jonnalagadda (<rajesh.jonnalagadda@phenompeople.com>)

## License and Authors

**License:**		Apache License

**Author :**		Phenompeople Pvt Ltd (<admin.squad@phenompeople.com>)
