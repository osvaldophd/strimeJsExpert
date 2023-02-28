# JSExpertMax Gesture Controller - Semana JS Expert 7.0
Seja bem vindo(a) à sétima Semana Javascript Expert. Este é o código inicial para iniciar nossa jornada.

#Estrutura inicial do Projecto
    1 - index.js -> é responsavel por chamar todas as camamadas
    2 - services -> Toda a lógica de negócio e chamada externas(API, arquivo, banco de dados)
    3 - viewa -> Toda interação com oDOM(HTML)
    4 - Controller -> é a itermediária entre o service e views
    5 - factor -> importa as dependencia e cria as instancia
    6 - worker -> toda logica Pesada que envolve CPU

## Preview
<img width=100% src="./assets/demo-template-lg.gif">

## Pre-reqs
- Este projeto foi criado usando Node.js v19.6

## Running
- Execute `npm ci` para restaurar os pacotes
- Execute `npm start` e em seguida vá para o seu navegador em [http://localhost:3000](http://localhost:3000) para visualizar a página acima

## Checklist Features
- Titles List
  - [x] - Campo para pesquisa não deve travar ao digitar termo de pesquisa
  - [] - Deve desenhar mãos na tela e fazer com que elementos em segundo plano  continuem sendo clicáveis  🙌
  - [] - Deve disparar scroll up quando usar a palma das mãos abertas 🖐
  - [] - Deve disparar scroll down quando usar a palma das mãos fechadas ✊
  - [] - Deve disparar click no elemento mais próximo quando usar  gesto de pinça 🤏🏻
  - [] - Ao mover elementos na tela, deve disparar evento **:hover** em elementos em contexto

- Video Player
  - [x] - Deve ser possivel de reproduzir ou pausar videos com o piscar de olhos 😁
  - [x] - Todo processamento de Machine Learning deve ser feito via Web worker

### Considerações
- Tire suas dúvidas sobre os desafios em nossa comunidade, o objetivo é você aprender de forma divertida. Surgiu dúvidas? Pergunte por lá!

- Ao completar qualquer um dos desafios, envie no canal **#desafios** da comunidade no **Discord**

### Créditos ao Layout
- Interface baseada no projeto [Streaming Service](https://codepen.io/Gunnarhawk/pen/vYJEwoM) de [gunnarhawk](https://github.com/Gunnarhawk)