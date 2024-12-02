## Run the Script Below to Create Kafka Topic

```sh

sudo docker exec broker kafka-topics --bootstrap-server broker:9092 --create --replication-factor 1 --partitions 1 --topic logstash
sudo docker exec broker kafka-topics --bootstrap-server broker:9092 --create --replication-factor 1 --partitions 1 --topic zipkin

```