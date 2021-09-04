Fogo do Doom gerado com JavaScript puro.

O desenvolvimento do projeto se deu a partir do tutorial do Filipe Deschamps (https://www.youtube.com/watch?v=fxm8cadCqbs&t=2s&ab_channel=FilipeDeschamps), portanto créditos a ele!

O fogo do Doom é criado a partir de uma tabela com dois parâmetros: posição (x, y) e intensidade (do fogo). É montado portanto um mapa de intensidades para o fogo, com códigos RGB para indicar a cor a ser visualizada na tela. Valores aleatórios são subtraidos da intensidade a cada intervalo de tempo (pré determinado) para que seja passado a sensação de movimento ao fogo, tanto na vertical, simbolizando movimento de chama, quanto na horizontal, simbolizando o vento. 

O projeto possui dois arquivos:
- index.html: aqui são gerados os parâmetros visuais, como definições da tabela
- fire.js: aqui o fogo é de fato gerado, com o código de cores, efeitos de aleatoriedade, intensidade e afins. Aqui também é definido o tamanho da tabela onde o fogo será posicionado