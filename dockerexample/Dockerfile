FROM openjdk:8
ADD target/docker-springboot.jar /root
EXPOSE 8005
ENTRYPOINT ["java", "-jar","docker-springboot.jar"]