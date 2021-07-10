# Exploração e Avaliação de Técnicas para a Geração de Anáglifos [[PDF]](http://)

## Descrição do Problema
### Resumo
Este trabalho investigou e avaliou um conjunto de técnicas para a geração de imagens de anáglifos, a partir de uma ou duas imagens, explorando o efeito tridimensional (3D) causado na contrução de uma  imagem bidimensional (2D). Técnicas clássicas foram também estudadas e aplicadas de forma a se obter um estudo comparativo entre elas. Com base nesta pesquisa, determinamos que os métodos lineares são os mais simples deser implementados, em comparação com os não lineares.  As seguintes técnicas foram avaliadas:  Verdadeiro (True), Cinza (Gray), Colorido (Color), Meia Cor (Half Color) eOtimizado (Optimized).  Os resultados obtidos mostraram que cada uma destas técnicas possui suas vantagens e desvantagens e, embora algumas combinações de filtros melhorem o resultado final, ainda podemos observar algumas anomalias como a distorção de cores, competição retinal (retinal/binocular rivalry) e desaparecimento (ghosthing).

### Objetivo
O tema deste artigo  ́e a investiga ̧c ̃ao de t ́ecnicas para a gera ̧c ̃ao de imagens, explorandoseu efeito tridimensional (3D). A t ́ecnica escolhida para realiza ̧c ̃ao deste estudo  ́e o an ́aglifoque, a partir de uma ou duas imagens, pode combin ́a-las em uma terceira, gerando o efeito3D, mas ainda sendo uma imagem bidimensional (2D). Como objetivo secund ́ario, t ́ecnicascl ́assicas foram estudadas e aplicadas de forma a se obter um estudo comparativo entre elas.Para cumprimento desses objetivos, uma revis ̃ao bibliogr ́afica foi realizada, al ́em do estudonecess ́ario para a identifica ̧c ̃ao de uma base de dados com imagens.

### Requisitos
* Acesso ao notebook Google Colab

### Ajuste no Código
Na execução do script será necessário atualizar o diretório local onde está localizado as imagens, que busco a pasta no meu drive:
```python
# atualizar o diretório do método save_img:
diretorio_F = '/content/drive/MyDrive/PFG/Imagens/Resultados/'+ image_number +'_F_' + metodo +'.png'

# atualizar com o nome da imagem:
image_number = '0112'

# atualizar diretório de onde a foto se encontra no drive:
diretorio_R = '/content/drive/MyDrive/PFG/Imagens/Teste/'+ image_number +'_R.png'
diretorio_L = '/content/drive/MyDrive/PFG/Imagens/Teste/'+ image_number +'_L.png'
diretorio_F = '/content/drive/MyDrive/PFG/Imagens/Teste/'+ image_number +'_R.png'
```

### Base de Imagens
A base utilizada para realizar os experimentos foi a [Flickr1024](https://yingqianwang.github.io/Flickr1024/),
um banco de imagens já utilizando em diversos outros estudos e resoluções de problemas relacionados à 
estereoscopia, ao efeito paralaxe e à visão binocular.

### Métodos
#### True
#### Gray
#### Color / Photoshop
#### Half Color
#### Optimized

### Links úteis:

Trabalhos Relacionados:

- [Comparação de Métodos Anáglifos](http://www.3dtv.at/Knowhow/AnaglyphComparison_en.aspx)
- [Base de Imagens Flickr1024](https://yingqianwang.github.io/Flickr1024/)






### Citação:
```
@techreport{TR-IC-PFG-21-02,
  number = {IC-PFG-21-02},
  author = {Matheus {Mendes Araujo} and Hélio Pedrini},
  title = {{Exploração e Avaliação de Técnicas para a Geração de Anáglifos}},
  month = {July},
  year = {2021}, 
  institution = {Institute of Computing, University of Campinas}
}
 ```
