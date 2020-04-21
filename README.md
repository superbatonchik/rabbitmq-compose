# RabbitMQ in docker-compose

## Setup
This setup assumes you already have docker-compose and docker (using docker toolbox) installed.

```
git clone git@github.com:superbatonchik/rabbitmq-compose.git
cd rabbitmq-compose
docker-compose up -d
```

## Usage
```
open http://$(docker-machine ip default):15672/
```
## Credentials

```
username: rabbitmq
password: rabbitmq
```

## License
MIT License
