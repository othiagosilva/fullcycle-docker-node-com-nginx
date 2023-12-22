# Explicação
Colocar em prática o que foi visto em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada na aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:


Full Cycle Rocks!

- Lista de nomes cadastrada no banco de dados.

Gere o docker-compose de uma forma que basta apenas rodarmos o comando abaixo que tudo deverá estar funcionando e disponível na porta: 8080.

```
docker-compose up -d
```
