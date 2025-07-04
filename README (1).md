
# 👕 Previsão de Estoque de Camisas de Times com Amazon SageMaker Canvas


## 🎯 Objetivo

Prever a quantidade de camisas de futebol que precisarão ser reabastecidas em estoque, com base nas vendas dos últimos dias. O modelo foi criado usando o SageMaker Canvas, visando facilitar a reposição automatizada de produtos.

---

## 🚀 Etapas Realizadas

1. ✅ Criação da conta na AWS
2. ✅ Acesso ao SageMaker Canvas via console AWS
3. ✅ Criação de um dataset com dados fictícios de vendas de camisas
4. ✅ Upload do dataset em formato CSV
5. ✅ Criação do modelo de Machine Learning no Canvas
6. ✅ Definição da variável alvo: `estoque_futuro`
7. ✅ Treinamento automático do modelo
8. ✅ Geração de previsões
9. ✅ Exportação dos resultados
10. ✅ Documentação do processo neste repositório

---

## 📊 Dataset Utilizado

Foi criado um dataset fictício com base em vendas simuladas de camisas de quatro grandes clubes de futebol brasileiro:

- **São Paulo**
- **Corinthians**
- **Santos**
- **Palmeiras**

### Estrutura do Dataset:
| time         | estoque_atual | vendas_ultimos_30_dias | estoque_futuro |
|--------------|----------------|--------------------------|----------------|
| São Paulo    | 120            | 85                       | 35             |
| Corinthians  | 90             | 70                       | 20             |
| Santos       | 100            | 45                       | 55             |
| Palmeiras    | 75             | 60                       | 15             |

A variável alvo usada para previsão foi `estoque_futuro`, ou seja, a quantidade estimada necessária para o próximo período.

---

## 🤖 Resultados

O SageMaker Canvas treinou automaticamente o modelo com boa precisão. A previsão indicou a necessidade de reposição mais urgente para alguns clubes com maior volume de vendas.

### Exemplo de Previsão Final:

| Time         | Previsão de Estoque (em unidades) |
|--------------|-----------------------------------|
| São Paulo    | 35                                |
| Corinthians  | 20                                |
| Santos       | 55                                |
| Palmeiras    | 15                                |

---

## 🧠 Tecnologias Utilizadas

- [AWS SageMaker Canvas](https://aws.amazon.com/sagemaker/canvas/)
- Machine Learning No-Code
- GitHub
