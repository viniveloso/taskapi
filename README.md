# TaskApi
?? TaskApi – API de Gerenciamento de Tarefas (.NET 8)

Uma API REST simples desenvolvida em .NET 8, usando Entity Framework Core e SQLite.
Criada para demonstrar domínio de:

Estrutura de APIs REST
CRUD completo
Boas práticas com controllers
EF Core + Migrations
Uso do DbContext
Documentação com Swagger

A API permite criar, listar, atualizar e deletar tarefas.

?? Tecnologias Utilizadas
.NET 8 Web API
Entity Framework Core
SQLite
Swagger / OpenAPI

?? Estrutura do Projeto
TaskApi/
 ??? Controllers/
 ?    ??? TasksController.cs
 ??? Data/
 ?    ??? AppDbContext.cs
 ??? Migrations/
 ??? Models/
 ?    ??? TaskItem.cs
 ??? appsettings.json
 ??? Program.cs
 ??? TaskApi.csproj

?? Como Executar o Projeto
1. Restaurar pacotes: dotnet restore
2. Aplicar migrations: dotnet ef database update
3. Rodar o servidor: dotnet run

?? Swagger disponível em:
https://localhost:7180/swagger

?? Endpoints Principais
?? GET /tasks
Retorna todas as tarefas.

?? GET /tasks/{id}
Retorna uma tarefa específica.

?? POST /tasks
Cria uma nova tarefa.

?? PUT /tasks/{id}
Atualiza uma tarefa.

?? DELETE /tasks/{id}
Remove a tarefa.

?? Exemplo de JSON (POST/PUT)
{
  "title": "Estudar C#",
  "isCompleted": true
}

?? Licença
Projeto sob licença MIT. Sinta-se à vontade para usar e modificar!

? Autor
Vinicius Veloso
Desenvolvedor .NET | Evolução contínua ?