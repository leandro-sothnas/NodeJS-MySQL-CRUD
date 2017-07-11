# NodeJS
Projeto de CRUD feito em NodeJS usando Express e MySQL

### Objetivo do framework
O Node JS é uma plataforma para desenvolvimento de aplicações server-side baseadas em rede utilizando JavaScript e o V8 JavaScript Engine,
usa um modelo de I/O direcionada a evento não bloqueante que o torna leve e eficiente.
Ideal para aplicações em tempo real com troca intensa de dados através de dispositivos distribuídos.<br>

### Requisitos básicos para poder utilizá-lo
* [NodeJS](https://nodejs.org)
* [Xampp](https://www.apachefriends.org)
* [Postman](https://www.getpostman.com)

### Documentação
* NodeJS em inglês [NodeJS Docs](https://nodejs.org/en/docs/)  <br>
* Express em português [Express](http://expressjs.com/pt-br/)

### Principais vantagens do framework
* V8 JavaScript Engine: é o interpretador de JavaScript open source implementado pelo Google em C++ e utilizado pelo Chrome.<br>
* Single threaded: Embora isso possa parecer uma desvantagem, o que se percebe ao desenvolver com Node.js é que isso simplifica extremamente a construção da aplicação. <br>
* IO(In/Out) não-bloqueante: Com isto nenhuma tarefa pesadas de entrada e saída vai travar a aplicação,
pois elas serão executadas em background sem bloquear a aplicação e o retorno de sucesso
ou falha dessas tarefas ocorrem através de uma função de callback.<br>
* Ready for real-time: Frameworks que interagem em real-time entre cliente e servidor, que são compatíveis com o novo protocolo WebSockets 
e permitem trafegar dados através de uma única conexão bi-direcional,
tratando as mensagens via eventos no JavaScript. <br>
* Comunidade Ativa

### Desvantagem
O Express cria por padrão o projeto com view em `.jade`, sendo que mudaram para `.pug`.

### Principais passos para instalação e configuração deste projeto
Após clonar o projeto para executalo é necessário abrir o terminal ou cmd e ir para a pasta do projeto e executar: `npm install`. 
Também é necessário criar uma banco de dados e importar o arquivo `node.sql`. <br>
Após novamento no terminal executar o comando `npm start` para executar o projeto. <br>
Agora pode acessar `http://localhost:3000` para verificar se esta funcionando. <br>
E para usar no postman `http://localhost:3000/produtos`.

### Criar novo projeto
Após instalar o nodejs abrir o cmd ou terminal e executar o comando `npm install express-generator -g` para instalar o Express. 
Para criar um novo projeto executar `express nome_do_projeto`. <br>
Uma dica é executar antes o `express -h` para criar um projeto com as opções de desejar. 
Por exemplo `express --git --ejs nome_do_projeto` que cria um .gitignore e a os arquivos da view em formato ejs(o padrão é .jade). <br>
Com a criação do projeto entre pelo terminal ou cmd na pasta do projeto e execute `npm install`. <br>
Agora com o projeto criado e os modulos instalar pode executar `npm start` e acessar `http://localhost:3000` 
para ver se o projeto esta funcionando. 

### Videos
Criando e configurando o projeto 
[Parte 1](https://youtu.be/O81otVG1bZs) 
[Parte 2](https://youtu.be/w7DPGbVNZgI) 
