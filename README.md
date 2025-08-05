📉 Previsão de Evasão de Clientes (Churn Prediction)
Este projeto tem como objetivo prever a evasão de clientes (churn) com base em variáveis comportamentais, 
contratuais e demográficas, utilizando modelos de Regressão Logística e Árvore de Decisão.

🧠 Modelos Utilizados
- Regressão Logística (com normalização)
- Árvore de Decisão (sem normalização)

📊 Etapas do Projeto
1. Carregamento e pré-processamento dos dados
2. Divisão da base em treino e teste (70/30)
3. Normalização dos dados para modelos sensíveis à escala
4. Criação e avaliação dos modelos
5. Avaliação com métricas:
   - Acurácia
   - Precisão
   - Recall
   - F1-score
   - Matriz de Confusão
   - Curva ROC
6. Análise de Overfitting/Underfitting
7. Extração da importância das variáveis (coeficientes da Regressão Logística)

📈 Principais Resultados
- Modelo com melhor desempenho:** _(Ex: Regressão Logística com F1-score de 0.87)_
- Principais variáveis que influenciam a evasão:
  - Fidelidade do contrato
  - Forma de pagamento
  - Tempo como cliente
  - Uso de serviços como suporte técnico, segurança, etc.

📌 Estratégias de Retenção Recomendadas
Com base nas variáveis mais influentes:
- Oferecer benefícios para contratos de longo prazo
- Incentivar pagamentos automáticos com desconto
- Investir em serviços com alto índice de cancelamento
- Criar campanhas personalizadas para clientes com maior probabilidade de evasão

▶️ Como Executar
1. Abra o notebook no Google Colab

