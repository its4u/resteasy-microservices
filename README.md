# RESTEasy Microservices
This project is an proof of concept of a REASTEasy microservice.
Its deployment target is a Servlet 3.0 container.
It is preconfigured for **Tomcat 7.0 JBoss EWS 2.0** OpenShift Cartridge.

## Try it
Usage is to create the application with the cartridge and to puish this code to the inner Git repository of the application.
It will be build with the openshift maven profile activated. This profile packages the WAR as ROOT.war in webapps folder where is it expected by the cartridge.

Microservices available at:
http://<domain>.rhcloud.com/hello/document/1

## Git hints
For hints on to push to the OpenShift application inner Git:
http://stackoverflow.com/questions/12657168/can-i-use-my-existing-git-repo-with-openshift/12669112#12669112

