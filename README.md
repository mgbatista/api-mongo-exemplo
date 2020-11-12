# Projeto API Covid-19 

Esta API faz o cadastro de pessoas infectadas através de um método POST, utilizando o formato abaixo:

```json
{
	"dataNascimento": "1990-03-01",
	"sexo": "M",
	"latitude": -23.5630994,
	"longitude": -46.6565712
}
```

Link de teste: http://localhost:5000/infectado

Utilizando o mesmo link, trás as informações cadastradas através do método GET, e atualiza através do método PUT.

Com o método DELETE é possível excluir um cadastro, basta incluir a data de nascimento como parâmetro, conforme exemplo abaixo:

http://localhost:5000/infectado/1930-03-01

Projeto realizado através do Bootcamp Avanade pela Digital Innovation One

Repositório do instrutor: https://github.com/gabrielfbarros/dotnet-mongo

