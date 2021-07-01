# Vaga Backend Ruby on Rails

## Sobre a vaga

Estamos em busca de desenvolvedores Ruby on Rails para compor nosso time de backend, também será bem vindo desafios feitos em NodeJS e Typescript. Vamos conversar?

[Agendar entrevista](https://meetings.hubspot.com/sidnei-pacheco)

**Requisitos:**

- Conhecimento de Ruby on Rails
- Conhecimento de HTML, CSS e JavaScript
- Experiência de implementação de testes unitários
- Conhecimento de Git e gostar de colaborar via pull requests
- Conhecimento de SQL. PostgreSQL é um diferencial
- Consumo de APIs
- Sidekiq

## Sobre a SEUGURU

Nascemos uma insurtech com o objetivo de desburocratizar os beneficios para os profissionais autonomos.

Venha fazer parte do nosso time!

## Sobre o desafio

Criar um sistema para consumir a [API da Marvel](https://developer.marvel.com/) importar as historias e personagens.

O mesmo sistema, deve importar e possuir endpoints para listar as historias seus personagens, cadastro de usuário para consumir os items importados.

DICA: Um personagem pode pertencer a mais de uma historia.

## ENDPOINTS disponiveis

[GET] /stories

[GET] /characters

[POST] /users
```json
{
  "email": "user@user.com.br",
  "password": "password123"
}
```


[POST] /auth
  
  Request
```json
{
  "email": "user@user.com.br",
  "password": "password123"
}
```
  Response
  ```json
  {
    "email": "user@user.com.br",
    "token": "token"
  }
  ```

**Lista de atributos**
https://developer.marvel.com/documentation/entity_types

### PLUS

 - Adicionar autenticação via token para consumir a API
 - Adicionar endpoints para criação do hitorias e personagens via POST.
 - Testes unitários


## Dúvidas 

Em Caso de dúvidas estamos a disposição,
sidnei.pacheco@seuguru.com.br



