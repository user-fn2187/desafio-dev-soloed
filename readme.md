# Desafio Soloed - React + Node

Neste desafio, vamos avaliar seus conhecimentos em React e NodeJs. Queremos que você desenvolva um pequeno ecommerce para a Soloed_store seguindos os padrões do nosso layout e desenvolvendo um json server com os dados disponibilizados no arquivo JSON neste repositório.

# Instruções

- Clone este projeto em seu ambiente
- Desenvolva a aplicação seguindo as instruções abaixo
- Ao finalizar o desafio, suba para um repositório em seu Github e responda o e-mail com o link

## Frontend

Baseado no layout ([Figma](https://www.figma.com/file/sl23D5HJ2d3rgUTlnkHaJN/Soloed_store_teste?node-id=0%3A1)) sua tarefa é construir o frontend do nosso ecommerce seguindo os padrões de design (fontes, espaçamentos, cores e etc..).

#### User Stories

- [x] O usuário pode ver a lista completa de produtos
- [x] O usuário pode adicionar um produto ao carrinho
- [x] O usuário pode acessar a lista de produtos adicionados ao carrinho de compras
- [ ] O usuário pode alterar a quantidade de produtos no carrinho
- [x] O usuário pode remover produtos do carrinho
- [x] O usuário pode ver o valor total de produtos adicionados ao carrinho

#### Pré-requisitos

- Construir a aplicação utilizando React.
- Utilizar solução para gerenciamento de estado (Ex. Redux, Context API).
- Comprometimento com o design das páginas

#### Diferenciais

- Utilizar CSS in JS
- Utilizar Typescript
- Testes automatizados

## Backend

[x] Utilizando o arquivo JSON disponibilizado neste repositório, sua tarefa é construir uma API que será consultada pelo frontend.

#### API

[x] A API deve conter um método para consulta da listagem de produtos disponibilizadas em stock.json via HTTP Request.

#### Pré-requisitos

[x] Construir a API utilizando NodeJs

#### Diferenciais

[x] Utilizar Typescript
- Utilizar Docker Containers
- Testes automatizados

# Soloed\_ Store

- Projeto node
    instalar: yarn
    rodar projeto: yarn dev:server
    rota: http://localhost:3333//products

- Projeto React
    instalar: yarn
    rodar projeto: yarn start


 - Para o backend foi construido uma API em node que retorna através do request os produtos em formato json.
 Estruturei o projeto utilizando TS e dividindo responsabilidades. Nesta etapa não tive dificuldades e terminei em pouquissimo tempo.

- No frontend eu encontrei dificuldades com a criação do layout, foi o que mais me tomou tempo durante o desafio, isso resultou na falta da funcionalidade (aumentar a quantidade de um produto no carrinho), algo que eu conseguiria fazer se não estivesse demorando pra fazer o layout. Resumindo, minha maior dificuldade neste projeto foi o CSS. 

Fiquei feliz de ter a oportunidade de fazer esse desafio, enquanto eu realizava fui capaz de ver o resultado do meu 1 mês de estudo em react, mas também o quanto ainda preciso melhorar.