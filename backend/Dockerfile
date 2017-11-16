FROM openjdk:8-jre-alpine

ADD ./target/wildfly-swarm-polyglot-swarm.jar /opt/wildfly-swarm.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/opt/wildfly-swarm.jar"]