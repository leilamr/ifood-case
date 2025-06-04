# 📦 iFood Data Science Case – Otimização de Cupons com Machine Learning

Este projeto foi desenvolvido como parte do case técnico de Data Science do iFood.

---

## 🧠 Objetivo

Desenvolver uma solução baseada em dados que auxilie na decisão de **qual oferta deve ser enviada para cada cliente**, maximizando engajamento e reduzindo o desperdício de recursos promocionais.

---

## 💻 Ambiente

Todo o projeto foi executado em **[Databricks Community Edition](https://community.cloud.databricks.com/)**, utilizando **PySpark** para processamento e LightGBM Ranker para treinamento.

---

## 📈 Dados Utilizados

O projeto utiliza três conjuntos de dados fornecidos:

- `customers.json`: informações demográficas e de cadastro de ~17k clientes  
- `offers.json`: metadados de ofertas promocionais (BOGO, desconto, informacional)  
- `transactions.json`: histórico de ~300k eventos (transações, recebimento e uso de ofertas)

---

## 🔍 Etapas do Projeto

### 1. Análise Exploratória de Dados (EDA)

- Estudo do perfil dos clientes (idade, limite de crédito, histórico de uso de cupons)
- Identificação de padrões de engajamento com diferentes tipos de ofertas e canais
- Geração de insights estratégicos para a etapa de modelagem

### 2. Processamento de Dados

- Limpeza, tratamento de outliers e conversão de dados temporais
- Junção dos três datasets em um **dataset unificado** por cliente e oferta
- Engenharia de features relevantes para o modelo

### 3. Modelagem Preditiva

- Utilização de um **modelo de ranking (LightGBM Ranker)** para priorizar ofertas por cliente
- Avaliação por métricas de ranking (ex: NDCG@5 = 66%)
- Geração de recomendações personalizadas por cliente

---

## 🎯 Conclusão

A solução desenvolvida mostra que **o uso de dados reais e modelos inteligentes pode transformar a distribuição de cupons em uma alavanca estratégica**. Com isso, o iFood pode:

- Engajar mais clientes com menos esforço
- Reduzir custos com ofertas mal direcionadas
- Escalar decisões personalizadas com eficiência

---

## 🚀 Execução

Este projeto foi executado 100% em notebooks do **Databricks Community Edition**.  
Com as versões:
- PySpark 3.3.2
- LightGBM 4.6.0

---

## 📩 Contato

Caso tenha dúvidas ou feedback sobre o projeto, fique à vontade para abrir uma issue ou me contatar por [linkedin](https://www.linkedin.com/in/rodrigues-leila/).

---

