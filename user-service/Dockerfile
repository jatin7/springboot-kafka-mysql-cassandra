FROM openjdk:8-jre-alpine

LABEL maintainer="ivangfr@yahoo.com.br"

RUN apk --no-cache add curl

ARG JAR_FILE
COPY ${JAR_FILE} /user-service.jar

CMD ["java", "-jar", "/user-service.jar"]

EXPOSE 8080