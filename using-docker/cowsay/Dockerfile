FROM ubuntu:bionic

RUN apt update && apt install fortune cowsay -y

COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]