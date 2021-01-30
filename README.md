# click-fraud

Este é um projeto desenvolvido na Formação Cientista de Dados na [Data Science Academy](https://www.datascienceacademy.com.br/).

## Descrição do Projeto

O risco de fraude está em toda parte, mas para as empresas que anunciam online, a fraude de cliques pode acontecer em um volume avassalador, resultando em dados de cliques enganosos e dinheiro desperdiçado.

A TalkingData (https://www.talkingdata.com) cobre mais de 70% dos dispositivos móveis ativos na China. Eles lidam com 3 bilhões de cliques por dia, dos quais 90% são potencialmente fraudulentos. Sua abordagem atual para impedir fraudes de cliques para desenvolvedores de aplicativos é medir a jornada do clique de um usuário em todo o portfólio e sinalizar endereços IP que produzem muitos cliques, mas nunca acabam instalando aplicativos. Com essas informações, eles criaram uma lista negra de IPs e uma lista negra de dispositivos.

Embora bem-sucedidos, eles querem estar sempre um passo à frente dos fraudadores. Sendo assim, o objetivo neste projeto é construir um modelo de aprendizado de máquina para determinar se um clique é fraudulento ou não.

**DATASET**: https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/overview

## Descrição da Resolução

- Utilizou-se **Python 3.7.6** com Jupyter Notebook.
- Arquivo `data.csv` contém os dados utilizados para análise e criação do modelo
- Jupyter `click-fraud-modeling.ipynb` contém a construção do algoritmo para previsão

## Resultados Obtidos
***Estes resultados se baseiam no modelo final apenas***

- ROC Curve (AUC = 0.95)
- Precisão de 99,90%
- Quão bom o algoritmo é em acertar cliques fraudulentos: 99,69%
- Quão bom o algoritmo é em acertar cliques não fraudulentos: 42,85%

## Melhorias Futuras
- Aprimorar a análise exploratória dos dados
- Aplicação da Otimização de parâmetros no modelo criado
- Aprimorar o tratamento de váriaveis de tempo (Um abordagem possível: https://ianlondon.github.io/blog/encoding-cyclical-features-24hour-time/)
- Testar outros modelos de Classificação além do Random Forest
