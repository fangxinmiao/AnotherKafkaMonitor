AnotherKafkaMonitor
===========

![Build Status](/WebContent/media/readmepic/build-passing.png)

## Preface
AnotherKafkaMonitor is an app which used to monitor kafka producer and consumer progress inspried by [KafkaOffsetMonitor](https://github.com/quantifind/KafkaOffsetMonitor). It aims to help you figure out what's going on in your kafka cluster, that's to say, to understand how fast the producer send message to the kafka or whether the consumer is far behind the producer or not, if lag exceeds threshold, you will be noticed through alarm email.

## Quick Look
Now, we are going to show you some screenshot of main featrues about [AnotherKafkaMonitor]()

### 1. DashBoard
Dashboard lists some general info:
* How many kafka ***Brokers, Topics, Zookeepers*** and ***Consumers*** you hava in cluster
![DashBoard](/WebContent/media/readmepic/akm-dashboard.png)

### 2. Topic List
* List Topics you have created
* List Partition Indexes of each topic
![Topic List](/WebContent/media/readmepic/akm-topiclist.png)

### 3. Cluster Info
* Kafka Broker List
* Zookeeper List
![Cluster Info](/WebContent/media/readmepic/akm-clusterinfo.png)

### 4. Consumers
* List how many consumer group you have
* The topic(s) consumed by each consumer group
* RealTime process rate about producer and consumer of one topic
![Consumers](/WebContent/media/readmepic/akm-consumers.png)
![Topic Detail](/WebContent/media/readmepic/akm-topicsdetail.png)
![Topic Realtime](/WebContent/media/readmepic/akm-realtime.png)

### 5. Alarm Configuration
* Alarm notice list
* Add alarm notice
![Alarm List](/WebContent/media/readmepic/akm-alarmadd.png)

### 6. Zookeeper Client
>Support simple shell comand, such as ls, get and delete
![Zookeeper Client](/WebContent/media/readmepic/akm-zkshell.png)
