# kafka-realtime-notify

[Source](https://morioh.com/a/88d30c12462f/build-a-real-time-notification-system-with-go-and-kafka)

## Development Environment

* macOS Ventura 13.5.1
* go@1.21.0 via Homebrew
* JetBrains GoLand 2023.2
* Docker Compose version v2.20.2-desktop.1

## Test

### Step 1：Run Kafka docker compose

```shell
docker compose up -d
```

### Step 2：Run Kafka producer

```shell
go run cmd/producer/producer.go
```

### Step 3：Run Kafka consumer

```shell
go run cmd/consumer/consumer.go
```
