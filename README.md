# EBAC - Cientista de Dados | Modulo 15
# Churn Analysis for Telecommunications

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED.svg?logo=docker)](Dockerfile)
![EBAC](https://img.shields.io/badge/EBAC-Cientista%20de%20Dados-blue?style=for-the-badge)

**[PT-BR](#sobre-o-projeto) | [English](#about-the-project)**

</div>

---

<a name="sobre-o-projeto"></a>

## Sobre o Projeto

Este projeto faz parte da Formacao **Cientista de Dados** da [EBAC (Escola Britanica de Artes Criativas e Tecnologia)](https://ebaconline.com.br) -- Modulo 15. O foco e a analise completa de churn em telecomunicacoes, aplicando tecnicas avancadas de modelagem preditiva, otimizacao de hiperparametros e interpretabilidade de modelos.

O projeto avanca sobre o trabalho do [Modulo 14](https://github.com/galafis/EBAC-PROJETO-CIENTISTA-DE-DADOS-M14) (pre-processamento), agora focando na construcao, avaliacao e comparacao de modelos de machine learning.

---

## Pipeline de Modelagem

```mermaid
flowchart LR
    A[Dataset\nLimpo M14] --> B[Feature\nEngineering]
    B --> C[Selecao de\nVariaveis]
    C --> D[Treinamento\nde Modelos]
    D --> E[Otimizacao de\nHiperparametros]
    E --> F[Avaliacao\ne Metricas]
    F --> G[Modelo\nFinal]

    style A fill:#1e3a5f,color:#fff,stroke:#1e3a5f
    style D fill:#4a90d9,color:#fff,stroke:#2c5f8a
    style G fill:#155724,color:#fff,stroke:#155724
```

---

## Conteudo do Repositorio

| Arquivo | Descricao |
|---|---|
| `Analise_Churn_Telecomunicacoes.ipynb` | Notebook principal com pipeline completo |
| `CHURN_TELECON_MOD08_TAREFA.csv` | Base de dados de clientes Telecom |
| `LICENSE` | Licenca MIT |
| `README.md` | Documentacao do projeto |

## Como Executar

```bash
git clone https://github.com/galafis/EBAC-PROJETO-CIENTISTA-DE-DADOS-M15.git
cd EBAC-PROJETO-CIENTISTA-DE-DADOS-M15
pip install pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook Analise_Churn_Telecomunicacoes.ipynb
```

## Aplicacao na Industria

A previsao de churn e uma das aplicacoes mais valiosas de ML em telecomunicacoes, permitindo acoes proativas de retencao que podem reduzir custos de aquisicao de novos clientes em ate 5x.

---

<a name="about-the-project"></a>

## English

### About the Project

This project is part of the **Data Scientist** program at [EBAC](https://ebaconline.com.br) -- Module 15. It focuses on a complete churn analysis in telecommunications, applying advanced techniques in predictive modeling, hyperparameter optimization, and model interpretability.

The project builds upon [Module 14](https://github.com/galafis/EBAC-PROJETO-CIENTISTA-DE-DADOS-M14) (preprocessing), now focusing on building, evaluating, and comparing machine learning models.

### How to Run

```bash
git clone https://github.com/galafis/EBAC-PROJETO-CIENTISTA-DE-DADOS-M15.git
cd EBAC-PROJETO-CIENTISTA-DE-DADOS-M15
pip install pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook Analise_Churn_Telecomunicacoes.ipynb
```

---

## Licenca | License

Distribuido sob a licenca MIT. Veja [LICENSE](LICENSE). | Distributed under the MIT License. See [LICENSE](LICENSE).

---

*Gabriel Demetrios Lafis* | [github.com/galafis](https://github.com/galafis)
