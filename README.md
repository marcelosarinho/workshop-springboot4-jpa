# Workshop Spring Boot + JPA

Projeto desenvolvido para estudo de **Spring Boot 4**, **Spring Data JPA** e **Hibernate**, implementando uma **API RESTful** com persistência de dados em banco relacional.

A aplicação utiliza **H2 Database para ambiente de desenvolvimento** e possui suporte a **PostgreSQL**, seguindo uma arquitetura em camadas com **Controllers, Services e Repositories**.

---

## 🚀 Tecnologias Utilizadas

- **Java 25**
- **Spring Boot 4.0.3**
- **Spring Web MVC** (criação da API REST)
- **Spring Data JPA** (camada de persistência)
- **Hibernate ORM** (implementação JPA)
- **Maven** (gerenciamento de dependências)
- **H2 Database** (banco em memória para desenvolvimento)
- **PostgreSQL** (banco relacional para ambiente real)
- **jBCrypt** (criptografia de senhas)

---

## 📚 Conceitos Praticados

Neste projeto foram aplicados conceitos essenciais do ecossistema Spring:

- Criação de APIs REST
- Arquitetura em camadas
- Persistência de dados com **Spring Data JPA**
- Mapeamento objeto-relacional com **Hibernate**
- Relacionamentos entre entidades
- Serialização JSON com Jackson
- Configuração de banco de dados em memória
- Seed inicial de dados para testes
- Criptografia de senha com **BCrypt**

---

## 🏗 Arquitetura do Projeto

O projeto segue a arquitetura comum em aplicações Spring Boot:

Controller (Resource)\
↓\
Service\
↓\
Repository\
↓\
Database
