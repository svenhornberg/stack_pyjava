FROM python:3-onbuild
ONBUILD RUN ["apt-get", "install", "-y", "openjdk-7-jre"]

# Define commonly used JAVA_HOME variable
ONBUILD ENV JAVA_HOME /usr/java/default
ONBUILD ENV PATH $PATH:$JAVA_HOME/bin

CMD ["java", "-version"]
