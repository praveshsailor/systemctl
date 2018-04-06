Docaker Systemctl on CentOS 7.

Base Docker Image

https://hub.docker.com/r/openshift/base-centos7/

To Start container use command.

#docker run -ti -v /sys/fs/cgroup:/sys/fs/cgroup:ro --privileged -d --name "container name"