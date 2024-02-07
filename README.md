# ml-computer-vision-exercise
 
## Exercício final da disciplina de Visão Computacional

### Passos do Exercício:

#### Arquivos:

Arquivo Utilizado: exercise.ipynb<br>
Arquivo do Padrão solicitado: deteccao_liveness_notebook.ipynb


Arquivos Adicionais<br>

Pasta FILME_ML<br>
--> Nesta Pasta estão contidos os filmes para frames<br>

Pasta IMAGEM_ML_FALSA<br>
--> Nesta pasta estão contidas as imagens FALSAS<br>

Pasta IMAGEM_ML_VERDADEIRA<br>
--> Nesta pasta estão contidas as imagens VERDADEIRAS

Pasta IMAGEM_ML_TESTE<br>
--> Nesta pasta estão contidas as imagens de TESTE


## Processo

Realizou-se a separação em frames (imagens) utilizando os videos gravados na pasta "FILME_ML", foram capturadas imagens falsas e verdadeiras de usuários.<br>
Com isso geramos uma rede neural simples realizando o processo de convoluções e maxpooling, adicionamos a parte de dense, flatten e dropout.<br>
Apos o treinamento, utilizamos algumas imagens como teste e obtivemos um sucesso ate considerável se a devida imagem realmente é ou não é um liveness.

<BR>
Aqui um exemplo de uma CNN tipo VGG-16 com sua arquitetura

![Rede Neural VGG 16](https://www.researchgate.net/publication/346259768/figure/fig8/AS:961803395801094@1606323207263/VGG-16-CNN-model-architecture-layer-wise.jpg)

<BR>

Linha de tempo de redes neurais
![Historical line CNN Architectures](https://www.aismartz.com/blog/wp-content/uploads/2019/10/CNN-Architecture-over-a-timeline.jpg)
