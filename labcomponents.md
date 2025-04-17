| Layer          | Component                         | Note |
|---------------|----------------------------------|------|
| **Microservice**  | Simple UI                        | Python |
|               | Simple UI Backend                | Python |
|               | Consumer or Microservice 2       | Golang |
| **Infrastructure** | Kubernetes                      | Deploying on GKE |
|               | MongoDB                          | MongoDB Atlas |
|               | Kafka Cluster                    | Strimzi Kafka Operator |
|               | Kafka Connect                    | — |
|               | *(Optional)* Conduktor             | UI for Kafka |
|               | *(Optional)* PostgreSQL            | Percona PostgreSQL Operator |
|               | *(Optional)* ELK or O2             | Using O2 due to promising compression ratio and big data adaptation |
|               | *(Optional)* Open Telemetry Stack  | For end-to-end tracing |
|               | *(Optional)* Prometheus/Victoriametric Stack | — |
|               | *(Optional)* Keda Scaler           | Performance scaling in production |