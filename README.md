# Superstore Modelo de Mitigação de Prejuízos

Abra no Colab para visualizar gráficos interativos com Plotly.

[![Colab](https://img.shields.io/badge/Colab-Superstore%20Modelo%20de%20Mitigação%20de%20Prejuízos-yellow?style=flat&logo=google-colab)](https://colab.research.google.com/github/pedro-kaneko/superstore-modelo-de-mitigacao-de-prejuizos/blob/main/superstore_modelo_de_mitigacao_de_prejuizos.ipynb)

![Imagem de Capa](cover.png)

## Introdução

Este projeto explora o dataset "Superstore", que representa um e-commerce de produtos de tecnologia, mobília e material de escritório, atendendo aos públicos consumidor, corporativo e home-office. O conjunto de dados contém informações detalhadas sobre transações comerciais, clientes, produtos, localização, datas de pedidos e entregas. O objetivo é abordar os problemas financeiros enfrentados pela empresa devido a descontos excessivos e otimizar a formulação de preços.

## Objetivos

Mitigar prejuízos causados por descontos excessivos em produtos através de um modelo preditivo que estima a margem de lucro antes dos produtos serem anunciados na plataforma. O sucesso será medido pela redução percentual de transações prejudiciais.

## Resumo do Projeto

A Análise Exploratória de Dados (EDA) revelou que, apesar do crescimento no volume de vendas e no lucro, a empresa enfrenta prejuízos significativos, atribuídos principalmente a descontos excessivos. Foi desenvolvido um Modelo Preditivo de Regressão usando Machine Learning para estimar a margem de lucro com base em variáveis como categoria, sub-categoria, preço e desconto. Testes mostraram uma redução de até 96,8% nas transações prejudiciais. Foi proposto um Experimento Controlado Randomizado (RCT) para validar a eficácia do modelo, com os resultados sendo avaliados pelo Teste de Fisher. Recomenda-se a implementação do modelo em um ambiente controlado e o monitoramento contínuo.

## Etapas do Projeto

1. **Análise da Performance de Vendas e Financeira**:
   - Avaliação do desempenho geral das vendas e lucros para identificar áreas problemáticas e padrões emergentes.

2. **Identificação de Problemas e Pontos de Atenção**:
   - Identificação das principais causas de prejuízos, como a má formulação de preços e descontos excessivos.

3. **Desenvolvimento de Soluções**:
   - Proposição de um modelo preditivo para estimar a margem de lucro e ajustar preços com base em dados históricos e variáveis relevantes.

4. **Implementação e Teste das Soluções**:
   - Aplicação do modelo preditivo e realização de testes para verificar a eficácia da solução proposta em ambiente controlado.

5. **Validação e Análise dos Resultados**:
   - Condução de experimentos controlados para validar o modelo em ambiente de produção, análise dos resultados e avaliação do impacto na redução de prejuízos.

6. **Recomendações e Ações Futuras**:
   - Apresentação de recomendações para a implementação do modelo em produção e sugestões para monitoramento contínuo e ajustes futuros.

7. **Apresentação dos Resultados**:
   - Compilação dos resultados obtidos e apresentação das conclusões e relevância das soluções propostas para a mitigação de prejuízos.

## Metodologia

1. **Análise Exploratória de Dados (EDA) e Visualizações**:
   - Realização de uma análise preliminar dos dados para entender o comportamento das variáveis e identificar padrões ou anomalias.
   - Utilização de visualizações gráficas para explorar o volume de vendas, margem de lucro e impacto dos descontos.

2. **Análise Estatística**:
   - Aplicação de métodos estatísticos para determinar a relação entre variáveis, como descontos e margem de lucro.
   - Uso de testes estatísticos para validar hipóteses e identificar correlações significativas.

3. **Desenvolvimento do Modelo Preditivo**:
   - **Divisão dos Dados**: Separação do conjunto de dados em conjuntos de treinamento, validação e teste.
   - **Pré-processamento**: Implementação de um pipeline para limpeza, transformação e normalização dos dados.
   - **Treinamento**: Treinamento do modelo com o conjunto de dados de treinamento.
   - **Importância das Features**: Avaliação da importância das variáveis para entender o impacto de cada feature no modelo.

4. **Validação do Modelo**:
   - **Avaliação de Performance**: Medição da performance do modelo em ambiente de validação e teste utilizando métricas como erro médio absoluto (MAE), erro quadrático médio (RMSE) e coeficiente de determinação (R²).
   - **Avaliação Classificatória**: Análise das métricas de precisão, taxa de falsos positivos (FPR) e taxa de falsos negativos (FNR) para mensurar a capacidade do modelo em distinguir transações lucrativas de prejudiciais.

5. **Planejamento e Implementação do Experimento Randomizado Controlado (RCT)**:
   - **Design do Experimento**: Criação de um experimento controlado para validar o modelo em ambiente de produção.
   - **Definição de Grupos**: Estabelecimento de grupos de controle e tratamento e aplicação de métodos de amostragem e estratificação para garantir a representatividade.

6. **Validação Estatística dos Resultados do Experimento**:
   - **Teste Estatístico**: Aplicação do Teste de Fisher para comparar amostras e validar estatisticamente a eficácia do modelo preditivo.
   - **Análise dos Resultados**: Interpretação dos resultados do experimento para confirmar a redução significativa de transações prejudiciais.

7. **Acompanhamento e Ajustes**:
   - **Monitoramento Contínuo**: Acompanhamento da performance do modelo e ajustes baseados em novos dados e feedback do ambiente de produção.
   - **Revisão Periódica**: Atualização do modelo para manter a precisão e a eficácia na mitigação de prejuízos.

## Ferramentas e Bibliotecas Utilizadas

- Google Colaboratory
- Python
- Pandas
- Numpy
- Scikit-learn
- SciPy
- Math
- Matplotlib
- Plotly
- ChatGPT (assistente de codificação)

## Conteúdo do Projeto

- **Conjunto de dados utilizado na análise**: `DadosSuperstore2-230321-143628.xlsx`
- **Notebook de desenvolvimento com explicação técnica**: `superstore-modelo-de-mitigacao-de-prejuizos.ipynb`
- **Apresentação executiva**: `superstore-apresentacao-executiva.pdf`
- **Arquivo de requisitos**: `requirements.txt` (lista de bibliotecas e dependências necessárias para executar o projeto)

## Como Utilizar

1. Clone o repositório.
2. Instale as dependências listadas no `requirements.txt`.
3. Execute o notebook para iniciar a análise.
