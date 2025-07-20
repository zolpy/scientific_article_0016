<!-- Simulação de abas usando detalhes -->
<details open>
<summary>🇧🇷 Português</summary>

# Artigo Científico – Análise Preditiva da Produtividade do Café com ML

Este repositório contém o conjunto de dados sintético e os códigos-fonte utilizados nas análises apresentadas no artigo científico **"Análise Preditiva da Produtividade em Lavouras Cafeeiras Utilizando Modelos de Regressão e uma Base de Dados Sintética Fundamentada em um Estudo de Projeção de Safras"**.

## Conteúdo

- 📁 `data/` — Contém o conjunto de dados sintético (`base_sintetica_produtividade_cafe.xlsx`) com 10.000 registros, gerado para replicar as interações entre fatores climáticos, espectrais e de manejo na produtividade cafeeira.
- 📁 `notebooks/` — Notebooks Jupyter (`.ipynb`) detalhando cada etapa do processo:
    - `01_synthetic_data_generation.ipynb`: Geração do conjunto de dados sintético com base no estudo de referência.
    - `02_regression_model_benchmark.ipynb`: Treinamento, avaliação e comparação dos 21 modelos de regressão para prever a produtividade.
    - `03_exploratory_data_analysis.ipynb`: Análise exploratória dos dados e geração dos gráficos de correlação.
- 📁 `figures/` — Gráficos e diagramas produzidos durante o estudo, incluindo os benchmarks de R² e as tabelas de resultados.
- 📄 `results/` — Métricas de desempenho detalhadas para cada modelo em formato CSV, incluindo R², MAE, RMSE e MAPE.

## Objetivo

Este repositório visa garantir a **reprodutibilidade completa** dos experimentos descritos no artigo. Ele permite que outros pesquisadores validem os resultados, explorem o desempenho de diferentes algoritmos ou adaptem a metodologia para prever a produtividade de outras culturas agrícolas ou em diferentes regiões.

## Como Citar

Se você utilizar o código ou os dados deste repositório em seu trabalho, por favor cite o artigo original (a referência completa será adicionada após a publicação).

## Observações

- Todos os dados são **sintéticos**, gerados com base nos parâmetros estatísticos e nas relações causais descritas no estudo de projeção de safras de referência [Goulart, 2025].
- As dependências de bibliotecas Python necessárias para executar os notebooks estão listadas no arquivo `requirements.txt`.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

</details>

<details>
<summary>🇺🇸 English</summary>

# Scientific Article – ML-based Predictive Analysis of Coffee Yield

This repository contains the synthetic dataset and source code used in the analyses presented in the scientific article **"Predictive Analysis of Coffee Crop Yield Using Regression Models and a Synthetic Dataset Grounded in a Harvest Projection Study"**.

## Contents

- 📁 `data/` — Contains the synthetic dataset (`base_sintetica_produtividade_cafe.xlsx`) with 10,000 records, generated to replicate the interactions between climatic, spectral, and management factors on coffee productivity.
- 📁 `notebooks/` — Jupyter notebooks (`.ipynb`) detailing each step of the process:
    - `01_synthetic_data_generation.ipynb`: Generation of the synthetic dataset based on the reference study.
    - `02_regression_model_benchmark.ipynb`: Training, evaluation, and comparison of the 21 regression models to predict yield.
    - `03_exploratory_data_analysis.ipynb`: Exploratory analysis of the data and generation of correlation plots.
- 📁 `figures/` — Plots and diagrams produced during the study, including R² benchmarks and results tables.
- 📄 `results/` — Detailed performance metrics for each model in CSV format, including R², MAE, RMSE, and MAPE.

## Purpose

This repository aims to ensure **full reproducibility** of the experiments described in the article. It allows other researchers to validate the findings, explore the performance of different algorithms, or adapt the methodology to predict the yield of other agricultural crops or in different regions.

## How to Cite

If you use the code or data from this repository in your work, please cite the original article (full citation will be added upon publication).

## Notes

- All data are **synthetic**, generated based on the statistical parameters and causal relationships described in the reference harvest projection study [Goulart, 2025].
- The Python library dependencies required to run the notebooks are listed in the `requirements.txt` file.

## License

This project is licensed under the [MIT License](LICENSE).

</details>
