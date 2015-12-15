FROM java:7

COPY Helloworld.java /
RUN javac Helloworld.java

ENTRYPOINT ["java", "Helloworld"]
ENV FOO bar
