# Samarth Tikotkar

**Engineering Student | Backend, Cloud & Distributed Systems**

I build distributed systems, focusing on architecting scalable, production-grade microservices and custom database engines. My engineering work is driven by a core technology stack of Java and Spring Boot, combining rigorous backend development with active contributions to open-source software and cloud infrastructure.

I am currently pursuing a B.Tech in Electronics at MIT Academy of Engineering, Pune, with an expected graduation in July 2027. 

I place a strong emphasis on advanced algorithmic problem-solving and system design, maintaining a 1600+ rating on LeetCode with over 450 problems solved.



---

## Open Source Contributions

### [Floci](https://github.com/floci-io/floci) (Local Cloud Emulator)
*   **ECS Lifecycle & Terraform Parity** [Pull Request](https://github.com/floci-io/floci/pull/1166)

Engineered strict AWS parity for ECS service lifecycle management by retaining INACTIVE state markers and ensuring deep structural equality verification for idempotent REST requests. This resolved critical idempotency failures and unhandled ARN parsing errors, stabilizing Terraform destroy-and-recreate workflows.

*   **EC2 Network Interface Serialization** [Pull Request](https://github.com/floci-io/floci/pull/1214)

Fixed the omitted `<attachTime>` element in the EC2 `describe-instances` XML response. Added safe serialization and timestamp tracking to the emulator's `InstanceNetworkInterface`, aligning output with real AWS behavior and preventing deserialization crashes for IaC tools.

---

## Featured Projects

### [JKeyDB](https://github.com/someear9h/JKeyDB) (NoSQL Database Engine)
*   Architected a production-grade NoSQL database engine in Java from scratch, modeled on DynamoDB's partition keys, sort keys, and durability design.
*   Engineered a custom Write-Ahead Log (WAL) with startup replay, surviving all crash scenarios with zero data loss.
*   Designed composite key storage enabling range queries at `O(log n)` versus `O(n)` full scans, achieving sub-millisecond response times on partitions with over 10,000 items via a Spring Boot REST API.

### [Patient Data Orchestrator](https://github.com/someear9h/Patient-Data-Orchestrator) (Microservices)
*   Architected a 5+ service microservices system utilizing Spring Boot and an API Gateway, secured with JWT and Spring Security to block unauthorized requests.
*   Cut inter-service latency to ~20ms (5x faster than standard REST) via gRPC implementation.
*   Processed 10,000+ patient events per hour at 99% reliability using Kafka, supported by a comprehensive RestAssured and JUnit integration test suite.
*   Designed the architecture for independent scalability with zero single points of failure and streamlined one-command Docker deployments.

---

## Technical Skills

*   **Languages:** Java, Python
*   **Backend Development:** Spring Boot, REST APIs, gRPC, API Gateway, JWT Authentication, Kafka
*   **Databases:** MySQL, PostgreSQL, DynamoDB
*   **Tools & Platforms:** Git, GitHub, Docker, Postman, IntelliJ IDEA, VS Code

---

## Achievements

*   **1st Place:** Hack Matrix 4.0 (ARTIMAS 2026, GeeksforGeeks Campus Body, PCCOE) - Led a team of 3 in a 24-hour hackathon, winning the Miscellaneous track.
*   **Winner:** TechSprint Open Innovation Hackathon 2026 (Google Developer Groups on Campus, MITAOE) - Led team "Qore" to first place.

---

**More of me:** [LinkedIn](https://www.linkedin.com/in/samarth-tikotkar-7532b0328/) | [LeetCode](https://leetcode.com/u/someear1h/) 
