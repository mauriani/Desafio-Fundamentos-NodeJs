# Desafio-Fundamentos-NodeJs

<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 05: Primeiro projeto Node.js
</h3>


## :rocket: Sobre o desafio

Esse é o desafio n° 05 do bootcamp, a ideia foi solidificar tudo que foi transmitido até agora. A aplicação permite que usuário realize dépositos, gerencie os valores e controle do saldo atual.

### Rotas da aplicação

Essas foram as rotas criadas:

- [x]  **`POST /transactions`**: A rota deve receber `title`, `value` e `type` dentro do corpo da requisição, sendo `type` o tipo da transação, que deve ser `income` para entradas (depósitos) e `outcome` para saídas (retiradas). Ao cadastrar uma nova transação.
- [x]  **`GET /transactions`**: Essa rota deve retornar uma listagem com todas as transações que você cadastrou até agora, junto com o valor de soma de entradas, retiradas e total de crédito.


### Clonando o projeto

```jsx
 # clonar o repositório
 $ https://github.com/mauriani/Desafio-Conceito-Nodejs.git

 # acessar a pasta do projeto
 $ cd Desafio-Conceito-Nodejs

 # instalar as dependências do projeto
 $ yarn or npm install
```

### Start na aplicação
Depois disso basta rodar:

```jsx
yarn dev:server
```





