# Move Mouse Head

[![N|Solid](https://uploaddeimagens.com.br/images/002/869/762/original/DesenvolvidoPor.png)](https://8pixel.com.br)

O Move mouse é uma aplicação que tem como principal objetivo tornar os sites acessíveis para pessoas que tem algum tipo de deficiência motora e por isso não consegue mover o mouse com a mão ou com o pé. 
O Objetivo dele é bem simples, com movimentos com a cabeça que são reconhecidos pela webCam, o usuário vai conseguir mover o mover o mouse e efetuar cliques.

  ![Alt text](http://8pixel.com.br/github/readme-imgs/Cima.png "Pessoa olhando para cima") <br />
  - Inclinando a cabeça para cima o mouse vai para cima <br />
  ![Alt text](http://8pixel.com.br/github/readme-imgs/Baixo.png "Pessoa olhando para baixo")<br />
  - Inclinando a cabeça para  baixo o mouse vai para baixo<br />
  ![Alt text](http://8pixel.com.br/github/readme-imgs/Esquerda.png "Pessoa olhando para esquerda")<br />
  - Inclinando a cabeça para a esquerda o mouse vai para esquerda<br />
  ![Alt text](http://8pixel.com.br/github/readme-imgs/Direita.png "Pessoa olhando para direita")<br />
  - Inclinando a cabeça para a direita o mouse vai para a direita


### Plugins

Para funcionar o Move mouse utiliza ferramentas e plugins:

* [Teachable Machine] - Uma maneira rápida e fácil de criar modelos de aprendizado de máquina para seus sites, aplicativos e muito mais - sem necessidade de conhecimento ou codificação.
* [Tensor Flow] - Desenvolva modelos de ML em JavaScript e use ML diretamente no navegador ou no Node.js.

E, claro, o próprio Move Mouse é open source com um [repositório público][dill]
no GitHub.

### Instalação

Para instalar é muito simples, basta efetuar o download ou o clone do projeto e inserir o uma tag <script> na <head> do seu website.

```html
<!DOCTYPE html>
<html>
    <head>
	    <meta  charset="UTF-8">
	    <!-- META TAGS DO SEU WEBSITE -->
	    <title>[NO DO SEU WEBSITE]</title>
        <script type="text/javascript" src="lib.js"></script>
    </head>
    <body>
	</body>
</html>
```
A tag pode ser inserida também ao final do body.


### Disparar e usar

Para disparar o evento e começar a utilizar a biblioteca para mover o mouse, basta adicionar a o atributo data-head-mouse em qualquer o botão.
```html
<button type="button" data-head-mouse>Começar</button>
```

### Demo
Para ver em funcionamento [visite nossa página demo]

### Desenvolvimentor

Esta aplicação ainda esta em desenvolvimento, então toda e qualquer ajuda é bem vinda.

### Todos

 - Realizar teste funcional com as personas corretas
 - Adicionar módulo de controle de velocidade de mouse
 - Aprimorar sensores de movimento

License
----

MIT


** Software livre**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [Tensor Flow]: <https://www.tensorflow.org/js>
   [ visite nossa página demo]: <https://demowebpage.8pixel.com.br>
   [Teachable Machine]: <https://teachablemachine.withgoogle.com/>
