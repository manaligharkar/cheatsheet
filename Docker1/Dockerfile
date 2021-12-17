FROM fedora:29

RUN groupadd -r swuser -g 433 && \
    useradd -u 431 -r -g swuser -s /sbin/nologin -c "Docker image user" swuser

USER root

RUN dnf install -y vim

USER swuser
=======================================================================
