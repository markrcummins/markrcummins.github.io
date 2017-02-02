---
layout: project
type: project
image: images/server.jpg
title: Client Server Simulation
permalink: projects/client_server
date: 2016
labels:
  - C
  - TCP/IP
  - Networking
summary: An ongoing server client program in C that was started in ICS 451.
---

<img class="ui image" src="../images/c.png">

In ICS 451 we were tasked with simulating the client server model in C. The server needed to handle multiple client requests, simulate the TCP handshake, and correctly change the bit flags when sending and receiving data. 

The project was very arduous, as C is very unforgiving. Besides having to fix numerous segmentation faults, I really enjoyed making this since bit-shifting is my favorite thing to do in C. Making sure the client sends SYN, then receives SYN-ACK, and then the last ACK for the handshake was the best part. 

It was also interesting reading the man pages for the TCP header and the Unix functions that set up the server. The man pages for the TCP header were slightly vague at some times, meaning you could interpret things differently. This could make your server different than others, which can create complications. I plan on continuing to improve this program over the course of my college career. 

Source: <a href="https://github.com/markrcummins/networks/tree/master/client_server"><i class="large github icon "></i>networks/client_server</a>

