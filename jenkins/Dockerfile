FROM jenkins/jenkins:lts-jdk17

USER root

# Gerekli paketler: git, docker ve docker-compose
RUN apt-get update && \
    apt-get install -y git docker.io docker-compose && \
    rm -rf /var/lib/apt/lists/*

# Tekrar Jenkins kullanıcısına dön
USER jenkins
