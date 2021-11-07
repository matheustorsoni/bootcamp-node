# Projeto eduzz-bootcamp

### Descrição do projeto

<p>Vamos iniciar o desenvolvimento com Node.js, conhecendo os conceitos e uso do Node com JavaScript e aplicando isso a um projeto: criar um servidor, subir e devolver uma mensagem em JSON com informações de uso da memória RAM."</p>

--------------------
### Tabela de conteúdos
<!--ts-->
   * [Descrição do Projeto](#Descrição-do-Projeto)
   * [Tabela de conteúdos](#tabela-de-conteúdo)
   * [Oque Apendi com este projeto](#oque-aprendi-com-este-projeto)
   * [Imagens](#Imagens)
   * [Pre-Requisitos](#pre-requisitos)
   * [O que é o NodeJS](#O-que-é-o-NodeJS)
   * [Tecnologias](#tecnologias)
   * [Autor](#Autor)
<!--te-->

--------------------
### Oque aprendi com este Projeto
<!--ts-->
* Importaçao de modulos 'os'
* explorando metodos do modulo impoortado
* tratando as variaves
* criar um objeto com informaçoes
* explorando o metodo nativo setInterval()
* exportar o app e importar no servidor
* utilizando metodo JSON.stringfy()
* req res
* event Loop
* npm
* importaçao de modulo http
<!--te-->

------------------
### Imagens
<h3> 📌 Projeto rodando </h3>
<img src="imagens\imagen1.png" width="900px;" alt=""/>

------------------
### Pre-Requisitos


Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

-------
### O que é o NodeJS?

<img src="https://cdn.pixabay.com/photo/2015/04/23/17/41/node-js-736399_1280.png" width="300px" alt="logo nodejs"/>

O **NodeJs** é um ambiente de execução do **JavaScript** em _server-side_
</br></br>
Ok. Mas o que isso quer dizer? 
Ele nos dá a possibilidade de rodar localmente o JavaScript fora do navegador por exemplo. </br></br>

O nodejs trabalha com requisições **assíncronas**, ou seja, não precisa esperar todos os pedidos, vai entregando o que for ficando pronto.

Assim, o processamento é não-bloqueante(_non-blocking_), pois funciona mesmo sem uma requisição estar pronta, do contrário seria bloqueante(_blocking_) e tudo ficaria parado.</br></br>

Consequentemente, o entregador não precisa mais ficar preocupado e entrega o pedido assim que o mesmo for finalizado, depois volta no quadro de pedidos, pega os que faltaram e entrega logo após. Chamamos isso de **_Event-Loop_**.</br></br>

------------
### 🎲 Rodando o servidor local
```bash
# Clone este repositório
$ git clone <https://github.com/matheustorsoni/bootcamp-node.git>

# Acesse a pasta do projeto no terminal/cmd ou usando a opcao guit bash here
$ cd nomedapasta

# Execute 
$ node server.js
```
-----------------

### ⚒️Tecnologias⚒️ 

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)

----------

### Autor


 <img style="border-radius: 50%;" src="imagens\FotoPerfil.jpeg" width="100px;" alt=""/>
  <br />
 <sub><b>Matheus Torsoni</b></sub></a>

Feito por Matheus Torsoni👋🏽 Entre em contato!

[![Twitter Badge](https://img.shields.io/badge/-@tcmatheus-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/tcmatheus_)](https://twitter.com/tcmatheus_) [![Linkedin Badge](https://img.shields.io/badge/-Matheus-Torsoni?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/matheus-torsoni-b33957156/)](https://www.linkedin.com/in/matheus-torsoni-b33957156/) 
[![Outlook Badge](https://img.shields.io/badge/matheus_tcampos@hotmail.com-c14438?style=flat-square&logo=outlook&logoColor=white&link=mailto:matheus_tcampos@hotmail.com)](matheus_tcampos@hotmail.com)
