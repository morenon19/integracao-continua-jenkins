FROM jenkins/jenkins:2.364-jdk11

USER root
RUN apt-get update && apt-get install -y maven

RUN echo 'export M2_HOME=/opt/apache-maven-3.5.4' >> ~/.bashrc
RUN echo 'export PATH=${M2_HOME}/bin:${PATH}' >> ~/.bashrc

USER jenkins