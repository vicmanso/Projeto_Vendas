# 📊 Análise de Vendas – Projeto com Python

Este projeto tem como objetivo realizar uma análise exploratória de dados de vendas ao longo do ano de 2024, utilizando a linguagem Python e diversas bibliotecas de análise e visualização de dados. O foco é extrair insights relevantes sobre o desempenho por produto, por vendedor e por mês.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python** – linguagem principal para análise de dados.
- **Jupyter Notebook** – ambiente utilizado para desenvolvimento e organização do projeto.
- **Pandas** – manipulação e análise de dados (agrupamentos, filtros, cálculos).
- **NumPy** – apoio em operações numéricas.
- **Matplotlib** – geração de gráficos de linha e pizza.
- **Seaborn** – visualização estatística com gráficos estilizados.
- **Plotly** – gráficos interativos e dinâmicos.

---

## 🔎 Etapas do Projeto

### 1. **Importação e leitura da base de dados**
- Arquivo Excel contendo colunas como: data da venda, produto, vendedor, quantidade, preço unitário e valor total.

### 2. **Limpeza e transformação dos dados**
- Conversão da coluna de data para o formato datetime.
- Criação de colunas auxiliares como `mês` e `valor_total`.

### 3. **Análises mensais**
- Agrupamento por mês para calcular:
  - Quantidade total de produtos vendidos.
  - Faturamento total por mês.

**Destaques:**
- **Julho**: maior quantidade de produtos vendidos.
- **Março**: maior faturamento, impulsionado por um pico de vendas no dia **03/03**.

### 4. **Análises por produto**
- Identificação da quantidade total vendida de cada produto no ano.
- **Tablet** foi o produto mais vendido, especialmente em março por **Eva** e **Daniel**.

### 5. **Análises por vendedor**
- Total de produtos vendidos por vendedor.
- Faturamento total por vendedor.

**Resultados:**
- **Daniel**: maior faturamento do ano.
- **Eva** e **Daniel**: líderes em número de vendas.
- **Carlos**: menor número de produtos vendidos.
- **Alice**: menor faturamento total.

### 6. **Análise diária (março)**
- Criação de gráfico de linha mostrando a quantidade de vendas por dia.
- Identificação de pico de vendas no dia **03/03**.

---

## 📈 Visualizações Criadas

- **Gráfico de linha**: vendas por dia em março.
- **Gráficos de pizza**: percentual de vendas por produto e por vendedor.
- **Gráficos de barras**: comparações entre meses e entre vendedores.

---

## 📌 Conclusões

- **Julho** teve o maior volume de vendas, possivelmente por sazonalidade.
- **Março** foi o mês mais lucrativo, com pico de vendas no dia **03/03**.
- **Eva** e **Daniel** foram os vendedores com maior número de vendas.
- **Daniel** também foi o vendedor com maior faturamento (vendas de produtos de maior valor).
- **Tablet** foi o produto mais vendido do ano.
- **Carlos** e **Alice** apresentaram os piores desempenhos (quantidade e faturamento).

---

## 💡 Aprendizados

Este projeto foi uma excelente oportunidade para aplicar e reforçar conhecimentos de:

- Análise exploratória de dados com **Pandas**.
- Agrupamentos, sumarizações e filtros.
- Criação de visualizações personalizadas com **Matplotlib**, **Seaborn** e **Plotly**.
- Interpretação de dados e geração de **insights de negócio**.

---

## 🖥️ Apresentação Final

Como parte da entrega do projeto, foi desenvolvida uma **apresentação em PowerPoint** contendo os principais insights e conclusões obtidos na análise de dados, com foco na **visualização clara das métricas de desempenho por vendedor, por produto e por mês**.
