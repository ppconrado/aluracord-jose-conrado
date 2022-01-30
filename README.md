## PARTE 1

Começaremos a fazer a nossa área de login no Aluracord! E você vai colocá-la no ar!

Nesta aula vamos criar tudo do ZERO: desde o package.json até os arquivos bases do Next.js para iniciar nosso projeto e ter o CSS in JS com styled-jsx para cuidar da camada de estilo da nossa aplicação, duas ferramentas essenciais do mundo React. Também entenderemos como React se tornou tão popular no mercado de tecnologia e como iniciar o nosso aprendizado com a tecnologia.

Conteúdo detalhado
Iniciaremos um projeto Next.js;
Criaremos components com React usando CSS in JS;
Vamos ver a estrutura inicial de um projeto Next.js;
Passaremos propriedades para components;
Faremos deploy do seu Aluracord na Vercel.
Lembre de postar o resultado final do seu Aluracord com as hashtags #ImersaoReact e #Aluracord marcando o Mario e o Paulo!

Desafios desta aula!
Customizar o Aluracord com o SEU tema, seu background do assunto favorito (Filmes, Séries, Esportes, o desenho do coração) e compartilhar com a gente!, lembre-se de usar o Coolors que indicamos nesta aula, para gerar a paleta de cores.
Nosso arquivo de config com a parte das cores para você fazer o seu tema está aqui, use-o como base 😍
Customizar o Aluracord com o SEU tema, seu background do assunto favorito (Filmes, Séries, Esportes, o desenho do coração) e compartilhar com a gente!, lembre-se de usar o Coolors que indicamos nesta aula, para gerar a paleta de cores.
Códigos e links importantes para você acompanhar a aula
Figma com o design que desenvolvemos na tela

Iniciar o projeto

npx create-next-app --example with-styled-components

# ou

yarn create next-app --example with-styled-components
Instalar e importar a lib de componentes brasileira totalmente integrada com o Next.js @skynexui/components

npm install @skynexui/components
ou

yarn add @skynexui/components
E depois, no seu código importe:

import { Box, Button, Text, TextField, Image } from '@skynexui/components';
Códigos prontos citados na aula
Repositório do Aluracord
Confira nossa vitrine e deixe seu fork e star em nosso projeto. Vamos fazer o mundo todo ver essa comunidade que estamos criando para aprender React! https://github.com/alura-challenges/aluracord-matrix
Aqui você consegue ver com detalhes as alterações de arquivos que fizemos: https://github.com/alura-challenges/aluracord-matrix/pull/1/files
Links citados nesta aula
React
Mario Souto - Strategy Pattern
Mario Souto - Pegando dados de uma API com React
Mario Souto - O sistema de rotas do NextJS, principais dúvidas
Mario Souto - Linter
Mario Souto - Centralizar conteúdo na tela
CSS Grid Garden
Flexbox Froggy
Mario Souto - Storybook na prática
Mario Souto - Configurando ambiente JavaScript/NodeJS/Yarn
Documentação interativa com Storybook do SkynexUI

## PARTE 2

Vamos lidar com o state do React e entender melhor o que é uma SPA (Single Page Application).

Conteúdo detalhado

Entender melhor o que é um SPA;
Conhecer o useState do React;
Como trabalhar com eventos no React onSubmit, onClick;
E sempre após cada push na sua branch principal do GitHub faremos deploy do seu Aluracord na Vercel.
Lembre de postar o resultado final do seu Aluracord com as hashtags #ImersaoReact e #Aluracord marcando o Mario e o Paulo!

Desafios
Pratique mais com o useRouter!
Validação do campo: Só mostrar a imagem se tiver mais de 2 caracteres
Desafio Master: Pegar outras informações do usuário batendo na API do GitHub
Dica: você vai usar a função fetch do JavaScript
Colocar algo divertido na página 404.js da sua pasta pages e compartilhar com a gente no twitter!
Repositório do Aluracord
Confira nossa vitrine e deixe seu fork e star em nosso projeto! Vamos fazer o mundo todo ver o Aluracord Matrix: https://github.com/alura-challenges/aluracord-matrix/
Aqui você consegue ver com detalhes as alterações de arquivos que fizemos: https://github.com/alura-challenges/aluracord-matrix/pull/3/files
Links importantes para você acompanhar a aula
Aprender forEach e map - Mario Souto
Links citados nesta aula
Mario Souto - Validando Formulários com React
Como fazer AJAX? E pegar os dados da API do GitHub
Mario Souto - Github Pro + Eslint
Criando Flappy Bird com JavaScript - Mario Souto

## Parte 3

Vamos criar a estrutura do nosso chat e fazer ele funcionar inicialmente sem nenhum Back-End. Explicaremos também muitos conceitos de Front-End que funcionam em diversos tipos de projetos. Você vai perceber como ser Dev em T facilita muito a sua vida como programador ou programadora!

Conteúdo detalhado
Entender um pouco mais de como podemos trabalhar com state no React;
Trabalhar com arrays no state;
Criar um campo que ao apertamos o "Enter", faz o submit das informações;
Lembre de postar o resultado final do seu Aluracord com a hashtag #ImersaoReact marcando o Mario e o Paulo!

Desafios
Paulo: Colocar o botão de OK para enviar a mensagem
Mario: Colocar um botão de apagar mensagem! Dica: use o filter
Repositório do Aluracord
Confira nossa vitrine e deixe seu fork e star em nosso projeto: https://github.com/alura-challenges/aluracord-matrix/
Links importantes para você acompanhar a aula
Template base da página do Chat usado no começo da aula
Código da Aula completo com tudo o que fizemos na aula
Links citados nesta aula
Lembre-se de se inscrever no canal do DevSoutinho
Dar uma star no repositório da imersão
Dar uma star no repositório da biblioteca @skynexui/components

## Parte 4

Vamos integrar com o Supabase! Uma ferramenta de "Back-End as a Service" que vai nos ajudar a ter um banco de dados real time para guardar as mensagens do nosso chat.

Conteúdo detalhado desta aula
AJAX e o que é?
Supabase
Aba network para debugarmos requests HTTP
useEffect no React
Lembre de postar o resultado final do seu Aluracord com a hashtag #ImersaoReact marcando o Mario e o Paulo!

Desafios desta aula!
Mario Souto: Mostrar o loading de mensagens (Tem que fazer o mais criativo ein!)
Paulo Silveira: Fazer um efeito quando passar o mouse em cima (Use esse link como referência: https://pt-br.reactjs.org/docs/events.html#mouse-events)
Se quiser tentar criar alguma coisa mais diferentona, fique a vontade para criar e compartilhe com a gente :)
Repositório do Aluracord
Confira nossa vitrine e deixe seu fork e star em nosso projeto: https://github.com/alura-challenges/aluracord-matrix/
Aqui você consegue ver com detalhes as alterações de arquivos que fizemos: https://github.com/alura-challenges/aluracord-matrix/pull/5/files
Links importantes para você acompanhar a aula
Figma com o design que desenvolvemos na tela
Supabase
Código que alteramos na aula arquivo por arquivo
Links citados na aula
Mario Souto - Latência
Mario Souto - Como fazer AJAX
Http Status Dogs
API do GitHub
Dev em T
Pacote de stickers da Alura
