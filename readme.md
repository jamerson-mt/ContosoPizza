# ContosoPizza API

Esta é uma API de exemplo criada com **ASP.NET Core**, seguindo o tutorial do **Microsoft Learn**. A API permite gerenciar uma pizzaria, incluindo operações de CRUD para pizzas e gerenciamento de pedidos de clientes.

## Índice

- [Introdução](#introdução)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Começar](#como-começar)
- [Endpoints da API](#endpoints-da-api)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Introdução

A API **ContosoPizza** foi criada como parte do aprendizado da plataforma **ASP.NET Core** e demonstra funcionalidades básicas de uma aplicação de back-end, com operações de criação, leitura, atualização e exclusão (CRUD).

## Funcionalidades

- Criar, visualizar, atualizar e deletar pizzas.
- Listar pizzas disponíveis.

## Tecnologias Utilizadas

- **ASP.NET Core** - Framework para o desenvolvimento da API.


## Como Começar

### Pré-requisitos

- [.NET SDK](https://dotnet.microsoft.com/download) instalado.
- Um editor de código, como o [Visual Studio Code](https://code.visualstudio.com/) ou o [Visual Studio](https://visualstudio.microsoft.com/).

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/jamerson-mt/ContosoPizza.git
   cd ContosoPizza
   ```

2. Instale as dependências e compile o projeto:

   ```bash
   dotnet restore
   dotnet build
   ```

3. Rode a API localmente:

   ```bash
   dotnet run
   ```

A API estará disponível em: `https://localhost:5001`.

### Armazenamento de Dados

Este projeto utiliza services e um cache temporário para armazenar dados no tempo de execução, ao invés de um banco de dados persistente. Isso significa que todas as alterações nos dados serão reiniciadas sempre que a aplicação for parada ou reiniciada. Não há necessidade de configurar ou migrar banco de dados.

## Endpoints da API

### Pizzas

- **GET /pizzas** - Retorna todas as pizzas.
- **GET /pizzas/{id}** - Retorna uma pizza específica pelo ID.
- **POST /pizzas** - Cria uma nova pizza.
- **PUT /pizzas/{id}** - Atualiza uma pizza existente.
- **DELETE /pizzas/{id}** - Deleta uma pizza pelo ID.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.


Esse README fornece uma visão clara do projeto e como iniciar com ele.
