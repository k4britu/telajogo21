# Resultado
### (algo próximo disto)

![alt text](image.png)

isto para primeira parte em seguida o resultado com reposicionamento dos itens.

com o reposicionamento e ajuste tamanho  deve ficar parecido como abaixo:

![alt text](image-1.png)

<hr>

Agora vamos focar no estudo de como foi escrito o nosso CSS. (vejamos abaixo):

``` css
.mesa{
    position: fixed;
    width:900px;
    height:600px;
    background-color: green;
      }
.robot{
   position: relative;
   top:5px;
   left:15px;
   width:160px;
   height:60px;
   background-color: black;  }      
.jogador{
    position: relative;
    top:390px;
    left:15px;
    width:160px;
    height:60px;
    background-color: black; }   
.baralho{
    position: relative;
    top:200px;
    left:315px;
    width:60px;
    height:80px;
    background-color:yellow;}   
```
Carlos Eduardo Lira de Oliveira
Código: Jogo21.html
```
<!DOCTYPE html> <!--define o tipo de documeto -->
<html lang="en"> <!--define o idioma usado -->
<head> <!--é o cabeçalho da página -->
    <meta charset="UTF-8"> <!-- define os caracteres -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!--define a escala da pagina de acordo com o dispositivo -->
    <title>Document</title> <!--é o nome do titulo da aba -->
    <link rel="stylesheet" href="estilo.css"> <!--linka o CSS com o html -->
</head>
<body> <!--é o corpo da página -->
    <div class="mesa"> <!--cria a div com a classe "mesa" -->
        <div class="robot"></div> <!--cria a div com a classe "robô" -->
        <div class="baralho"></div> <!--cria a div com a classe "baralho" -->
        <div class="jogador"></div> <!--cria a div com a classe "jogador" -->
    
    </div>
</body>
</html>

```
Código estilo.CSS

.mesa{ /*cria a classe "mesa"*/
    position: fixed;n /*define a posição da mesa na página*/
    width:900px; /*define a largura da mesa na página*/
    height:600px; /*define a altura da mesa na página*/
    background-color: green; /*define a cor da div*/
      }
.robot{  /*cria a classe "robot"*/
   position: relative; /*define a posição da robot na página*/
   top:5px; /*define a distância do robot do topo da página em pixels*/
   left:15px; /*define a distância do robot da esquerda da página em pixels*/
   width:160px; /*define a largura do robot na página*/
   height:60px; /*define a altura do robot na página*/
   background-color: black; /*define a cor de fundo da classe*/
     } 
.jogador{ /*cria a classe "jogador"*/
    position: relative; /*define a posição do jogador na página*/
    top:390px; /*define a distância do jogador do topo da página em pixels*/
    left:15px; /*define a distância do jogador da esquerda da página em pixels*/
    height:60px; /*define a largura do jogador na página*/
    background-color: black; /*define a cor de fundo da classe*/
    }   
.baralho{ /*cria a classe "baralho"*/
    position: relative; /*define a posição do baralho na página*/
    top:200px; /*define a distância do baralho do topo da página em pixels*/
    left:315px; /*define a distância do baralho da esquerda da página em pixels*/
    width:60px; /*define a largura do baralho na página*/
    height:80px; /*define a altura do barulho na página*/
    background-color:yellow; /*define a cor de fundo da classe*/
    }   
    
    ( ͡° ͜ʖ ͡°) 

