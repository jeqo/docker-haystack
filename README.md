```
kafka-topics --zookeeper localhost:2181 --create --topic proto-spans --replication-factor 1 --partitions 1
kafka-topics --zookeeper localhost:2181 --create --topic metricpoints --replication-factor 1 --partitions 1
kafka-topics --zookeeper localhost:2181 --create --topic mdm --replication-factor 1 --partitions 1
kafka-topics --zookeeper localhost:2181 --create --topic graph-nodes --replication-factor 1 --partitions 1
kafka-topics --zookeeper localhost:2181 --create --topic service-graph --replication-factor 1 --partitions 1
```
