# portfolio-DSMeta

Curso Semana Spring React -- Dev Superior
- https://devsuperior.com.br/
- https://github.com/devsuperior/sds-dsmeta

Distribuições gratuitas do java jdk:
- Java JDK adopt
- Java JDK Zulu

## Ferramentas Auxiliares:
- Figma: Site que auxilia montar o design da aplicação, desde o tamanho dos elementos até exportar as imagens.
- Sring initializr: Site que cria o Spring Boot Initializr com os parametros determinados para facilitar a configuração.
  - https://start.spring.io/
- vitejs: Ferramenta pratica para criar projetos.

## Links do Figma com o design da aplicacao:
- https://www.figma.com/file/UDJ31giDzSQGkTP6AuAFtK/DSMeta2-(Copy)?node-id=0%3A1

## Comandos:
- `java -version` ==> Verifica as versões do java instaladas
- `node -v` ==> Checa a versão do nodeJS instalado
- `yarn -v` ==> Checa a versão do nodeJS instalado
- `npm install --global yarn` ==> Instala o gerenciador de pacotes Yarn
- `yarn create vite frontend --template react-ts` ==> Cria o projeto react com o template usando typescript na pasta frontend usando a ferramenta **vite**
- `yarn start` ==> Executa o projeto
- `yarn dev` ==> Executa o projeto como desenvolvedor.
- `yarn add react-router-dom@6.2.1 @types/react-router-dom@5.3.2` ==> Instalação da biblioteca que ajuda na construção das rotas dentro do site

## Anotações:
- Segmentação de criação do projeto:
  - Frontend:
    - Implementação:
      - HTML;
      - CSS;
      - Javascript / Typescript;
      - React;
    - Hospedagem:
    - Link: 
  - Backend:
    - Implementação:
      - Java (versão 17 -- Azul Zulu Builds of OpenJDK);
      - Spring Boot (STS v4.13.0);
      - PostgreSQL 12 e pgAdmin 4 (Banco de dados);
    - Hospedagem:
      - Heroku;
    - Link: 
  - Outras ferramentas:
    - Git (Versionamento do projeto);
      - Armazenado no github;
    - Postman (Utilizar envios REST com HTTP para testar a aplicação);
    - VSCode (Editor de texto);
- Configuração no spring initializr:
  - Maven Project
  - Java
  - Spring Boot: 2.7.1
  - Group: `com.devsuperior`
  - Artifact: `dsmeta`
  - Name: `dsmeta`
  - Description: `Projeto da Semana Spring React Devsuperior`
  - Package name: `com.devsuperior.dsmeta`
  - Dependencies:
    - Web
    - JPA
    - H2
    - Security
- Importação dentro do Spring Tool Suite:
  - Maven/Existing Maven Project
  - pasta do backend do projeto