# Projeto de Votação

## Visão Geral

Este projeto é uma aplicação de votação desenvolvida com o uso de Nest.js para o backend (API) e Angular para o frontend (web). Ele oferece uma maneira interativa e moderna de gerenciar votações online.

Confira o projeto em ação no ambiente de produção:
[https://votacao.ivanfuhr.com/](https://votacao.ivanfuhr.com/)

## Configuração do Ambiente

### Pré-Requisitos

- Docker
- Docker Compose

### Modo de Desenvolvimento

Para executar o projeto em modo de desenvolvimento, é necessário ter uma instância do banco de dados PostgreSQL. Uma imagem do PostgreSQL já está definida no arquivo `docker-compose.development.yml`. Siga os passos abaixo para configurar o ambiente de desenvolvimento:

1. Inicie o serviço de banco de dados usando Docker Compose:

   ```sh
   docker compose -f docker-compose.development.yml up -d
   ```

2. Configure as variáveis de ambiente necessárias para cada serviço. Você encontrará os detalhes necessários dentro da pasta de cada serviço.

### Modo de Produção

Para executar o projeto em um ambiente de produção, utilize o arquivo `docker-compose.production.yml`:

1. Inicie os serviços com o seguinte comando:

   ```sh
   docker compose -f docker-compose.production.yml up -d
   ```

2. Assim como no modo de desenvolvimento, configure as variáveis de ambiente conforme necessário para cada serviço.

## Documentação Adicional

Para mais informações sobre a configuração e utilização do projeto, consulte a documentação presente nas pastas de cada serviço.
