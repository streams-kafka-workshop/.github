# Streams for Apache Kafka Workshop (This workshop is work in progress)

Welcome to the Streams for Apache Kafka Workshop! This GitHub organization serves as the central hub for all materials related to our hands-on training sessions on Apache Kafka, with a special focus on stream processing using Kafka Streams.

Workshop Overview

This workshop is designed to equip you with the knowledge and practical skills to effectively leverage Apache Kafka for event streaming and build robust stream processing applications. We'll cover a comprehensive set of topics, starting from the fundamentals and progressing to more advanced concepts, including real-world application integration and enterprise considerations like security and observability.

Workshop Modules

The workshop is divided into several key modules, each with dedicated repositories for code examples, exercises, and relevant resources.

1.  **Basics: Learning - CLI based**
    *   **Introduction to Event Streaming:** Understand what event streaming is, why it's crucial in modern architectures, and why Kafka excels in this domain.
    *   **Kafka Environment Overview:** Get familiar with the core components of a Kafka environment, including Operators, Clusters, Brokers, and the Console within OpenShift.
    *   **Topic, Producer, and Consumer Fundamentals:** Learn the core concepts of Kafka topics, producers, and consumers. You'll gain hands-on experience using CLI commands to create your first topic, produce messages, and consume them. We'll utilize multi-terminal setups for better visualization.
    *   **Partitions and Offsets:** Explore the importance of partitions for scalability and fault tolerance, and understand how offsets enable reliable message consumption and recovery.
2.  **Kafka Application: Producing and Consuming Messages using a Real-World App**
    *   **Introducing the Globex Application:** We'll use a simulated real-world application (Globex) to demonstrate practical Kafka usage.
    *   **Building Producers and Consumers:** Learn how to programmatically set up producers to send user activity or order data, and consumers to process it. We'll focus on demonstrating the creation of a producer and consumer for a new topic.
    *   **Consumer Groups:** Understand how consumer groups enable scalable and fault-tolerant message processing across multiple consumers.
    *   **Configuration Parameters:** Dive into essential Kafka configuration parameters for producers and consumers.
3.  **Stream Processing / Kafka Streams**
    *   **Introduction to Stream Processing:** Understand the concepts and benefits of real-time data processing.
    *   **Enriching Data with Kafka Streams:** Learn how to use the Kafka Streams API to process and analyze data in real-time, performing transformations and aggregations.
4.  **Kafka Ecosystem**
    *   **Schema Related Topics:**
        *   **Serialization and Deserialization (AVRO, Korxylicious):** Explore methods for efficient data serialization and deserialization, including schema validation.
        *   **Encryption:** Discuss considerations for data encryption in Kafka.
        *   **Schema Registry:** Understand the role and benefits of a Schema Registry for managing data schemas.
    *   **Connect to External Systems:**
        *   **Introduction to Kafka Connect:** Learn how Kafka Connect facilitates integration with various external systems.
        *   **Integrating with Debezium for CDC:** Get hands-on with Debezium for Change Data Capture (CDC), deploying connectors and understanding configurations. We'll explore how this integrates with our Globex application for use cases like a cashback application.
5.  **Security**
    *   **Configuring Authorized Access to Kafka:** Understand how to secure your Kafka environment.
    *   **Configuring User Security Mechanisms:** Explore authentication (SCRAM-SHA-512), authorization, ACL Rules, and Quotas. (Note: Some of these topics might be more relevant for administrators than developers).
6.  **Observability**
    *   **Introduction to Observability:** Learn about the importance of monitoring and understanding your Kafka ecosystem.
    *   **Console Walkthrough:** Get familiar with the Kafka Console for basic monitoring and management.
    *   **Prometheus / Grafana for Metrics:** Explore how to use Prometheus and Grafana for advanced metric collection and visualization in Kafka.
7.  **Kafka and AI (Introduction)**
    *   **Why Kafka is Important in the Context of AI:** Understand the role of Kafka in AI/ML pipelines for real-time data ingestion and processing.
    *   **MCP with Kafka:** (Further details to be added)
