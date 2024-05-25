# CIFAR-10_model_flaskAPI

## Configuração do Ambiente
Bibliotecas Utilizadas:

TensorFlow
Flask
pyngrok
requests
Pillow (PIL)

## Modelo:

- Arquitetura: CNN (Convolutional Neural Network)
- Dataset: CIFAR-10
- Camadas: Conv2D, MaxPooling2D, Flatten, Dense
- Função de perda: Categorical Crossentropy
- Otimizador: Adam
- Métrica: Acurácia
- Épocas de Treinamento: 10
- Tamanho do Batch: 64

## Descrição dos Casos de Teste

Teste 1: Classificação de um barco
- Imagem de Teste: barco.jpg
- Caminho: /content/drive/MyDrive/imagens/11/barco.jpg
- Predição Esperada: ship
- Resultado da Predição: ship

Teste 2: Classificação de um avião
- Imagem de Teste: aviao.jpg
- Caminho: /content/drive/MyDrive/imagens/11/aviao.jpg
- Predição Esperada: airplane
- Resultado da Predição: airplane

Teste 3: Classificação de um carro
- Imagem de Teste: carro.jpg
- Caminho: /content/drive/MyDrive/imagens/11/carro.jpg
- Predição Esperada: automobile
- Resultado da Predição: automobile
