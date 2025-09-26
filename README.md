Projeto Predições — Gym Churn

Este projeto analisa os dados de clientes de uma academia e desenvolve modelos preditivos para identificar quais clientes têm maior probabilidade de cancelar o serviço (churn).
Além disso, técnicas de agrupamento (clustering) foram aplicadas para segmentar os clientes e compreender perfis de comportamento.

📂 Dataset

Arquivo utilizado: gym_churn_us.csv

Descrição: contém informações de clientes, incluindo idade, frequência de uso, duração da associação, entre outros atributos relevantes para prever a evasão.

Variável alvo: Churn (0 = permaneceu, 1 = saiu).

🔍 Etapas do Projeto

Exploração inicial dos dados (EDA)

Inspeção de colunas e valores ausentes

Estatísticas descritivas

Distribuição da variável Churn

Análise das distribuições

Comparação entre clientes que ficaram e que saíram

Principais achados:

A idade influencia a decisão de cancelamento

A frequência média de aulas está diretamente ligada à permanência

Pré-processamento

Padronização dos dados (StandardScaler)

Modelagem preditiva

Regressão Logística

Random Forest Classifier

Avaliação com métricas: acurácia, precisão, recall e classification report

Clusterização (não supervisionado)

K-means e Agrupamento Hierárquico

Visualização de clusters e dendrogramas

📊 Principais Resultados

O modelo de Random Forest apresentou melhor desempenho em relação à Regressão Logística.

Idade e engajamento/frequência foram as variáveis mais relevantes para prever o churn.

O agrupamento permitiu identificar diferentes perfis de clientes, auxiliando em estratégias de retenção.

🛠 Tecnologias e Bibliotecas

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

SciPy
