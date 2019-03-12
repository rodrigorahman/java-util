# java-util

# Instalando Java em Linux 

```
$ sudo tar xzf jdk-8u151-linux-x64.tar.gz
$ cd jdk1.8.0_151/
$ sudo alternatives --install /usr/bin/java java /opt/jdk1.8.0_151/bin/java 2
$ sudo alternatives --config java
```


#Debug em docker

```shell
- ADDITIONAL_OPTS=-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005 -Xmx1G -Xms128m -XX:MaxMetaspaceSize=128m
```
