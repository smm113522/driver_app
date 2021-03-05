# 添加 Java 8 镜像来源
FROM java:8
VOLUME /tmp
ADD driver_app-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
