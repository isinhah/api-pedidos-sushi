# 🍣 Sistema de Pedidos de Sushi

---

## 📄 Descrição

Esse projeto foi desenvolvido para os clientes realizarem pedidos de sushi online. Com esta API, os clientes visualizam o cardápio, os produtos dentro de cada categoria e realizam os pedidos.

Para os funcionários, a API oferece ferramentas para gerenciar o cardápio e produtos, processar pedidos e administrar clientes.

---

## ⚙️ Funcionalidades

- **Visualização do cardápio**: Clientes podem navegar por categorias e produtos disponíveis.
- **Realização de pedidos**: Clientes podem criar e finalizar pedidos.
- **Gestão de cardápio**: Funcionários podem gerenciar categorias e produtos.
- **Processamento de pedidos**: Funcionários podem acompanhar e processar pedidos.
- **Administração de clientes**: Funcionários podem gerenciar informações dos clientes.

---

## 🗂️ Imagens do Projeto

<details>
    <summary><b>Categorias</b></summary>
    <img src="./media/categories.png" alt="Categorias">
</details>
<details>
    <summary><b>Produtos</b></summary>
    <img src="./media/products.png" alt="Produtos">
</details>
<details>
    <summary><b>Pedidos</b></summary>
    <img src="./media/orders.png" alt="Pedidos">
</details>
<details>
    <summary><b>Cliente</b></summary>
    <img src="./media/customer.png" alt="Cliente">
</details>

---

## 🛠️ Tecnologias

- **Linguagem**: Java
- **Framework**: Spring Boot
- **Gerenciador de Dependências**: Maven
- **Banco de Dados**: PostgreSQL
- **Migração de Banco**: Flyway Migrations
- **Segurança**: Java JWT
- **Testes**: JUnit, Mockito
- **Validação**: Spring Validation
- **Documentação da API**: SwaggerUI

---

## 📝 Endpoints

- **Documentação online**: https://sushi-ordering-system.onrender.com/swagger-ui/index.html
- **Documentação local**: http://localhost:8080/swagger-ui/index.html#/
- **Coleção com requisições HTTP**: [Collection](media/sushi_ordering_system_collection.json)

---

## 📈 Diagramas

<details>
    <summary><b>Diagrama de Classes</b></summary>
    <img src="./media/sushi-uml.png" alt="Diagrama de Classes" width=900>
</details>
<details>
    <summary><b>Diagrama de Entidade e Relacionamento</b></summary>
    <img src="./media/db-diagram.png" alt="Diagrama de Entidade e Relacionamento" width=800>
</details>

---

## ⚙️ Configuração e Execução

**Pré-requisitos**:

- Java 17
- Maven
- PostgreSQL

**Passos para Configuração**:

1. Clone o repositório
2. Acesse o diretório do projeto
3. Configure o banco de dados no arquivo `application.properties` (URL, usuário, senha)

```bash
# Execute a aplicação
mvn spring-boot:run

# Pressione (CTRL + C) para encerrar a aplicação
```

---

## 🙋‍♀️ Autor

👩‍💻 Projeto desenvolvido por [Isabel Henrique](https://www.linkedin.com/in/isabel-henrique/)

🤝 Fique à vontade para contribuir!
