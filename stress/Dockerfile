FROM ubuntu:latest
MAINTAINER Lopaka Delp

RUN apt-get update
RUN apt-get -y install stress

CMD ["/usr/bin/stress", "--cpu", "2", "--io", "2", "--vm", "2", "--vm-bytes", "128M"]
