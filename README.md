# Awesome-Enterprise-Message-Broker

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.



Here is the complete, ready-to-paste README.md for **Awesome-Enterprise-Message-Broker**.



---



# Awesome-Enterprise-Message-Broker



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Distributed Messaging, Event Streaming, Queue Semantics & Cloud-Native Pub/Sub*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Message Brokers**. These tools help organizations decouple services, stream events at scale, and build reliable asynchronous architectures across cloud and on-premises environments.



**Examples** include Azure Service Bus, RabbitMQ, Apache ActiveMQ, Amazon SQS, IBM MQ, Solace PubSub+, Google Cloud Pub/Sub, Redis Pub/Sub, IronMQ, and Anypoint MQ (the category leaders).



**Open-source emphasis**: The open-source message broker ecosystem is **exceptionally mature and production-proven**. **Apache Kafka** leads event streaming with the broadest connector ecosystem and Kafka 4.x KRaft architecture . **RabbitMQ** dominates traditional queuing with high reliability and flexible routing . **Apache Pulsar** provides native multi-tenancy and geo-replication with tiered storage . **NATS JetStream** offers lightweight, high-performance messaging with built-in deduplication . **Redpanda** delivers Kafka API compatibility in a single binary with lower operational complexity .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global message broker market is estimated at **~$15B in 2026**, growing toward **~$35B by 2032**. The sector is **moderately fragmented** — **Apache Kafka** dominates event streaming with the broadest ecosystem, while **RabbitMQ** leads traditional queuing, and **IBM MQ** and **Solace PubSub+** hold strong positions in regulated industries . **Pricing varies dramatically**: **Google Cloud Pub/Sub** charges per GiB for storage (**$0.27/GiB/month**) and per GiB for data transfer , **Amazon SQS** offers **1 million free requests per month** with pricing around **¥2.58–¥4.16 per million requests** in China regions , and **Azure Service Bus Premium** targets financial-grade reliability with five-nine uptime SLAs . **Solace PubSub+** reports **$80M messaging revenue** with **21.5% YoY growth** in 2024 . No single vendor holds a winner-take-all position; enterprises typically run multi-broker stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Azure Service Bus](https://azure.microsoft.com/en-us/products/service-bus/)** | **Microsoft's enterprise message broker.** Queues, topics, and subscriptions with advanced features like sessions, transactions, and duplicate detection. | **Standard**: **$0.05/million operations** + **$0.0135/hour** base. **Premium**: **$677/month** per messaging unit (1 unit = 1 CPU core, 1 GB memory). | **Azure free account**: **$200 credit for 30 days** + 12 months of free services. **No perpetual free tier** for Service Bus. | **~$281B revenue (Microsoft FY2025)**  |

| **[Google Cloud Pub/Sub](https://cloud.google.com/pubsub)** | **Google's fully managed messaging service.** Global scale with exactly-once delivery, snapshots, and dead-letter topics. | **Throughput**: **$0.04–$0.06/GiB** (first 10 GiB free). **Storage**: **$0.27/GiB/month**. **Data transfer**: **$0.01–$0.12/GiB** inter-region . | **Free tier**: **10 GiB/month** throughput, **10 GiB** storage. **Pub/Sub Lite was shut down June 30, 2026** . | **~$350B revenue (Alphabet FY2025)** |

| **[Amazon SQS](https://aws.amazon.com/sqs/)** | **AWS's fully managed queuing service.** Standard and FIFO queues with at-least-once and exactly-once processing. | **Standard**: **¥2.58–¥4.16/million requests** (China regions). **FIFO**: Higher rate. **Payload chunking**: Every 64 KB chunk = 1 request . | **Free tier**: **1 million requests/month** (all regions except GovCloud). **No perpetual free tier beyond that** . | **~$638B revenue (Amazon FY2025)** |

| **[Solace PubSub+](https://solace.com/)** | **Enterprise event mesh platform.** Appliance-level performance with unified on-prem and cloud deployment. | **Custom enterprise pricing** — quote required. **Migration packages**: **$50,000–$200,000** for legacy messaging migration . | **Free trial** available for PubSub+ Cloud. **No perpetual free tier** for enterprise. | **Private ($80M messaging revenue, 21.5% YoY growth)**  |

| **[IBM MQ](https://www.ibm.com/products/mq)** | **Enterprise messaging for mission-critical workloads.** Unmatched mainframe compatibility and broad integration toolset. | **Custom enterprise pricing** — quote required. **IBM MQ on Cloud**: Pay-as-you-go available. | **Free trial** available. **No perpetual free tier** for production. | **~$63B revenue (IBM FY2025)**  |

| **[Redis Pub/Sub](https://redis.io/)** | **In-memory publish/subscribe messaging.** Best-effort delivery with no persistence or retransmission. | **Redis Cloud Essentials Free**: **30 MB memory**. **Paid**: From **$5/month** for 250 MB . | **Free tier**: **30 MB memory**, **30 concurrent connections**, **5 GB/month bandwidth**, **100 ops/sec**. | **Private (~$2B valuation est.)** |



## 🔓 Open-Source GitHub Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[Apache Kafka](https://github.com/apache/kafka)** — **The de-facto standard for distributed event streaming.** Broadest connector ecosystem, Kafka Connect, Kafka Streams, and ksqlDB. **Kafka 4.0** removed ZooKeeper (March 2025); **KIP-932** share groups (queue semantics) GA in **4.2**. Latest stable: **4.3.1** (June 2026) . **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/apache/kafka?style=social&color=white)](https://github.com/apache/kafka/stargazers) | ~30,000 |

| **[NATS Server](https://github.com/nats-io/nats-server)** — **Lightweight, high-performance messaging system.** **JetStream** adds persistence, at-least-once delivery, and message deduplication . **Apache-2.0** . Ideal for cloud-native, IoT, and microservices architectures. | [![Stars](https://img.shields.io/github/stars/nats-io/nats-server?style=social&color=white)](https://github.com/nats-io/nats-server/stargazers) | ~17,000 |

| **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)** — **The most widely deployed open-source message broker.** Erlang-based with high reliability, flexible routing, and AMQP 1.0 support. **Durable messages** written to disk when persistence is specified . **MPL-2.0**. | [![Stars](https://img.shields.io/github/stars/rabbitmq/rabbitmq-server?style=social&color=white)](https://github.com/rabbitmq/rabbitmq-server/stargazers) | ~13,000 |

| **[Apache Pulsar](https://github.com/apache/pulsar)** — **Multi-tenancy and geo-replication as native features.** Compute/storage separation with Apache BookKeeper. **Native queue semantics** and topic isolation controls . **Apache-2.0**. **Note**: Kafka compatibility runs through a separate protocol handler, not native wire protocol . | [![Stars](https://img.shields.io/github/stars/apache/pulsar?style=social&color=white)](https://github.com/apache/pulsar/stargazers) | ~14,000 |

| **[Redpanda](https://github.com/redpanda-data/redpanda)** — **Kafka API compatible with single-binary deployment.** **Full Kafka protocol compatibility** — existing clients connect without code changes . Lower operational complexity than Kafka . **Community Edition** is free and source-available under **BSL** (converts to Apache 2.0 after 4 years); **Enterprise Edition** requires a license key . | [![Stars](https://img.shields.io/github/stars/redpanda-data/redpanda?style=social&color=white)](https://github.com/redpanda-data/redpanda/stargazers) | ~10,000 |

| **[Apache ActiveMQ Artemis](https://github.com/apache/activemq-artemis)** — **High-performance, non-blocking message broker.** Supports AMQP 1.0, MQTT, STOMP, and OpenWire. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/apache/activemq-artemis?style=social&color=white)](https://github.com/apache/activemq-artemis/stargazers) | ~1,000 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Apache RocketMQ](https://github.com/apache/rocketmq)** — Distributed messaging and streaming platform. **Apache-2.0**. |

| **[Apache ActiveMQ Classic](https://github.com/apache/activemq)** — The original ActiveMQ. **Apache-2.0**. |

| **[NSQ](https://github.com/nsqio/nsq)** — Realtime distributed messaging platform. **MIT**. |

| **[ZeroMQ](https://github.com/zeromq/libzmq)** — High-performance asynchronous messaging library. **MPL-2.0**. |

| **[NATS Streaming](https://github.com/nats-io/nats-streaming-server)** — Deprecated; use JetStream. |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Message brokers handle sensitive application data and event streams; ensure proper security configuration, encryption, and compliance with organizational policies.

- **Open-source reality**: The open-source ecosystem for enterprise message brokers is **exceptionally mature and production-proven**. **Apache Kafka** leads event streaming with the broadest connector ecosystem and **Kafka 4.x KRaft** architecture . **RabbitMQ** dominates traditional queuing with high reliability . **Apache Pulsar** provides native multi-tenancy and geo-replication . **NATS JetStream** offers lightweight, high-performance messaging with deduplication . **Redpanda** delivers Kafka API compatibility with lower operational complexity . However, **commercial platforms** (Azure Service Bus, Google Cloud Pub/Sub, Amazon SQS, IBM MQ, Solace) provide **managed infrastructure, enterprise SLAs, and dedicated support** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with strong platform engineering capacity.

- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Google Cloud Pub/Sub storage is $0.27/GiB/month** . **Amazon SQS offers 1 million free requests/month** . **Solace migration packages run $50,000–$200,000** . Always request a formal quote for accurate budgeting.



---



**Made for platform engineers, backend developers, SREs, and enterprise architects.**

Let's make enterprise messaging more open, transparent, and scalable.
