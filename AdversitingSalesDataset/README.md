<h1 align="center"> Sales Prediction from Advertising Ads </h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<br>

<p align="center">
  <img alt="Projeto" src="AdversitingSalesDataset\images\dataset-card.jpg" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias e bibliotecas:

- Python
- Pandas
- Seaborn e Matplotlib
- Scikit-learn
- Regressão Linear


## 💻 Projeto

**Objetivo**: Realizar recomendações para impulsionar o crescimento de vendas da empresa.

A publicidade é fundamental para empresas, sendo o meio essencial para promover produtos e serviços e atrair clientes. Contudo, os custos de uma campanha publicitária podem ser significativos e as empresas necessitam analisar a efetividade de suas campanhas publicitárias. 

Sendo assim, a previsão de vendas é um fator fundamental para as empresas pois fornece insights cruciais sobre a receita esperada originada de suas campanhas promocionais.

A regressão linear é uma técnica estística que tem como objetivo prever o valor de uma variável dependente com base no valor de outra variável independente. A regressão auxilia a identificar uma linha reta que melhor se ajusta aos dados.

**Sobre**

- Este dataset, disponibilizado no Kaggle, inclui informações relativas ao orçamento destinado para publicidade em TV, rádio e jornais, além das vendas que esses investimentos geraram.

**Fonte**
- https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset


**Metodologia:**

- Regressão Linear Simples: Analisamos a correlação entre cada mídia e as vendas, construindo um modelo de regressão linear para cada uma.

- Regressão Linear Múltipla: Construímos um modelo de regressão linear múltipla que considera o impacto conjunto da TV e Rádio nas vendas.
Análise de dados: Realizamos análises estatísticas e visualizações dos dados para identificar insights e tendências.

**1.Carregamento e exploração do Dataset**

**2.Visualização dos dados**

**3.Preparação dos dados para modelagem e predição**

**4.Construção e treinamento do modelo de regressão linear**

**5.Predição**

**6.Comparação entre valores reais e previstos**

**7.Avaliação do modelo e métricas**

**8.Regressão Linear Múltipla**

**9.Conclusões e Recomendações**

**Resultados**

- TV: A variável com maior correlação com as vendas.
- Rádio: A segunda variável com maior correlação com as vendas.
- Jornal: Pouco efeito nas vendas.
- Modelo de Regressão Linear Simples (TV): R² de 0.6766, MAE de 2.4444, MSE de 13.3286 e RMSE de 3.6508.
- Modelo de Regressão Linear Múltipla (TV e Rádio): R² de 0.9005, MAE de 1.5423, MSE de 5.9412 e RMSE de 2.4401.


## Conclusão

A pontuação obtida na regressão linear múltipla são: 0.9005833101920356, ou seja, o valor da precisão aumentou quando incluimos a variável "Radio" no modelo. Sendo assim, essa pontuação foi melhor do que a do modelo anterior em que utilizamos apenas uma variável e o score foi de 0.6766954295627076.

Isso significa que a publicidade na TV  e Rádio são as que mais contribui nas vendas, já no jornal, tem pouco efeito nas vendas. Sendo assim, podemos dizer que com base nessa análise o profissional responsável pelas campanhas deve alocar mais recursos para a TV e Rádio.

