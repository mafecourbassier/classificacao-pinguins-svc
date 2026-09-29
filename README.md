# Classificação de espécies de pinguins

Trabalho da disciplina de Inteligência Artificial para classificar pinguins das espécies Adelie, Chinstrap e Gentoo usando SVC e GridSearchCV.

**Integrantes:** Maria Fernanda Courbassier e Eliseu Portes.

## Dados utilizados

Utilizamos o arquivo `penguins_size.csv`, com 344 registros e 7 colunas.

Fonte: [Palmer Archipelago Penguin Data — Kaggle](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data).

## Etapas do trabalho

- Conferência dos valores ausentes e das linhas duplicadas.
- Separação de 80% dos registros para treino e 20% para teste.
- Preenchimento dos valores ausentes.
- Padronização das medidas e codificação das categorias.
- Busca de configurações do SVC com GridSearchCV.
- Avaliação com acurácia, relatório de classificação e matriz de confusão.

## Resultados

A melhor configuração foi o kernel linear com C = 1.

Na validação cruzada, a acurácia média foi de 99,27%. No teste, foram 68 acertos entre 69 pinguins, com acurácia de 98,55%.

O único erro foi um Adelie classificado como Chinstrap. Esses resultados correspondem à divisão dos dados utilizada neste trabalho.

## Como executar

1. Baixe `Classificacao_Pinguins.ipynb` e `penguins_size.csv`.
2. Abra o notebook no Google Colab.
3. Clique em “Executar tudo”.
4. Envie `penguins_size.csv` quando a primeira célula solicitar.

O notebook utiliza pandas, scikit-learn e matplotlib.
