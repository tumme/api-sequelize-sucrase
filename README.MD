<p align="center">
  <img width="115" height="100%" src="https://www.elemental.co.za/blog/wp-content/uploads/2020/04/api-2x.png" alt="API RESTful"></a>
</p>

<h3 align="center">API RESTful - MySQL Sequelize :: Sucrase</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

## Apresentação:

Projeto BackEnd: API RESTful seguindo conceito **MVC** utilizando Stack **NodeJS**, padronizado o código com **Eslint** e **Prettier**.

Pacotes principais: **Express** responsável pela criação de rotas, Middleware **JWT** para persistência do token por 30minutos, mantendo a segurança e credêncial do usuário, ORM **Sequelize** para conexão com banco de dados relacional (**MySQL**) e por fim, **Jest** para realização de tests.

Rotas mapeada do arquivo exportado Insominia: `Insomnia.json`

## Requisitos

#### Routes

- [x] Criar usuário

```java
router.post('/users', UserController.store)

{
     "name": "Caio",
     "email": "caio@gmail.com",
     "password": "123123"
}
```

- [x] Logar sessão

```java
router.post('/users', UserController.store)

{
     "email": "caio@gmail.com",
     "password": "123123"
}
```

## Contato

- [LinkedIn](https://www.linkedin.com/in/caioagiani/)
- caio.agiani14@gmail.com