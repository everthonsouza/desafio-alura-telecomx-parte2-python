
# 📉 Predição de Evasão de Clientes em Telecom com Machine Learning

Este projeto tem como objetivo prever a evasão de clientes (churn) em uma empresa de telecomunicações utilizando algoritmos de **Machine Learning**. A análise envolve desde o pré-processamento dos dados até a avaliação do modelo e interpretação dos principais fatores que influenciam a evasão.

---

## 🛠 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [scikit-learn (sklearn)](https://scikit-learn.org/)
- [imblearn - SMOTE](https://imbalanced-learn.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)

---

## 📁 Estrutura do Projeto

```
├── dados_normalizados.csv    # Base de dados em csv
├── TelecomX_BR_parte2.ipynb  # Jupyter Notebooks com experimentos e códigos realizados
└── README.md                 # Este arquivo
```

---

## 🔍 Etapas do Projeto

### 1. 📊 Análise Exploratória de Dados (EDA)
- Limpeza e transformação dos dados
- Análise de correlação entre variáveis
- Visualizações interativas com Plotly

### 2. ⚖️ Balanceamento de Classes com SMOTE
- Utilização do **SMOTE** para lidar com o desbalanceamento da classe "Churn"
- Geração de novos exemplos sintéticos da classe minoritária

### 3. 🧠 Treinamento do Modelo
- Testes dos modelo **RandomForestClassifier**, **DecisionTreeClassifier** e **KNeighborsClassifier**
- Separação entre treino e teste
- Otimização e avaliação dos modelos

### 4. 📈 Avaliação de Performance do modelo escolhido - RandomForestClassifier
- **Acurácia**: `0.836`
- **Precisão**: `0.809`
- **Recall**: `0.881`
- **F1-score**: `0.843`

### 5. 🧮 Importância das Variáveis
Principais variáveis que influenciam a evasão:
- `Meses_Contrato`
- `Tipo_Contrato`
- `Total_Mes`
- `Total_Gasto`
- `Custo_Diario`
- `Serviços adicionais` (TV, Segurança, Internet)

---

## 🎯 Conclusões e Estratégias de Retenção

Com base nos resultados do modelo, foram propostas **estratégias de retenção** como:
- Incentivo à migração para contratos de longo prazo
- Redução da percepção de custo mensal
- Oferta de pacotes adicionais personalizados
- Fidelização nos primeiros meses de contrato

---

## 📌 Requisitos

- Python >= 3.8  
- pandas  
- scikit-learn  
- imblearn  
- plotly  

---

> Desenvolvido por [Everthon Souza] ⚙️
