FROM openjdk:8-jdk-alpine
COPY target/com.spring.knapsack-1.jar app.jar
EXPOSE 8070 8070
ENTRYPOINT java -jar app.jar
#ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","app.jar","tar"]
#ENTRYPOINT bash
