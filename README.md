# Tutorial Kabil Contabilidade

## Back end e Front end

### Micro serviço(api), em linguagem Java, Spring Boot

Esta api realiza a comunicação com o servidor local Apache e banco de dados MySql criando as tabelas automaticamente com o serviço Hibernate, e também contém todas as funcionalidades da aplicação.

### Projeto Web NodeJS, em linguagem JavaScript, React

Este projeto web realiza a comunicação com o usuário, e está conectado com o micro serviço para realizar as ações do usuário.

**Requisitos:**

- IDE Eclipse.
- XAMMP (Serviço de servidor(Apache Tomcat), e banco de dados(MySql)).
- NodeJS.
- Visual Studio Code.
  - Opcional: GitHub, Postman, Git, Extensões React, HTML, CSS... para o Visual Studio Code.

### Back end

> Abra a IDE Eclipse e importe o projeto: **back-end-kabil**.
![alt text](https://github.com/peedroguerra/desktop-tutorial/blob/main/importar-projeto-eclipse.PNG)

> Abrir o **XAMMP** e acionar os serviços do Apache, e MySql.
![alt text](https://github.com/peedroguerra/desktop-tutorial/blob/main/iniciar-servicos-xammp.PNG)

> Criar uma base de dados chamado: **kabil**.
![alt text](https://github.com/peedroguerra/desktop-tutorial/blob/main/criar-base-dados.PNG)

> Executar o arquivo principal como uma aplicação Java.
![alt text](https://github.com/peedroguerra/desktop-tutorial/blob/main/executar-arquivo-principal.PNG)

Neste momento, quando a aplicação estiver executando, você pode testar as rotas da aplicação, com o programa Postman, as rotas  se encontram na documentação do Swagger.

### Front end

> Abra a pasta do projeto: **front-end-kabil** no Visual Studio Code.

> Abra um novo terminal no próprio Visual Studio, e digite `npm install`para instalar as depêndencias do projeto.
![alt text](https://github.com/peedroguerra/desktop-tutorial/blob/main/instalando-dependencias-npm.PNG)

> Digite o comando `npm start` para inicializar a aplicação.

> Terminado as etapas, você será redirecionado para o endereço local do jogo, abrindo seu navegador principal na tela inicial da aplicação.

### Guia para o desenvolvedor

- [git - apenas um guia prático para começar com git. sem complicação ;)](https://rogerdudler.github.io/git-guide/index.pt_BR.html).
- [Conhecendo o Eclipse - Uma apresentação detalhada da IDE](https://www.devmedia.com.br/conhecendo-o-eclipse-uma-apresentacao-detalhada-da-ide/25589).
- [Como Instalar o XAMPP para Windows](https://pt.wikihow.com/Instalar-o-XAMPP-para-Windows).
- [MySQL](https://www.devmedia.com.br/guia/mysql/34335).
- [Guia de Referência Hibernate](https://www.devmedia.com.br/guia/hibernate/38312).
- [Tudo sobre Java!](https://blog.geekhunter.com.br/tudo-sobre-java/).
- [Guia de Node.js](https://www.devmedia.com.br/guia/node-js/40312).
- [Um guia para usar React JS](https://blog.geekhunter.com.br/um-guia-para-usar-react-js/).
