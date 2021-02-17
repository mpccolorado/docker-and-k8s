FROM openjdk:8-jre-slim
COPY build/libs/*.jar application.jar
EXPOSE 4444
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "application.jar"]
