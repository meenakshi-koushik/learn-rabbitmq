# About

this is a starter project for learning rabbitMQ using Java Spring-AMQP.

# Setup

To open a development environment on your web-browser click:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/meenakshi-koushik/learn-rabbitmq)

Start rabbitmq on the workspace host, by running the command below (see [rabbitmq install instructions](https://www.rabbitmq.com/download.html) for more details):

```
RABBITMQ_CONFIG_FILE=/workspace/learn-rabbitmq/rabbitmq.conf \
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management
```

# To build and run tutorials

To build

```
mvn clean package
```

To run

```
java -jar target/learn*.jar
```
and follow the instructions output by it. For more details, refer [RabbitMQ Tutorials](https://www.rabbitmq.com/getstarted.html)
