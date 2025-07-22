# order-service
Microserviço para ordem de serviço

# Info
- Linguagem: Java 21
- Framework: Spring Boot 3.5.3
- Gerenciador de dependências: Maven

# Setup
- Clone o repositório
- Baixe as depêndencias ``$ mvn install``
- Rode o projeto ``$ mvn spring-boot:run``
- Acesse: http://localhost:8081/ para verificar se a aplicação está rodando

# RabbitMQ
- Subir a instacia da imagem rabbitmq: ``docker-compose up -d``
- Checar a porta http://localhost:15672
  
# Banco de dados
PostgreSQL
