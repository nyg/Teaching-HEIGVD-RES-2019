# Teaching-HEIGVD-RES-2019
This is the main repo for the course RES, taught at HEIG-VD in 2019. 

This is where you will find lecture notes, slides and some of the examples presented in the class. We will also keep links to the different repos used throughout the semester (for assignments).

## Upcoming deadlines

**Monday, March 25th 2019**

* Be ready for a challenging week
* Understand and be able to explain the following concepts:
  * What is Docker? How are containers different from virtual machines?
  * What is the difference between the Docker CLI and the Docker engine? Why can we say that Docker is based on a client-server architecture?
  * What is the difference between a Docker image and a Docker container?
  * How does one create a Docker image? How does one create a Docker  container?
  * What is Dockerhub?
  * Be able to explain what happens when you type `docker run -it —rm alpine /bin/sh`. Be able to explain the meaning of every argument in this command.
  * Be able to explain how port mapping works in Docker. Be able to explain how to use the `-p xx:yy`parameter when using `docker run`.
* Have been able to run the [demo 1](https://github.com/SoftEng-HEIGVD/Teaching-Docker-SimpleJavaServer) on one's laptop during the week.
* Be able to perform the following operations
  * Write a Dockerfile to define an image that contains a TCP server written in Java
  * Run multiple containers from the same image
  * Obtain the IP address assigned to the each of these containers
  * Send requests to the TCP server running in the containers, with `nc`or `telnet`
  * Log into a running container and explore the file system

## General links

- YouTube [playlist](https://www.youtube.com/playlist?list=PLfKkysTy70Qa1IYbV9Xndojc7L-T4keF-)



## ~~Week 1: introduction~~

* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019-Chill) is the repo for the first assignment. Make sur to **fork** it, before cloning your fork on your machine.
* [Here](https://www.youtube.com/playlist?list=PLfKkysTy70QaN-uez0K4UpSpVUbt8ETpk) is  the Youtube playlist that presents the first assignment material.



## ~~Week 2: Java IO part 1 (intro + buffered IOs)~~

- [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/blob/master/slides/01-JavaIOs.pdf) are the slides
- [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/blob/master/lectures/01-Lecture1-JavaIOs.md) are the lecture notes
- [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/01-BufferedIOBenchmark/BufferedIOBenchmark) is the project used to present the impact of buffering on performance



## ~~Week 3: Java IO part 2 (decorator pattern + encodings)~~

* Same slides and lecture notes as in week 2
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/02-FileIOExample/FileIOExample) is the example for manipulations of files, streams and adapters

- [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/03-CharacterIODemo/CharacterIODemo) is the example for character encodings
- [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019-Labo-Java-IO) is the repo for the lab, which we will work on during weeks 3 and 4



## ~~Week 4: TCP programming~~

* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/blob/master/slides/02-TcpProgramming.pdf) are the slides
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/05-DumbHttpClient/DumbHttpClient) is an example of a simple TCP client (which does NOT implement the HTTP spec)
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/04-StreamingTimeServer/StreamingTimeServer) is an example of a simple TCP server (streams current time)
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/07-TcpServers/TcpServers) is an example of a multi-threaded TCP server (with workers)
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/tree/master/examples/06-PresenceApplication/PresenceApplication) is an example of a client-server application (presence)
* **Make sure that you have a working Wireshark on your machine!**

## Week 5: introduction to Docker

* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019/blob/master/slides/03-Docker.pdf) are the slides
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2019-Exercise-Calculator) is the repo for the protocol design exercise
* [Here](https://github.com/SoftEng-HEIGVD/Teaching-Docker-SimpleJavaServer) is the repo with the TCP server in Docker demo
* [Here](https://goo.gl/forms/JaEU6hp5oMJTDRx22) is the link for the "sanity check" Google Form

## Week 6

## Week 7

## Week 8

## Week 9

## Week 10

## Week 11

## Week 12

## Week 13

## Week 14

## Week 15

## Week 16



## Past deadlines

~~**Sunday, February 24th: everybody must have**:~~

- setup GitHub (with SSH), forked and cloned the "chill" project

- setup maven and been able to build "chill" on the command line

- setup IDEA (with Lombok project)

- either successfully added one beer (with a unit test and a production class) and submitted a PR or filed an issue in the upstream server to precisely describe what has not worked


~~**Sunday, March 3rd, 23:00 (strict): everybody must have**:~~

- added at least 3 beers, with tests, and submitted at least 3 PRs (with a green light on GitHub)
- added enough beers and submitted enough PRs to really master the GitHub workflow
- be able to explain what is maven and how to run it from the command line
- be able to explain what is project Lombok
- filled out this Google [form](https://goo.gl/forms/z4bsuOchWphZfj8V2).

~~**Sunday, March 17th, 23:00 (strict): everybody must have:**~~

- implemented the project, so that all tests are green
- submitted a PR on GitHub
- have the structure of the project and the role of all classes in mind, to be able to quickly extend it with a new functionality
- be ready to execute the project, know where to find the output files
- submitted [this Google form](https://goo.gl/forms/yz9uPwZHVIShXvFk2)

## 