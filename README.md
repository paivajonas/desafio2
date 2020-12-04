# Desafio 2

## Detalhes
Utilizando Docker Compose, produza um ou mais docker-compose.yaml que provisione a infraestrutura necessária para subir um ambiente provisionado com Postgres, Python / Django e React, em suas últimas versões, resolvendo todas as dependências necessárias. Forneça um repositório Github com o arquivo e todas as orientações necessárias para a execução do ambiente no formato Readme.md

## Diretórios para a aplicação
1. Toda a aplicação executada pelo React deve ser inserida no diretório _react_.
* Os arquivos da aplicação serão copiados para o diretório _/home/react_ do container.

2. Toda a aplicação executada pelo Django deve ser inserida no diretório _django_.
* Os arquivos da aplicação serão copiados para o diretório _/home/django_ do container.

## Configurar e executar a aplicação
1. Para construir o ambiente da aplicação utilize o comando __docker-compose build__
2. Para executar o ambiente da aplicação utilize o comando __docker-compose up__

Após executar os comandos anteriores, o serviço deverá responder com endereço e portas abaixo:
* http://127.0.0.1:8000 é o aplicativo Django
* http://127.0.0.1:3000 é o aplicativo React
