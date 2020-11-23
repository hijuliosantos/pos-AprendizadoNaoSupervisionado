## Trabalho da aula de aprendizado não supervisionado da pós-graduação em Data Science da Furb.

Este trabalho consiste em aplicar a análise das componentes principais (PCA) na base da dados ORL, disponível neste repositório (ORL.zip), com o objetivo de realizar reconhecimento facial.

A base de dados (ORL.zip) é composta por 410 imagens de 41 pessoas diferentes, sendo 10 fotos de cada pessoa.

O trabalho foi desenvolvido no Google Colab, utilizando a linguagem de programação Python. Ele utiliza a biblioteca *OpenCV* para realizar a leitura de imagens e algumas transformações nelas. Toda a parte da implementação do machine learning, foi utilizada a biblioteca *scikit-learn*. Foi utilizado o método holdout de 70% das imagens para treinamento e 30% para os testes. Foi utilizada as 10 componentes principais até as 20 componentes principais. Para cada uma das iterações nas componentes principais, foi utilizado o algoritmo de aprendizado supervisionado 'Máquina de vetores de suporte' para realizar a predição. Como métrica, foi utilizada a acurácia. 

Ao final, é listada toda as imagens de teste, a imagem transformada com 20 componentes e uma imagem em branco, caso não tenha sido reconhecida Caso a imagem tenha sido reconhecida, é apresentada a imagem do acerto.

**Para executar o projeto:**
1) É necessário baixar o arquivo "ORL.zip" deste diretório;
2) Estar logado no gmail;
3) Acessar o diretório "PCA_ORL.ipynb" e clicar em "Open in Colab";
3.1) Pode ser acessado diretamente pelo seguinte endereço [PCAORL](https://colab.research.google.com/github/hijuliosantos/pos-AprendizadoNaoSupervisionado/blob/main/PCA_ORL.ipynb)
4) Após o notebook ser aberto, é necessário executar todas as células;
4.1) Na célula que abrirá a caixa de seleção "Escolher arquivos", é necessário inserir o arquivo "ORL.zip"
5) O arquivo "Resultado.png" apresenta a acurácia obtida na execução.
