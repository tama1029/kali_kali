FROM kalilinux/kali-rolling:latest
RUN sed -i "s/http.kali.org/mirrors.ocf.berkeley.edu/g" /etc/apt/sources.list && \
  apt-get update && \
  apt-get -y upgrade && \
  apt-get -y install nmap
