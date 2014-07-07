Amazon Kinesis Source and Sink for Apache Flume

Build:

1. git clone
2. cd flume-kinesis
3. mvn compile assembly:single
4. cp target/\*.jar FLUME\_HOME\_DIR/lib
5. refer to one of the configuration samples in flume-kinesis/conf on how to configure Amazon Kinesis Sink and Source
