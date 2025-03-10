# 📊 Análise de Dados de RH
Este projeto tem como objetivo analisar um conjunto de dados de candidatos que participaram de um treinamento oferecido por uma empresa de consultoria em Big Data e Data Science. A empresa busca identificar quais candidatos têm maior probabilidade de querer trabalhar com eles após a capacitação, diferenciando-os daqueles que apenas usam o curso para se recolocar no mercado.

## 🎯 Objetivo
Realizar análise exploratória dos dados (EDA) para entender padrões e tendências.
Limpar e transformar os dados para melhorar a qualidade da análise.
Identificar variáveis mais relevantes para prever quais candidatos são mais propensos a aceitar uma vaga na empresa.
Gerar recomendações para otimizar o processo de recrutamento.

## 📝 Etapas do Projeto
🔹 1. Carregamento e Inspeção dos Dados
Importação do dataset aug_train.csv.
Verificação do tamanho do dataset e das colunas disponíveis.
Identificação de valores ausentes e análise da distribuição dos dados.
🔹 2. Análise Exploratória
Estatísticas descritivas das variáveis numéricas e categóricas.
Visualizações utilizando Seaborn, Matplotlib e Plotly para compreender a distribuição dos dados.
Análise de correlação entre as variáveis numéricas e a variável-alvo (target).
🔹 3. Tratamento de Dados
Imputação de valores ausentes com base em padrões encontrados.
Conversão de variáveis categóricas para facilitar a análise.
Remoção de colunas irrelevantes para o objetivo da análise.
🔹 4. Identificação de Variáveis Relevantes
Cálculo da Correlação de Spearman para avaliar a relação entre as variáveis numéricas e a variável-alvo.
Uso de Weight of Evidence (WOE) e Information Value (IV) para medir a importância das variáveis categóricas.
🔹 5. Conclusões e Recomendações



## Variáveis mais relevantes para prever um bom candidato:

Índice de desenvolvimento da cidade.
Tempo de experiência.
Se está matriculado em um curso universitário.
Se possui experiência relevante na área.
Nível educacional.
Tipo de empresa onde trabalha ou trabalhou.
Especialização na graduação.
Variáveis menos relevantes:

ID do candidato.
Código da cidade onde reside.
Gênero.
Última vez que esteve empregado.
Tamanho da empresa.
Total de horas de treinamento.
Sugestões para a empresa:

Melhorar a coleta de dados para obter informações mais precisas.
Focar em candidatos de cidades menos desenvolvidas, com nível superior e pouca experiência, pois tendem a estar mais interessados em uma oportunidade de emprego.
Tornar o treinamento mais compacto, já que muitos candidatos concluem antes do tempo estimado.


# 🛠 Tecnologias Utilizadas
Linguagem: Python
Bibliotecas: Pandas, NumPy, Seaborn, Matplotlib, Plotly, SciPy, Scikit-learn, Missingno, Category Encoders
