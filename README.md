# Tema: Modelagem Preditiva da Quantidade de Cancelamentos

Repositório do Trabalho de Conclusão de Curso (TCC) desenvolvido por **Jonathas de Oliveira Fernandes Costa**, no curso de Ciência da Computação (IFSEMG, 2025). O trabalho aplica técnicas de **Aprendizado de Máquina** para prever o cancelamento de clientes, apoiando empresas na adoção de estratégias preventivas de retenção.

## Objetivo
Desenvolver e avaliar modelos preditivos capazes de identificar clientes com maior propensão ao cancelamento, fornecendo informações para estratégias de retenção mais eficientes.

## Estrutura do Repositório
- `pre-processamento/` --> Notebooks de limpeza, tratamento de valores ausentes, codificação, normalização, matriz de confusão e curva ROC.
- `dados_treino_teste/` --> Armazenado os dados de treino e teste, ambos os modelos utilizam os dados desta pasta.
- `regressao_logistica/` --> Implementação, avaliação e validação do modelo de Regressão Logística.  
- `random_forest/` --> Implementação, avaliação e validação do modelo de Random Forest.  
- `xgboost/` --> Implementação, avaliação e validação do modelo de XGBoost. 

## Tecnologias Utilizadas
- Python (pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn)  
- Jupyter Notebook

## Execute os notebooks na ordem:
1. pre-processamento/
    
2. regressao_logistica/
    
3. random_forest/
    
4. xgboost/

## Resultados Principais

1. Regressão Logística: boa interpretabilidade, mas menor desempenho em dados complexos.
    
2. Random Forest: robusto e equilibrado em precisão e recall.
    
3. XGBoost: melhor desempenho geral e maior capacidade de generalização.




## Comparação dos Modelos

A tabela abaixo apresenta os resultados obtidos pelos modelos de aprendizado de máquina na previsão de cancelamento de clientes. Foram avaliadas métricas clássicas de classificação e a quantidade de cancelamentos previstos por cada abordagem.

| Modelo               | Acurácia | Precisão | Recall | F1-Score | Cancelamentos Previstos |
|----------------------|----------|----------|--------|----------|-------------------------|
| Regressão Logística  | 89,44%   | 92,32%   | 88,75% | 90,50%   | 48.067                  |
| Random Forest        | 99,96%   | 99,99%   | 99,93% | 99,96%   | 49.969                  |
| XGBoost              | 99,98%   | 100,0%   | 99,97% | 99,98%   | 49.985                  |


