#  Classificação Inteligente de Chamados com Machine Learning

## 📌 Sobre o projeto

O **HelpNow** é um protótipo de Machine Learning desenvolvido para a empresa fictícia FecafTrade Solutions. Seu objetivo é auxiliar a equipe de suporte de TI na classificação automática de chamados de acordo com três níveis de prioridade: **Alta, Média e Baixa**.

A proposta é facilitar a triagem dos atendimentos, contribuindo para a organização da fila de suporte e a identificação de solicitações que precisam de maior atenção.

## 🎯 Objetivos

- Desenvolver um modelo de classificação de textos.
- Comparar diferentes algoritmos de Machine Learning.
- Avaliar os modelos por meio de métricas de desempenho.
- Explorar a aplicação de Inteligência Artificial no suporte técnico.
- Identificar limitações e possibilidades de melhoria para uso futuro.

## 🛠️ Tecnologias utilizadas

- **Python**
- **Google Colab**
- **Pandas e NumPy**
- **Matplotlib**
- **Scikit-learn**
- **TF-IDF**

## 🧠 Metodologia

O desenvolvimento foi organizado nas seguintes etapas:

1. Criação de uma base demonstrativa com 60 chamados simulados.
2. Limpeza e pré-processamento dos textos.
3. Transformação dos textos em representações numéricas com TF-IDF.
4. Separação dos dados em conjuntos de treinamento e teste.
5. Treinamento e comparação de três modelos:
   - SVM linear;
   - Random Forest;
   - MLP (Multilayer Perceptron).
6. Avaliação dos resultados com métricas e visualizações.
7. Teste de classificação de um novo chamado.

## 📊 Resultados

O relatório de classificação do modelo avaliado apresentou os seguintes resultados no conjunto de teste:

| Métrica | Resultado |
|---|---:|
| Acurácia (Accuracy) | 93% |
| F1-score macro | 0,93 |
| Precisão macro | 0,94 |
| Recall macro | 0,93 |

O desempenho por classe apresentou F1-score de 0,89 para Alta, 1,00 para Baixa e 0,91 para Média.

As métricas foram obtidas em um conjunto de teste com apenas 15 exemplos. Portanto, devem ser interpretadas com cautela.

## 📈 Avaliação dos modelos

O projeto inclui recursos de avaliação como:

- Comparação de Accuracy e F1-score macro;
- Matriz de confusão;
- Relatório de classificação;
- Curva ROC e cálculo de AUC;
- Visualização das palavras mais relevantes segundo a importância calculada pelo Random Forest;
- Previsão da prioridade de um novo chamado.

## ⚠️ Limitações

A base utilizada contém somente 60 exemplos simulados, e não chamados reais da FecafTrade Solutions. Os resultados demonstram o funcionamento do protótipo, mas não garantem o mesmo desempenho em um ambiente real.

## 🔒 Aspectos éticos

Uma possível aplicação deve considerar a proteção dos dados dos usuários, a anonimização de informações pessoais, a análise de possíveis vieses e a supervisão humana na definição das prioridades dos chamados.

## 🚀 Melhorias futuras

- Ampliar a base com chamados reais autorizados e anonimizados;
- Testar o modelo com dados externos ao treinamento;
- Aplicar validação cruzada e ajustar hiperparâmetros;
- Investigar erros de classificação, especialmente em chamados de alta prioridade;
- Monitorar o desempenho continuamente;
- Integrar o protótipo a um sistema de gerenciamento de chamados.

## ▶️ Como executar

1. Ba
