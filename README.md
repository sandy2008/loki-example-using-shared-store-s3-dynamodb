# loki-example-using-shared-store-s3-dynamodb

This repository contains a configuration example to run Grafana [Loki](https://grafana.com/oss/loki/) with
[minio](https://github.com/minio/minio) and [dynamodb-local](https://hub.docker.com/r/amazon/dynamodb-local) using the Loki 2.0.0 to save both storage & index in S3.

## Getting Started

```bash
docker-compose up
```

You can access... 

- Grafana at http://localhost:3000/explore to explore logs.
- DynamoDB Admin at http://localhost:7777.

