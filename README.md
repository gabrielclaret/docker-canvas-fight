# docker-canvas-fight

Jogo feito com HTML5 em docker.

## How-to

1. Buildar a imagem Docker:

`docker build -t canvasfight .`

2. Executar o container: 

`docker run -dt -p 3838:80 canvasfight`

> A porta 3838 é sua porta local, pode ser alterada. Mas é recomendado 3838 ou 8080. 

> A aplicação estará disponível no localhost:3838 (ou em outra porta, caso tenha alterado) no seu browser. 
