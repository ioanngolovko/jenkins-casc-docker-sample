# jenkins-casc-docker-sample
Repository for docker image with Configuration as Code plugin

## Build me
` docker build . --tag=jenkins-casc-sample --rm`

## Run me

`docker run -p 8080:8080 -p 50000:50000 -e CASC_JENKINS_CONFIG=jenkins.yml jenkins-casc-sample`
