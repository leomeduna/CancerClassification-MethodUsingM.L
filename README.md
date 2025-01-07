## Classificação de Câncer Maligno x Benigno com Machine-Learning

# Contexto:
Este projeto utiliza uma base de dados de câncer para prever se um tumor é maligno ou benigno, com base em características extraídas de exames médicos. O objetivo é implementar um modelo de classificação para auxiliar na identificação precoce de casos malignos, fornecendo suporte para diagnósticos mais precisos.

# Objetivo:
Desenvolver e avaliar um modelo de aprendizado de máquina que classifique tumores como malignos ou benignos, utilizando o algoritmo Random Forest Classifier. O foco é alcançar alta precisão e sensibilidade para minimizar erros em diagnósticos críticos.

# Estrutura do Projeto -
    Coleta e Preparação de Dados
    Importação da base de dados.
    Codificação da variável de diagnóstico: M (Maligno) → 1 e B (Benigno) → 0.
    Seleção das 5 variáveis mais correlacionadas com o diagnóstico.
    Treinamento e Teste do Modelo
    Divisão dos dados em conjuntos de treino (75%) e teste (25%).
    Treinamento do modelo utilizando Random Forest Classifier.
    Avaliação do Modelo

# Métricas de avaliação:
    Precision (Precisão): Proporção de diagnósticos malignos corretos.
    Recall (Sensibilidade): Capacidade de identificar casos malignos.
    F1-Score: Equilíbrio entre precisão e recall.
    Criação da matriz de confusão e análise de erros.
    Geração da curva ROC e cálculo da AUC para medir a capacidade de distinção entre as classes.
    
# Resultados e Interpretação
    F1-Score: 0.96, indicando um equilíbrio sólido entre precisão e sensibilidade.
    Curva ROC (AUC): 0.98, demonstrando excelente capacidade de classificação.

# Resultados
O modelo alcançou alta eficácia, com métricas de precisão e recall acima de 0.94.
A análise gráfica (Curva ROC e matriz de confusão) reforça a confiabilidade do modelo em diagnósticos médicos.
