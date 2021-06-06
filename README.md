# docker-tomcat-tutorial
A basic tutorial on running a web app on Tomcat using Docker

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone "your git repository URL"
* cd 'docker-tomcat-tutorial'
* $docker build -t my-tomcat-webapp .
* $docker run -p 81:8080 my-tomcat-webapp
* http://localhost:81

# Links
[Sample Tomcat web app](https://tomcat.apache.org/tomcat-8.0-doc/appdev/sample/)
