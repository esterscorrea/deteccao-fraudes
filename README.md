Detecção de Fraudes em Transações com Cartão de Crédito

Projeto desenvolvido como parte do bootcamp DIO.

Sobre o Projeto

Este projeto aplica técnicas de Machine Learning para identificar transações financeiras fraudulentas em um dataset real com mais de 284 mil transações.

📂 Dataset

Credit Card Fraud Detection — Kaggle

284.807 transações reais de cartões de crédito europeus
Apenas 492 fraudes (~0,17%) — dataset altamente desbalanceado

 Tecnologias Utilizadas

Python 3
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Etapas do Projeto

Análise exploratória dos dados (EDA)
Visualização da distribuição das classes
Pré-processamento e normalização
Treinamento com Random Forest
Avaliação com matriz de confusão e relatório de classificação
Análise das features mais importantes

 Resultados

O modelo Random Forest com class_weight='balanced' conseguiu detectar a maioria das fraudes com alta precisão, sendo as features V14, V17 e V12 as mais relevantes para a identificação de transações suspeitas.
