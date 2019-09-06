# nodejs-rabbitmq-demo

1. Start rabbitmq docker
docker run -d --hostname my-rabbit --name some-rabbit -p 15673:15672 -p 5672:5672 rabbitmq:3.7-management