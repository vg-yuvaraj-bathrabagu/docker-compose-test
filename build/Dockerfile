FROM ubuntu:18.04

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get -y install iputils-ping
COPY test.sh /tmp/test.sh
RUN chmod +x /tmp/test.sh
CMD ["/bin/sh", "/tmp/test.sh"]
#CMD ["echo test >> /tmp/test.txt"]
