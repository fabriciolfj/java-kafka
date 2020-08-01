# Java kafka


###### Kafka drop
```
java -jar kafdrop-3.27.0.jar kafka.brokerConnect=localhost:9092
```
###### Comandos kafka-cli
```
kafka-topics.sh --bootstrap-server localhost:9092 --create --partitions 3 --replication-factor 1 --topic getting started
``` 