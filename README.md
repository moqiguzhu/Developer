# Developer

## maven
- You need to update the maven's settings.xml file in ~/.m2/settings.xml if you need.
- So that you can use maven to download your dependencies automatically from our local nexus server.
- 

## install JDK
- download JDK from ftp server with wget command
- extract JDK with tar command
- add JAVA_HOME environment variable
 - JAVA_HOME=JDK_DIR
- export JAVA_HOME
 - export JAVA_HOME
- add JAVA_HOME to PATH
 - PATH=$PATH:$JAVA_HOME/bin
- update PATH
 - export JAVA_HOME


## install redis(3.0.7)
- download redis
 - wget http://download.redis.io/releases/redis-3.0.7.tar.gz

- extract redis with tar command
 - tar xzf redis-3.0.7.tar.gz

- enter redis directory
 - cd redis-3.0.7

- redis is dependent on make
 - sudo apt-get install make

- redis is dependent on gcc
 - sudo apt-get install gcc

- redis is dependent on tcl
 - apt-get install -y tcl

- test whether redis is ready
 - make & make test

## install kafka
- download kafka from ftp server

- extract kafka

- test kafka
 - sh kafka/bin/zookeeper-server-start.sh kafka/config/zookeeper.properties &
 - sh kafka/bin/kafka-server-start.sh kafka/config/server.properties

## install riak
- download riak from ftp server
- install riak
 - sudo dpkg -i riak_2.1.3-1_amd64.deb & 
 - sudo apt-get install -f











