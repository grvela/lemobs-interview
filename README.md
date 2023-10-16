# Como Executar o Projeto

  

Este guia descreve como executar o projeto, incluindo instruções para o backend e o frontend.

## Backend

1. Navegue até a pasta do backend:

    cd backend

2. Inicie o projeto usando o Docker Compose para configurar o ambiente:

    docker-compose up

Isso iniciará o backend, incluindo o servidor NestJS e o banco de dados PostgreSQL.

3. Instale as dependências do Node.js:

    npm install

4. Inicie o servidor NestJS:

    npm run start  

5. Execute as migrações do banco de dados:
  
    npm run migration:run


Agora, o backend deve estar em execução e pronto para aceitar solicitações.
  

## Frontend

1. Navegue até a pasta do frontend:

    cd frontend

2. Instale as dependências do Node.js:

    npm install

3. Inicie o servidor de desenvolvimento para o frontend:

    npm run start

Isso iniciará o frontend e você poderá acessá-lo em um navegador em http://localhost:3000 (ou em outra porta, dependendo da configuração).


Certifique-se de que o backend esteja em execução e configurado corretamente para que o frontend possa interagir com ele.



