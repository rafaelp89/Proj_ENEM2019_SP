# Análise Estatística dos Dados do ENEM 2019 - Estado de São Paulo

## 📌 Sobre o Projeto
Este projeto teve como objetivo realizar uma análise estatística detalhada dos dados do ENEM 2019 no estado de São Paulo, utilizando Python e bibliotecas como `pandas` e `numpy`. O trabalho foi baseado no curso *"Análise Estatística com Python"* do professor Luciano Galdino, combinando teoria e prática para explorar conceitos estatísticos fundamentais na análise de dados.

---

## 📊 Principais Etapas do Projeto

### 1. **Coleta e Limpeza de Dados**
   - Extração dos dados do site do INEP ([http://inep.gov.br/microdados](http://inep.gov.br/microdados)).
   - Filtragem do dataset para incluir apenas o estado de São Paulo.
   - Limpeza e seleção das variáveis relevantes para o estudo.

### 2. **Amostragem**
   - Utilização de técnicas de amostragem aleatória (simples, sistemática, estratificada e por conglomerado) para extrair dados de escolas da cidade de Campinas.

### 3. **Análise Exploratória**
   - **Distribuição de Frequências**: Análise da distribuição dos dados em municípios como Sorocaba, com uso de histogramas para visualização.
   - **Medidas de Tendência Central**: Cálculo de média, mediana e moda para entender o comportamento das notas.
   - **Medidas de Dispersão**: Análise de variância, desvio padrão e gráficos Boxplot para compreender a variabilidade dos dados.

### 4. **Correlação e Regressão**
   - Investigação da relação entre variáveis por meio de gráficos de dispersão e análise de normalidade.
   - Aplicação de regressão linear para prever resultados.

### 5. **Probabilidade**
   - Uso de distribuições como Binomial e Poisson para resolver problemas práticos, como calcular a probabilidade de um número específico de estudantes terminar a prova em um determinado tempo.
   - Análise de probabilidades em municípios como Guarulhos e Bauru.

### 6. **Testes de Hipótese**
   - Aplicação de testes T e Z para comparar médias, como a média das notas de um colégio específico com a média do estado de São Paulo.

---

## 📌 Conclusão
O projeto oferece uma análise estatística abrangente dos dados do ENEM 2019 em São Paulo, abordando desde estatística descritiva até inferencial. Os resultados fornecem *insights* valiosos sobre o desempenho dos estudantes, servindo como base para futuras pesquisas e decisões educacionais.

---

## 🛠️ Tecnologias Utilizadas
- **Python** (principal linguagem de análise)
- **Bibliotecas**: `pandas`, `numpy` (para manipulação de dados e cálculos estatísticos)
- **Visualização**: Histogramas, Boxplots, Gráficos de Dispersão

---

## 📂 Estrutura do Repositório
- `data/`: Contém os datasets utilizados (originais e processados).
- `notebooks/`: Jupyter Notebooks com as análises realizadas.
- `results/`: Gráficos e tabelas gerados durante o estudo.

---

## 🔍 Próximos Passos
- Expandir a análise para outros estados baseado nos métodos usados Estado de São Paulo.
- Incluir técnicas de machine learning para previsões mais avançadas.
- Desenvolver um dashboard interativo para visualização dos dados.

---

**Nota**: Este projeto foi desenvolvido como parte de um treinamento em análise estatística com Python, visando aplicar conceitos teóricos em um contexto prático e relevante.
