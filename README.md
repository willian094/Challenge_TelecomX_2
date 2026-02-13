# 📊 Telecom X – Previsão de Evasão de Clientes (Churn)

## 📌 Sobre o Projeto
Este projeto tem como objetivo desenvolver modelos de Machine Learning capazes de prever a evasão (churn) de clientes da Telecom X. A análise busca identificar padrões de comportamento e variáveis que influenciam o cancelamento de serviços, permitindo a criação de estratégias de retenção mais eficazes.

---

## 🎯 Objetivos
- Preparar os dados para modelagem (tratamento, encoding e normalização)
- Treinar modelos preditivos de classificação
- Avaliar o desempenho com métricas apropriadas
- Identificar as variáveis mais relevantes para churn
- Propor estratégias de retenção baseadas em dados

---

## 🗂️ Estrutura do Projeto

TelecomX-Churn/
│
├── dados_tratados.csv
├── notebook.ipynb
├── README.md


---

## ⚙️ Etapas do Pipeline
1. Remoção de variáveis irrelevantes (ex: `customerID`)
2. Codificação de variáveis categóricas (One-Hot Encoding)
3. Análise exploratória e correlação
4. Divisão treino/teste (80/20)
5. Treinamento dos modelos
6. Avaliação com métricas de classificação
7. Interpretação das variáveis mais importantes

---

## 🤖 Modelos Utilizados

### 1. Regressão Logística
- Modelo linear e interpretável
- Necessita normalização das variáveis numéricas
- Permite entender o impacto direto de cada variável na evasão

### 2. Random Forest
- Modelo não linear baseado em árvores
- Não requer normalização
- Captura relações complexas entre variáveis

---

## 📊 Métricas de Avaliação
Os modelos foram avaliados utilizando:
- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de Confusão

O foco principal foi o **Recall**, pois identificar clientes que irão evadir é crítico para ações de retenção.

---

## 🔎 Principais Fatores que Influenciam a Evasão
Com base na análise dos modelos, os fatores mais relevantes foram:

### Fatores que aumentam o churn
- Contratos mensais (Month-to-month)
- Alto valor de cobrança mensal
- Método de pagamento eletrônico
- Internet via fibra óptica

### Fatores que reduzem o churn
- Maior tempo como cliente (tenure alto)
- Contratos de longo prazo (1 ou 2 anos)
- Serviços adicionais (suporte técnico e proteção de dispositivos)

---

## 💡 Estratégias de Retenção Sugeridas
- Programas de fidelização para clientes novos
- Incentivo à migração para contratos de longo prazo
- Revisão de planos com alto custo mensal
- Oferta de serviços adicionais para aumentar retenção
- Uso de score preditivo para priorizar clientes em risco

---

## 🚀 Conclusão
O modelo Random Forest apresentou melhor desempenho preditivo, enquanto a Regressão Logística ofereceu maior interpretabilidade.  
Os resultados indicam que tempo de relacionamento, tipo de contrato e valor mensal são os principais determinantes da evasão.

A aplicação do modelo permite à Telecom X antecipar cancelamentos e agir de forma estratégica para aumentar a retenção de clientes.

---

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Seaborn / Matplotlib
- Google Colab

---
