gs-messaging-rabbitmq

Проверка связи по Rabbit MQ

Для теста нужно установить докер и установить Rabbit MQ:
docker pull rabbitmq

И запустить:
docker run -d --hostname my-rabbit --name some-rabbit rabbitmq:3