FROM fedora:39

# update packages to the newest version
RUN dnf update -y

# golang
RUN mkdir -p /go
RUN dnf install -y golang

WORKDIR /go