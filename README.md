# projeto-evasao-escolar
Projeto de machine learning para prever evasão escolar com base em características de alunos.

Previsão de Evasão Escolar com Machine Learning
🎯 Descrição do Projeto
Este projeto tem como objetivo prever a evasão escolar de estudantes com base em características comportamentais e socioeducacionais, utilizando técnicas de análise de dados e aprendizado de máquina (machine learning).

📥 Coleta de Dados
Fonte: Kaggle
Dataset: xAPI-Edu-Data.csv
Descrição: A base contém registros de estudantes, incluindo:
Gênero
Relação com o responsável
Participação em aula (raisedhands)
Acesso a recursos (VisITedResources)
Discussões e visualizações de anúncios
Satisfação dos pais
Dias de ausência
Status do estudante (Class: H, M ou L)
📊 Análise Exploratória
A análise exploratória revelou padrões importantes:

Alunos com baixa participação (raisedhands) tendem a apresentar status L (baixo desempenho, indicador de risco de evasão).
A falta de acesso a recursos e menor participação em discussões também aparecem mais entre os alunos em risco.
Pais menos satisfeitos ou com menor presença escolar contribuem para o aumento da evasão.
Visualizações utilizadas:

📌 Distribuição da variável alvo Class
📌 Evasão por relação com o responsável (Relation)
📌 Nível de participação por faixas
📌 Matriz de confusão e importância das variáveis (modelagem)
🧠 Modelagem
Foi treinado um modelo de Random Forest com os seguintes passos:

Pré-processamento

Codificação de variáveis categóricas (LabelEncoder)
Transformação da variável alvo: evasao = 1 para L (evasores), 0 para M e H
Divisão da base

70% Treino / 30% Teste
Métricas do Modelo

Acurácia: 90%
Recall (evasão): 87%
F1-score (evasão): 85%
O modelo apresentou ótimo desempenho na identificação de alunos com risco de evasão.

📈 Visualizações de Resultados
🔷 Matriz de Confusão
Matriz de Confusão

🔷 Importância das Variáveis
Importância das Variáveis

✅ Conclusões
A combinação de características como baixa participação, ausência e insatisfação dos pais permite prever com eficiência o risco de evasão escolar.
O modelo pode ser utilizado para ações preventivas por escolas e instituições públicas.
Próximos passos possíveis: uso de outros algoritmos, ajuste de hiperparâmetros e coleta de mais dados históricos.
📂 Estrutura do Repositório
projeto-evasao-escolar/ ├── xAPI-Edu-Data.csv ├── Semantix.ipynb ├── imgs/ │ ├── matriz_confusao.png │ └── importancia_variaveis.png ├── README.md

✍️ Autor

John Valentim
Projeto realizado como parte do programa de empregabilidade (EBAC / Semantix).
