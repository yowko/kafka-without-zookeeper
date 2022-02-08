# Create Kafka via docker compose

## Introduction

It's possible to run Kafka without ZookKeeper. You can get more information from [KRaft mode ((aka KIP-500)](https://github.com/apache/kafka/blob/3.1/config/kraft/README.md).

I think it's great to run Kafka without ZookKeeper via docker-compose.

## How to run

```bash
docker-compose up -d
```

## Warning

The latest Kafka version is 3.1.0. KRaft is currently PREVIEW AND SHOULD NOT BE USED IN PRODUCTION
