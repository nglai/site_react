# Gerenciador de projetos em react!

## É uma API no qual os dados serão salvos em um banco de dados

Na página principal pode-se inserir um novo projeto informando:
* Nome do projeto
* Orçamento do projeto
* Categoria

Em /projects mostrará todos os projetos existentes, no qual se pode editar ou excluir.

Ao selecionar o projeto, ira para /project/id, no qual mostrará as informações do projeto, botão para editar essas informações, os serviços daquele projeto, um botão para criar um novo serviço e um botão para excluir um serviço.

Ao clicar em adicionar um serviço, deve-se informar:
* Nome do serviço
* Custo do serviço
* Descrição do serviço

Algumas regras de negócio:
* O custo total de todos os serviços de um projeto não pode ultrapassar o orçamento do projeto

### Instalações:
* Criar o projeto: npx creat-react-app nomeDoProjeto
* Simulação do banco de dados: npm i json-server
* React icons (ícones): npm i react-icons
* Rotas: npm i react-router-dom
* Identificador: npm i uuid

### Para iniciar o projeto
* npm start
* npm run backend => starta o banco de dados que está na porta 5000