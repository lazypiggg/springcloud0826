FROM java:8-jdk

FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

CMD ["mkdir", "/app"]
ADD ./target/serviceb2-1.0.0.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/serviceb2-1.0.0.jar"]

EXPOSE 7078
