## Questions from CCDAK Exam

### Kafka Theory
- Kafka is a ... ? 
  + publish-subscribe messaging system.
- In which language is Kafka written?
  + A: **Scala**
  + B: Groovy
  + C: Python
  + D: Groovy
- What is referred to as a broker in Kafka? 
  + A: Subscriber
  + B: **Server**
  + C: Zookeeper
  + D: Message
- In Kafka, every broker… (select three)
  + A: contains all the topics and all the partitions
  + B: **contains only a subset of the topics and the partitions**
  + C: **knows all the metadata for all topics and partitions**
  + D: knows the metadata for the topics and partitions it has on its disk
  + E: **is a bootstrap broker**
  + F: is a controller
- If a topic has a replication factor of 3…
  + A: **Each partition will live on 3 different brokers**
  + B: Each partition will live on 2 different brokers
  + C: Each partition will live on 4 different brokers
  + D: 3 replicas of the same data will live on 1 broker
- Your manager would like to have topic availability over consistency. Which setting do you need to change in order to enable that?
  + A: min.insync.replicas
  + B: compression.type
  + C: **unclean.leader.election.enable**

### Kafka Streams 
- Which of the Kafka Stream operators are stateful ?
- Which of the Kafka Stream operators are stateless ?
- Which window is not having gap ?
- You want to perform table lookups against a KTable every time a new record is received from a KStream. What is the output of KStream-KTable join?
	+ **_A: KStream_**
	+ B: KTable
	+ C: GlobalKTable
	+ D: You choose between KStream or KTable

### Confluent Schema Registry 
- Which of the following is not a primitive type of Avro ?
- Which of the following in not a complex type of Avro?
- Which of the following is not a required field in Avro Schema?
- Delete a field without default value in Avro schema is ...... compatibility? 
- Using the Confluent Schema Registry, where are Avro schema stored?
	+ A: In the Schema Registry embedded SQL database
	+ B: **In the _schemas topic**
	+ C: In the message bytes themselves
	+ D: In the Zookeeper node /schemas
