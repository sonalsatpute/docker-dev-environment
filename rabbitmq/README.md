# Sample for Custom RabbitMQ

## Build

$ build docker build -t rabbitmq-dev .

## Start

$ docker run -p 15672:15672 --hostname my-rabbit --name rabbitmq-dev rabbitmq-dev

http://localhost:15672

username / password
admin / admin
