# Apache Kafka Overview

Apache Kafka is a publish-subscribe messaging system. A messaging system lets you send messages between processes, applications, and servers. Broadly Speaking, Apache Kafka is software where topics (a topic might be a category) can be defined and further processed. Applications may connect to this system and transfer a message onto the topic. A message can include any kind of information from any event on your blog or can be a very simple text message that would trigger any other event.

![Apache kafka](images/kafka-intro.png)

## Core Concepts

Kafka operates as a cluster of servers called brokers, which are managed by a master node called Zookeeper. These store and manage streams of records in categories known as topics. Each topic is partitioned, allowing data to be distributed, replicated, and processed across multiple brokers to achieve fault tolerance and scalability. Records in Kafka consist of a key, value, and timestamp, with each record assigned a unique offset for retrieval and replay.

- **Producer:** A topic is a category or feed name to which messages are published by producers. 
- **Consumer:** Consumers are applications that subscribe to Kafka topics and consume data from them. 
- **Broker:** Kafka servers that store topic data and manage client connections.
- **Topic:** Logical categories for streaming records, enabling organized data flow.
- **Partitions:** It's is a log of messages within a topic that is distributed across brokers, enabling a topic's data to be split and processed in parallel.
- **ZooKeeper:** ZooKeeper is a distributed coordination service that Kafka uses for cluster coordination, management, and configuration. It maintains the metadata about the Kafka brokers, topics, partitions, and consumer groups.


## Key Features

Apache Kafka offers the following collection of intuitive features:

- **Low latency:** Apache Kafka has an extremely low end-to-end latency, up to 10 milliseconds, for large volumes of data.
- **Seamless messaging functionality:** Due to its unique ability to decouple messages and store them effectively, Kafka has the ability to publish, subscribe, and process data records in Real-Time.
- **High Scalability:** It refers to a system’s capacity to sustain its performance when subjected to variations in application and processing demands.
- **High Fault Tolerance:** Kafka is very fault-tolerant and reliable since it duplicates and distributes your data often to other servers or Brokers.
- **Multiple Integrations:** Kafka can interface with a variety of Data-Processing Frameworks and Services, including Apache Spark, Apache Storm, Hadoop, and Amazon Web Services.


## Common Use Cases

- Real-time monitoring and analytics
- Event sourcing and log aggregation
- Microservices communication
- Data pipeline integration across systems

Kafka has become essential for modern data architectures, supporting millions of events per second with reliable delivery, flexibility, and robust fault tolerance.

## References

[Apache Kafka - GeeksForGeeks](https://www.geeksforgeeks.org/apache-kafka/apache-kafka/)

[Kafka Partitions: Essential Concepts for Scalability and Performance](https://www.datacamp.com/tutorial/kafka-partitions)

[Kafka Clusters Architecture 101: A Comprehensive Guide](https://hevodata.com/learn/kafka-clusters/)

[Apache Kafka 101: Partitioning](https://youtu.be/y9BStKvVzSs)

[Guide on Kafka – An open-source distributed streaming system](https://enhops.com/blog/guide-on-kafka-an-open-source-distributed-streaming-system)

***

<div align="center">⁂</div>