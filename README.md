# Predição de Pokémon Lendários

## 📊 Descrição

Este projeto tem como objetivo prever se um Pokémon é ou não lendário com base em seus atributos. Utilizamos **Análise Exploratória de Dados (EDA)** para entender melhor o conjunto de dados e selecionamos cuidadosamente algumas **features** para exibição. Demonstramos que, na ciência de dados, a combinação ideal de atributos depende da imaginação e da curiosidade ao lidar com os dados.

Além da EDA, treinamos um modelo de **Machine Learning** simples que, em conjunto com **Optuna** para otimização de hiperparâmetros e o poderoso **CatBoost**, alcançou uma **acurácia de 98%** na predição de Pokémon lendários.

## 🚀 Tecnologias Utilizadas

- **Linguagem de Programação:** Python
- **Bibliotecas:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - CatBoost
  - Optuna


🔍 Metodologia
Análise Exploratória de Dados (EDA):

Exploração das principais características dos Pokémon.
Visualização de distribuições e correlações entre atributos.
Pré-processamento:

Tratamento de valores faltantes.
Codificação de variáveis categóricas, se necessário.
Seleção de Features:

Escolha das features mais relevantes para a predição.
Consideração de que combinações de features podem variar conforme a criatividade e curiosidade do cientista de dados.
Treinamento do Modelo:

Utilização do CatBoost como algoritmo de classificação.
Otimização de hiperparâmetros com Optuna.
Avaliação:

Medição da acurácia do modelo.
Validação cruzada para garantir a robustez dos resultados.
🏆 Resultados
Acurácia: 98%
Modelo Utilizado: CatBoost com otimização via Optuna
