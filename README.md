# Predição do faturamento semanal do Walmart - Escolhendo o melhor algoritmo de machine learning entre algumas opções.

## Sumário
* [Overview](#overview)
* [Resultados e Conclusões](#Resultados)
* [Tecnologias](#tecnologias)

## Overview
Estimação da venda semanal de produtos do Walmart. Os dados estão distribuidos em três bancos de dados, um contendo dados sobre a macroeconomia e sobre o clima (features.csv), um contendo informações sobre as lojas (stores.csv), e por fim, um dataset contendo os valores das vendas semanais (train.csv). O presente estudo teve como objetivo selecionar e aplicar o melhor modelo a massa de dados apresentada acima.

## Fonte dos Dados
Os dados utilizados na análise são open source e podem ser encontrados no seguinte website: https://github.com/fregonalab/Walmart_Sales/

## Resultados e Conclusões
O presente estudo foi uma ótima oportunidade de revisão principalmente do processo envolvido na seleção de modelos, e ajuste de seus hiperparâmetros com limitação computacional. Aqui cobrimos o estudo da conecção entre datasets, tratamento de outliers, one-hot encoding, normalização de variáveis numéricas, amostragem de dados, seleção de modelos, métricas para modelos de regressão, e ajuste de hiperparâmetros. Como resultado, o algoritmo final teve um RMSE = 4189 doláres e um MAE = 2392 doláres no conjunto de validação utilizando todo o banco de dados.
	
## Tecnologias
Projeto criado com:
* Python: 3.10.4
  * Biblioteca: Numpy, Matplotlib.pyplot, pandas, seaborn, scikit-learn
* IDE: Google Colab
* Unix: OS version 18.7.0
* Git and Github
