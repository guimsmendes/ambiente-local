## 1 - Instale o Docker Compose na URL abaixo:

https://docs.docker.com/compose/install/

## 2 - Suba o ambiente local na sua máquina (RabbitMQ, Kafka, MongoDB e ElasticSearch) rodando o docker-compose.yml em anexo. 

* Na CLI, cesse o repositório em que está salvo o docker-compose.yml e utilize os comandos:

> docker-compose build
> docker-compose up

Tenha certeza que as portas 2181 e 9092 (Kafka), 5672 e 15672(RabbitMQ), 9200 e 9300 (ElasticSearch) e 27017 (MongoDB) estão disponíveis.

## 3 - Atualize o application.yml da sua aplicação.

* Utilize o application.yml de exemplo para configurar as conexões com o RabbitMQ, MongoDB e ElasticSearch.

* Atualize o nome da aplicação.

* Inclua todas as demais variáveis de ambiente que sua aplicação esteja utilizando.

> Sugiro fazer uma varredura código para garantir que nenhuma variável de ambiente esteja faltando.

## 4 - Delete ou comente o bootstrap.yml da sua aplicação.

## 5 - Rode sua aplicação.
