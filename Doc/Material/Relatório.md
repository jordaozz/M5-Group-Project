# Relatório Técnico: Importação, Tratamento e Visualização de Dados**

## **1. Introdução**

Este relatório detalha o processo de importação, tratamento e visualização de dados das 10 maiores moedas, destacando as escolhas metodológicas e justificativas por trás dessas decisões.

## **2. Processo de Importação e Tratamento de Dados**

Os dados foram obtidos do Kaggle, uma fonte confiável e amplamente utilizada para conjuntos de dados públicos. O uso do Python e de bibliotecas como Pandas e Numpy para o tratamento dos dados foi escolhido devido à sua eficiência e flexibilidade. A limpeza dos dados, incluindo a remoção de valores nulos e duplicados, foi necessária para garantir a integridade dos dados. A seleção das 10 maiores moedas foi baseada em critérios de volume de negociação ou outra métrica relevante, garantindo a representatividade do conjunto de dados.

## **3. Preparação para o MySQL**

Para importação dos dados para o MySQL, optou-se por criar um script executável em Python (index.py) para transferir os dados tratados para a pasta do XAMPP. Essa abordagem foi escolhida devido à sua simplicidade e eficiência, permitindo uma integração perfeita com o ambiente MySQL utilizando a query.sql. Esta escolha também considerou a facilidade de automação e reprodutibilidade do processo.

## **4. Visualização de Dados com Tableau**

A escolha do Tableau para visualização dos dados foi fundamentada em sua reputação como uma das principais ferramentas de análise visual disponíveis. O Tableau oferece uma ampla gama de recursos para criar dashboards e análises interativas, permitindo uma exploração detalhada dos dados das moedas selecionadas. Esta decisão foi tomada com base na necessidade de apresentar os dados de forma clara e acessível, facilitando a interpretação e a comunicação dos insights obtidos.
