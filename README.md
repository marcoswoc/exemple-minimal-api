# exemple-minimal-api

## Introdução
A partir do .NET 6 a Microsoft disponibilizou um novo recurso chamando Minimal APIs, com esse recurso podemos criar uma API com o minimo de dependências do ASP .NET Core. Diferente do padrão já existente para criar APIs, o novo recurso não utiliza os famosos Controllers para expor suas rotas, nesse artigo vamos criar uma Minimal API com Swagger e Entity Framework Core.

Você pode acessar o repositório desse projeto em <a href="https://github.com/marcoswoc/exemple-minimal-api" target="_blank">Exemplo-Minimal-Api ⭐</a>

## Pré-requisitos

+ .NET 8
+ Visual Studio Code (VS Code)

## Criando o projeto
Com o comando **`dotnet new web`** vamos criar um projeto do tipo Minimal API, podemos utilizar o parâmetro **`-o`** para criar o projeto em uma pasta, o nome da pasta será o nome do projeto, também estamos utilizando o parâmetro **`-f`** para determinar a versão do framework utilizado, no nosso caso net8.0

    dotnet new web -o ExemploMinimalApi -f net8.0
## Conclusão