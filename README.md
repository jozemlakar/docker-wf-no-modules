# Ixtlan Team WildFly Docker image

This is a Dockerfile with [WildFly application server](http://wildfly.org/) with modules removed. This docker then serves as a root for building app dockers by Ixtlan Team.

## Building

Build 

    docker build --tag=ixtlan-team/wildfly-no-modules:10.1.0.Final .

## References

This project is based on https://github.com/JBoss-Dockerfiles/wildfly
