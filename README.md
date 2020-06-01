![header](https://raw.githubusercontent.com/salomaocristiano/gostack11-desafio-reactjs-crud/master/assets/header-desafios.png)

<h3 align="center">
  Desafio 10: GoRestaurant Web
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/salomaocristiano/gostack11-desafio-reactjs-crud.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/salomaocristiano/gostack11-desafio-reactjs-crud.svg">

  <a href="https://www.codacy.com/app/salomaocristiano/gostack11-desafio-reactjs-crud?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=salomaocristiano/gostack11-desafio-reactjs-crud&amp;utm_campaign=Badge_Grade">
    <img alt="Codacy grade" src="https://img.shields.io/codacy/grade/04db4b43120b4d05b9b39c9d2da97300.svg">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/salomaocristiano/gostack11-desafio-reactjs-crud.svg">
  <a href="https://github.com/salomaocristiano/gostack11-desafio-reactjs-crud/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/salomaocristiano/gostack11-desafio-reactjs-crud.svg">
  </a>

  <a href="https://github.com/salomaocristiano/gostack11-desafio-reactjs-crud/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/salomaocristiano/gostack11-desafio-reactjs-crud.svg">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/salomaocristiano/gostack11-desafio-reactjs-crud.svg">
</p>

## Screenshot

<p align="center">

![image-example](https://raw.githubusercontent.com/salomaocristiano/gostack11-desafio-reactjs-crud/master/assets/bootcamp.jpg)

</p>

<p align="center">

![image-example](https://raw.githubusercontent.com/salomaocristiano/gostack11-desafio-reactjs-crud/master/assets/bootcamp01.jpg)

</p>

<p align="center">

![image-example](https://raw.githubusercontent.com/salomaocristiano/gostack11-desafio-reactjs-crud/master/assets/bootcamp02.jpg)

</p>

<p align="center">

![image-example](https://raw.githubusercontent.com/salomaocristiano/gostack11-desafio-reactjs-crud/master/assets/test.jpg)

</p>

## :rocket: Sobre o desafio

Criada aplicação GoRestaurant utilizando React.js junto com TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).

Essa será uma aplicação que irá se conectar a uma fake API, e exibir os pratos de comida criados e permitir a criação, remoção e atualização desses pratos.

### Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `title`, `value`, e  `description` e `available` de todos os pratos de comida que estão cadastrados na sua API.

- **`Adicionar novos pratos de comida a sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Novo Prato` no Header. Esse modal deve ser responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

- **`Editar pratos de comida da sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Editar Prato`. Esse modal deve ser responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.

- **`Remover pratos de comida da sua API`**: Em sua página Dashboard você deve remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: Em sua página Dashboard você deve alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.

### Específicação dos testes

Para esse desafio, temos os seguintes testes:

* **`should be able to list all the food plates from your api`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados, toda os pratos de comidas que são retornadas da sua fake API.

- **`should be able to add a new food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja adicionado a sua api, adicionando-o também à listagem.

- **`should be able to edit a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja editado na sua api, editando-o também na listagem.

- **`should be able to remove a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja removido da sua api, removendo-o também da listagem.

- **`should be able to update the availibility of a food plate`**: Para que esse teste passe, em sua dashboard você deve permitir que o status do prato de comida seja alterado entre `Disponível` e `Indisponível`;

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
