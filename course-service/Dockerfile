FROM openjdk
LABEL maintainer="abc@mail.com"
EXPOSE 8084
WORKDIR /app
COPY target/coursesevice.jar /app/courseservices.jar
ENTRYPOINT ["java", "-jar","courseservice.jar"]
