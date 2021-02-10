# Messaging Queues
A Messaging queue also simply known as a queue is a specified location where messages are sent. Messages accumulate in the queue until the system or process that service those queues recover them. It is different from the shared memory in the sense that multiple processes can access the data in shared memory but in a messaging queue once the message is received by a process it will no longer be available for other processes. There are client application called producers that create messages and deliver them to the messaging queue. Another application called consumer connects to the queue and processes them.

##### Use Of Messaging Queue
- Better Performance -- Messaging queue uses asynchronous communication which means that producer and consumer don't need to interact with each other but with the queue resulting in a better performance.
- Increased Reliability -- By separating different components with messaging queue we establish more fault tolerance. Even if some part of the system fails other parts can still function and interact with the queue.
- Granular Scalability -- Messaging Queues allow us to scale accurately where we need to. At the time of high load, multiple instances of our application can add requests to the queue without the danger of a crash.
- Simplified Decoupling -- By eliminating dependencies between different components after which even parts of code written in other programming languages can be useful to process the transaction.

##### Some Popular Tools 
Some Popular tools for the implementation of Messaging Queues are
- Apache Kafka
- RabbitMQ
- Celery 
- IBM MQ
- Amazon SQS
- MSMQ
- Amazon MQ

##### Enterprise Service Bus

Enterprise Service Bus(ESB) is a type of architecture. It is a set of rules and standards where we connect different components or applications on a common communication bus, and each component has endpoints to communicate with the bus. ESB is useful when we have to integrate a large no of applications because in such a scenario point-to-point integration becomes hard to manage and troubleshoot. ESB architecture is more agile and easy to scale. In conclusion, ESB is a service-oriented paradigm to facilitate and allow heterogeneous environments to interoperate.

###### Referecces
[Ref-1] https://www.oracle.com/technical-resources/articles/middleware/soa-ind-soa-esb.html
[Ref-2] https://stackshare.io/message-queue
[Ref-3] https://www.ibm.com/support/knowledgecenter/SSFKSJ_8.0.0/com.ibm.mq.pro.doc/q002620_.html
