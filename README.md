![image](https://github.com/marcostwelve/API-EF/assets/94411600/cd709e49-c5df-4385-8b99-997d1bee6221)

# API Contatos

API de contatos, é um projeto para criar e guardar contatos. Com os dados de ID, Nome, Telefone e Status.

## 🔥 Introdução

API foi criada com os métodos Http, com todos os endpoints do Http: Get, Post, Put, Delete

### ⚙️ Pré-requisitos
* Visual Studio
* Entity Framework
* .Net Core
* Sql Server (Ou outro banco de dados)


### 🔨 Guia de instalação

Para utilizar este projeto, necessário instalar o Entity Framework, e configurar o banco de dados no arquivo appsettings.Development.json, e instalar as migrations para conexão com o banco de dados

Etapas para instalar:

```bash
dotnet tool install --global dotnet-ef
```
Passo 2:
```bash
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```
Passo 3:
```bash
Install-Package Microsoft.EntityFrameworkCore.Design
```
Passo 4:
```bash
dotnet-ef migrations add (Nome da migration do projeto)
```

Passo 5:
```bash
dotnet-ef database update
```


## 🛠️ Executando os testes (caso tenha testes)

Para executar o projeto, para testes. Digite o seguinte comando no terminal do Visual Studio

```bash
dotnet watch run
```

### Método Get

O Método Get, realiza a busca todos os contatos, ou um contato, através do seu ID
![image](https://github.com/marcostwelve/API-EF/assets/94411600/2f647d79-7064-44a7-a0c0-035ed6f64052)

![image](https://github.com/marcostwelve/API-EF/assets/94411600/0ab2320d-6c1f-435b-961b-cac8352048fe)
Caso o ID não exista, o endpoint irá retornar o status 404 Not Found (não encontrado)

### Método Post
O método Post, realiza a criação de um novo contato, enviando dados através do Body da requisição
![image](https://github.com/marcostwelve/API-EF/assets/94411600/0fdd9eed-d45f-4a84-abba-3b5235f5d3a5)

Caso algum campo não seja preenchido, ele será salvo como nulo

### Método Put
O método Put, irá atualizar o contato, com preenchimento de todos os campos
![image](https://github.com/marcostwelve/API-EF/assets/94411600/64d0812d-c167-4a0b-87c9-619b52dc2f2a)

### Método Delete
O método Delete, irá deletar o contato do banco de dados, sendo uma operação irreversível
![image](https://github.com/marcostwelve/API-EF/assets/94411600/82708e1c-d3d3-49d6-b1bf-52d25f4829e9)


## 📦 Tecnologias usadas:

Coloque aqui as ferramentas que você usou para criar seu projeto, exemplo:

* [C#](https://learn.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/)
* [Entity Framework](https://learn.microsoft.com/pt-br/ef/core/get-started/overview/install)
* [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)



## 👷 Autores


* **Maurício Marcelino** - *Back-End do projeto* - [Maurício Marcelino](https://github.com/marcostwelve)


## 📄 Licença

Esse projeto está sob a licença (MIT) - acesse os detalhes [LICENSE.md](https://opensource.org/license/mit/).




## 💡 Expressões de gratidão

* Agradeço todos por verificarem o meu projeto. Esotu aberto a sugestões de melhorias e evolução do projeto.
* [Meu linkedin](https://www.linkedin.com/in/mauricio-marcelino/)
