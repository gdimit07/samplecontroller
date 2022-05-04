FROM centos:7
MAINTAINER Karim Boumedhel <karimboumedhel@gmail.com>
RUN yum -y install git epel-release python3 python3-pip && yum clean all && rm -rf /var/cache/yum
RUN pip3 install kubernetes && pip3 install PyYAML
RUN alternatives --install /usr/bin/python python /usr/bin/python2 50
RUN alternatives --install /usr/bin/python python /usr/bin/python3 60