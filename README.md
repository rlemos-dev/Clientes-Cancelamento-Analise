# Clientes-Cancelamento-Analise

Análise de dados focada em identificar padrões de cancelamento de clientes (churn) e propor estratégias para retenção.

---

## 🚀 Sobre o Projeto

Este projeto tem como objetivo analisar uma base de dados de clientes para entender os principais fatores que levam ao cancelamento de serviços.

A análise foi realizada utilizando Python, com foco em:
- Tratamento de dados
- Análise exploratória (EDA)
- Visualização de dados
- Geração de insights estratégicos

---

## 🧠 Problema de Negócio

Uma empresa com mais de **800 mil clientes** identificou um alto índice de cancelamentos e precisa entender:

- Por que os clientes estão cancelando?
- Quais perfis têm maior probabilidade de churn?
- O que pode ser feito para reduzir cancelamentos?

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Plotly

---

## 📂 Etapas da Análise

### 1. Importação e Visualização dos Dados
- Leitura da base de dados (.csv)
- Remoção de colunas irrelevantes (CustomerID)
- Visualização inicial

### 2. Tratamento de Dados
- Remoção de valores nulos
- Verificação de tipos de dados
- Limpeza geral da base

### 3. Análise Inicial
- Cálculo da taxa de cancelamento
- Distribuição percentual de clientes que cancelaram

### 4. Análise Exploratória
- Criação de gráficos para todas as variáveis
- Comparação entre clientes que cancelaram vs. não cancelaram
- Identificação de padrões relevantes

### 5. Geração de Insights e Estratégias

Com base nos dados, foram identificadas algumas ações para reduzir o cancelamento:

- ❌ Evitar planos mensais (maior taxa de churn)
- 📞 Monitorar clientes com muitas ligações ao call center
- ⏳ Controlar atrasos acima de 20 dias
- 🎯 Focar em estratégias para diferentes faixas etárias

---

## 📈 Principais Insights

- Clientes com plano mensal têm maior chance de cancelamento
- Alto número de ligações ao suporte indica insatisfação
- Atrasos frequentes estão diretamente ligados ao churn
- Idade também influencia no comportamento de cancelamento

---

## 💡 Possíveis Melhorias

- Aplicar modelos de Machine Learning para prever churn
- Criar dashboard interativo (Power BI ou Streamlit)
- Implementar segmentação de clientes
- Automatizar análises

---

## ▶️ Como Executar

1. Clone o repositório:
git clone https://github.com/rlemos-dev/Clientes-Cancelamento-Analise.git

2. Instale as dependências:
pip install pandas plotly

3. Execute o notebook:
jupyter notebook

---

## 📌 Observações

- Projeto com foco educacional e prático em análise de dados
- Base de dados utilizada para fins de estudo

---

## 👨‍💻 Autor

Desenvolvido por Rafael Lemos
