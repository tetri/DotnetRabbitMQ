Comando para iniciar a instância do RabbitMQ no docker:

```
docker run -d --hostname localhost --name rabbitmq3 -e RABBITMQ_DEFAULT_USER=tetri -e RABBITMQ_DEFAULT_PASS=tetri -p 5672:5672 -p 8080:15672 rabbitmq:3-management
```

É possível acessar o gerenciamento do RabbitMQ no endereço http://localhost:8080, utilizando os dados de acesso indicados em `RABBITMQ_DEFAULT_USER` e `RABBITMQ_DEFAULT_PASS`.
