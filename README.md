# Igor Novak

_Senior Backend Engineer & Team Lead | 9+ Years Experience_

igor.novak.work@gmail.com · +4915510626032 · GMT+2 · [WhatsApp](https://wa.me/4915510626032) · [LinkedIn](https://linkedin.com/in/igor-novak-dev) · [GitHub](https://github.com/igor-novak)

## About Me

Results-driven Senior Backend Developer and Team Lead with over 9 years of hands-on experience specializing in architecting, scaling, and maintaining fault-tolerant, high-load distributed systems using Go (Golang). Possess deep technical expertise in cloud-native microservices, event-driven architectures (Apache Kafka, NATS, RabbitMQ), gRPC high-performance communication, and database optimization (PostgreSQL, ClickHouse, Cassandra, Redis).

Proven track record of technical leadership, mentoring cross-functional engineering teams, enforcing engineering standards (TDD, CI/CD, Observability), and driving infrastructure availability to 99.99% while handling 120K+ RPS. Passionate about designing resilient, secure, and high-throughput backend ecosystems that solve complex business challenges and dramatically accelerate time-to-market.

## Skills

- **Languages**: Go, Python, SQL
- **Databases & Caching**: PostgreSQL, ClickHouse, Cassandra, MongoDB, Redis, Memcached, Elasticsearch, etcd
- **Messaging & Streaming**: Apache Kafka, NATS JetStream, RabbitMQ, AWS SQS/SNS
- **Cloud & DevOps**: AWS, GCP, Kubernetes (K8s), Docker, Terraform, Helm, GitLab CI/CD, GitHub Actions, Linux
- **Observability & Tooling**: Prometheus, Grafana, OpenTelemetry, Jaeger, ELK, pprof
- **Architecture & Paradigms**: Microservices, Highload, Event-Driven Architecture, Domain-Driven Design (DDD), Clean/Hexagonal Architecture, Distributed Systems, gRPC, REST API, GraphQL, WebSockets

## Education
Saint Petersburg State University of Telecommunications — Bachelor, Computer Science and Engineering (Sep 2012 – Jun 2016)
Saint Petersburg State University of Telecommunications — Master, Information Systems and Technologies (Sep 2016 – Jun 2018)

## Experience

### Nexo — Lead Developer / Team Lead (Golang) (Sep 2024 – Present)

**High-Throughput Real-Time Crypto Trading & Liquidity Aggregator**

- Spearheaded an engineering team of 9 backend developers to architect a high-throughput crypto liquidity aggregator in Go using gRPC and Apache Kafka, achieving seamless order execution under peak loads of **120,000 RPS with sub-10ms latency**.

- Engineered a concurrent trade settlement microservice in Golang featuring atomic database transactions in PostgreSQL and in-memory locking via Redis, processing **$50M+ in daily payouts with zero double-spend**.

- Designed custom Kubernetes Operators in Go (kubebuilder) to automate multi-region cluster failover and database backups, **cutting downtime by 99.9%**.

- Optimized critical hot paths in the transaction validation pipeline using Go pprof and memory allocation tuning, **cutting CPU usage by 45% and GC pauses by 60%** across 200+ Kubernetes pods.

- Architected an end-to-end distributed tracing and observability pipeline with OpenTelemetry, Prometheus, Jaeger, and Grafana across 30+ microservices, slashing MTTR of production incidents **from 2 hours to under 12 minutes**.

- Established standardized engineering practices including strict golangci-lint rules, automated integration testing, and CI/CD pipelines in GitLab CI, increasing unit test coverage to 94% and accelerating production deployment frequency **from bi-weekly to 4 times per day**.

**Technologies Used:** Go (Golang), PostgreSQL, Apache Kafka, Redis, gRPC, Kubernetes, Docker, OpenTelemetry, Prometheus, Grafana, Jaeger, GitLab CI/CD, Linux.

[https://nexo.com](https://nexo.com)

### Replicate — Senior Golang Developer (Jul 2022 – Sep 2024)

**High-Performance AI Model Execution & Worker Dispatcher Engine**

- Developed a core worker orchestration engine in Go using NATS JetStream and Redis Streams to dispatch AI inference tasks across thousands of GPU instances, achieving dispatch latencies **under 5ms at 80,000 requests per minute**.

- Architected a high-performance streaming file artifact service in Golang leveraging concurrent chunked uploads to AWS S3 and GCP Cloud Storage, **cutting 10GB+ model download times by 70%**.

- Implemented a multi-tier rate limiting and quota enforcement middleware in Go using Token Bucket algorithms and Redis Cluster, shielding the platform against DDoS traffic surges up to 100K RPS while maintaining **99.99% availability**.

- Refactored legacy monolithic services into Clean Hexagonal Architecture Go microservices with gRPC communication, eliminating tight coupling and cutting developer onboarding time by 50% while **boosting API throughput by 3x**.

- Optimized heavy analytical queries and indexes in PostgreSQL and ClickHouse for historical usage tracking, reducing analytics dashboard query response times **from 15 seconds to 350ms**.

- Constructed a custom distributed lock manager on top of etcd in Go, ensuring race-condition-free GPU resource allocation and **saving $180,000 a year** on underutilized cloud infrastructure.

**Technologies Used:** Go (Golang), NATS JetStream, Redis, PostgreSQL, ClickHouse, AWS S3, GCP, gRPC, etcd, Docker, Kubernetes.

[https://replicate.com](https://replicate.com)

### CrowdStrike — Golang Developer (Mar 2019 – Jul 2022)

**Real-Time Endpoint Threat Telemetry & Event Ingestion Pipeline**

- Designed and deployed a high-scale event ingestion pipeline in Go processing **>1.5 million events per second at under 50ms** using Apache Kafka and worker pool patterns.

- Developed a high-speed telemetry indexing service in Golang integrated with Elasticsearch and Cassandra, enabling security analysts to search **100+ TB of threat data in under a second**.

- Built an asynchronous threat detection rule evaluator in Go using custom goroutine pools and channels, **increasing pattern-matching throughput by 400%**.

- Integrated gRPC and Protocol Buffers for high-performance low-latency internal transport between 15+ telemetry processing microservices, **cutting network bandwidth by 65%** compared to legacy JSON/REST calls.

- Automated disaster recovery and zero-downtime database migrations for PostgreSQL clusters containing 500M+ records using Go migration tooling and Docker, ensuring **zero data loss** during major schema upgrades.

- Constructed a real-time health and metric monitoring agent in Go with Prometheus exporters, tracking 50K+ host nodes and **detecting host-agent anomalies 80% faster**.

**Technologies Used:** Go (Golang), Apache Kafka, Cassandra, Elasticsearch, PostgreSQL, gRPC, Protobuf, Prometheus, Docker, Kubernetes, Linux.

[https://crowdstrike.com](https://crowdstrike.com)

### Snowplow — Golang Developer (May 2017 – Mar 2019)

**Real-Time Behavioral Data Enrichment & Event Validation Engine**

- Architected a high-performance HTTP API gateway in Go for real-time behavioral event validation and enrichment, handling **25,000 RPS with latency under 20ms**.

- Developed an asynchronous enrichment worker pool in Go on RabbitMQ to transform and fan out validated events, processing **over 50 million events a day** with zero queue backpressure.

- Engineered an in-memory cache for enrichment reference data on Memcached and Redis in Go, reducing lookup times **from 120ms to 4ms**.

- Built a concurrent log parsing and ETL pipeline in Go with goroutines and channels, cutting preprocessing of 5TB+ raw event logs for Data Science teams **from 36 hours to 4 hours**.

**Technologies Used:** Go (Golang), Python, PostgreSQL, RabbitMQ, Memcached, Redis, REST API, Docker, AWS.

[https://snowplow.io](https://snowplow.io)
