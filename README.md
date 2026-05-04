# Learning RabbitMQ: Efficient Message Queuing

This repository contains my notes, exercises, and practice code from the LinkedIn Learning course **"Learning RabbitMQ: Efficient Message Queuing"** by Peter Morlion. It serves as a personal reference for building message-based systems with RabbitMQ.

 
Successfully completed the course.
 
**[View My Certificate](https://www.linkedin.com/learning/certificates/e7d9723d1fa72890df787c8fc17825a9d036e67cdd18b0b5e7d268d71c37d119?trk=share_certificate)**

## Skills & Concepts Learned

Understanding the difference between **RPC-style communication** and **message-based architecture**
- Role of a **message broker** in decoupling services
- Working with **AMQP 0-9-1**, the core protocol behind RabbitMQ

Hands-on practice with all four exchange types and their routing behavior:
 
| Exchange Type | Use Case |
|---|---|
| **Fanout** | Broadcast messages to all bound queues |
| **Direct** | Route by exact match on routing key |
| **Topic** | Route by pattern matching with wildcards |
| **Headers** | Route based on message header attributes |


- Publishing messages to a RabbitMQ exchange
- Consuming messages from a queue
- Filtering messages using direct, topic, and headers exchanges