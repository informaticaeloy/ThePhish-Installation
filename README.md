# ThePhish-Installation

```shell
sudo -v ; wget -q -O /tmp/install-thehive.sh https://archives.strangebee.com/scripts/install-deb.sh ; bash /tmp/install-thehive.sh

```

![image](https://user-images.githubusercontent.com/20743678/182128531-fcc82ec5-8b80-45bb-92b8-863cfb61d1bf.png)

usuario@ubuntu:~/Desktop$ wget -q -O /tmp/install-thehive.sh https://archives.strangebee.com/scripts/install-deb.sh 
usuario@ubuntu:~/Desktop$ bash /tmp/install-thehive.sh
---
THeHive installation script for Linux using DEB packages

Following softwares will be installed:
 - Cassandra 4.0.x
 - Elasticsearch 7.x
 - TheHive 5.x
 
It has sucessfully been tested on freshly installed Operating systems:
 - Ubuntu 20.04 LTS
 - Debian 11

Requirements: 
 - 4vCPU
 - 16 GB of RAM
 
Usage:
 
   $ sudo -v && bash install-deb.sh 
 

Maintained by: ©StrangeBee - https://www.strangebee.com

---


Installing package(s) wget gnupg apt-transport-https
[sudo] password for usuario: 
  package(s) wget gnupg apt-transport-https installed
Installing package(s) openjdk-11-jre-headless
  package(s) openjdk-11-jre-headless installed
Installing package(s) cassandra
 package(s) cassandra installed
Configuring cassandra
Installing package(s) elasticsearch
  package(s) elasticsearch installed
Configuring elasticsearch
Installing package(s) thehive
  package(s) thehive installed
Configuring thehive

Starting services
  * Service cassandra is starting
  * Service elasticsearch is starting
  * Service thehive is starting
>>>> TheHive installation complete! More information is available in /tmp/install-thehive.log file.


