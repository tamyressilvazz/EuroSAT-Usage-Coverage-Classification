# 🛰️ Classificação de Uso e Cobertura do Solo com Deep Learning e EuroSAT

## 📖 Descrição

Este projeto explora técnicas de **Visão Computacional** e **Deep Learning** para classificação automática de imagens de satélite utilizando o dataset **EuroSAT**.

O objetivo é desenvolver um modelo capaz de identificar diferentes tipos de cobertura terrestre a partir de imagens capturadas pelo satélite Sentinel-2, contribuindo para aplicações de monitoramento ambiental, planejamento urbano e análise geoespacial.

---

## 🎯 Objetivos

* Aplicar técnicas de Deep Learning em imagens de sensoriamento remoto;
* Realizar o pré-processamento e preparação dos dados;
* Treinar uma Rede Neural Convolucional (CNN) para classificação multiclasse;
* Avaliar o desempenho do modelo utilizando métricas de classificação;
* Analisar a capacidade de generalização do modelo em imagens de satélite.

---

## 📊 Dataset

### EuroSAT

O projeto utiliza o dataset **EuroSAT**, um conjunto de dados amplamente utilizado em pesquisas de classificação de imagens de satélite.

Características do dataset:

* Aproximadamente 27.000 imagens RGB;
* Resolução de 64 × 64 pixels;
* Imagens extraídas do satélite Sentinel-2;
* 10 categorias de uso e cobertura do solo.

### Classes Disponíveis

| Classe               | Descrição                 |
| -------------------- | ------------------------- |
| AnnualCrop           | Culturas agrícolas anuais |
| Forest               | Florestas                 |
| HerbaceousVegetation | Vegetação herbácea        |
| Highway              | Rodovias                  |
| Industrial           | Áreas industriais         |
| Pasture              | Pastagens                 |
| PermanentCrop        | Culturas permanentes      |
| Residential          | Áreas residenciais        |
| River                | Rios                      |
| SeaLake              | Lagos e áreas marítimas   |

---

## 🧠 Metodologia

O fluxo geral do projeto consiste em:

1. Carregamento do dataset;
2. Pré-processamento das imagens;
3. Normalização dos dados;
4. Divisão em conjuntos de treino, validação e teste;
5. Treinamento da rede neural convolucional;
6. Avaliação do desempenho do modelo;
7. Visualização e análise dos resultados.

---

## 🛠️ Tecnologias Utilizadas

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* OpenCV
* Jupyter Notebook

---

## 📈 Avaliação

O desempenho do modelo pode ser avaliado utilizando métricas como:

* Accuracy
* Precision
* Recall
* F1-Score
* Matriz de Confusão

Essas métricas permitem analisar a capacidade do modelo em diferenciar corretamente as classes presentes no dataset.

---

## 🌍 Aplicações

Modelos de classificação de imagens de satélite possuem diversas aplicações práticas:

* Monitoramento ambiental;
* Identificação de áreas urbanas;
* Agricultura de precisão;
* Mapeamento territorial;
* Gestão de recursos naturais;
* Estudos climáticos e ambientais.

---

## 🚀 Como Executar

### Instalar Dependências

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn opencv-python
```

### Executar o Projeto

Abra o notebook do projeto:

```bash
jupyter notebook
```

Execute todas as células para reproduzir os experimentos e resultados.

---

## 📚 Conceitos Aplicados

* Deep Learning
* Redes Neurais Convolucionais (CNN)
* Classificação de Imagens
* Visão Computacional
* Sensoriamento Remoto
* Aprendizado Supervisionado
* Processamento de Imagens
* Avaliação de Modelos

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido com fins educacionais para aplicação prática de técnicas de Deep Learning em problemas de classificação de imagens de satélite, utilizando um dos principais datasets da área de sensoriamento remoto.

---

## 📖 Referências

Helber, P., Bischke, B., Dengel, A., & Borth, D. (2019).

**EuroSAT: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification.**

Dataset disponível em:

https://github.com/phelber/EuroSAT
