# Version in English:
# Financial Performance Dashboard – Sales & Expenses Analytics  
## Business Intelligence Project

### Overview  
This project focuses on **building a financial performance dashboard** to monitor sales, expenses, and profit margins across different products.  
Developed in **Excel**, it transforms raw transactional data into **visual insights** that help track business health, identify top-performing items, and optimize decision-making.  

The dataset simulates a small business scenario, including **product catalogs, suppliers, sales entries, and expense records**, integrated through pivot tables and formulas to generate a dynamic dashboard.

---

## Project Objectives  

- Design an **interactive financial dashboard** in Excel  
- Visualize **revenue, expenses, and profit growth** over time  
- Identify the **Top 5 most profitable and best-selling products**  
- Compare **monthly income vs. expenses**  
- Present an annual summary with clear and actionable KPIs  

---

## Dataset Description  

The dashboard integrates four core datasets:

| Dataset | Description | Example Columns |
|----------|--------------|------------------|
| **Products** | Product catalog and pricing info | `Product`, `Unit Price`, `Category` |
| **Suppliers** | Supplier registry | `Supplier Name`, `Contact`, `Region` |
| **Entries** | Sales transactions | `Product`, `Quantity`, `Month`, `Revenue` |
| **Exits** | Expense records | `Product`, `Month`, `Cost` |

---

## Key Insights  

- 💰 **Revenue:** R$ 19,042.50  
- 💸 **Expenses:** R$ 5,530.00  
- 📈 **Profit Margin:** 244%  
- ☕ **Top Product:** Coffee — R$ 5,670.00 in sales  
- 📊 Sales remain stable year-round, with clear peaks in March, July, and September  

---

## Data Analysis & Design Approach  

1. **Data Cleaning**  
   - Standardized column formats and product names  
   - Removed duplicate and inconsistent entries  

2. **Base Building**  
   - Merged *entries* and *exits* datasets into a unified analytical view  
   - Created a hidden “Calculation Base” sheet to automate KPIs  

3. **Dashboard Design**  
   - One-page layout for quick executive overview  
   - Charts:  
     - *Revenue vs Expenses (monthly line chart)*  
     - *Top 5 Products (bar chart)*  
     - *Monthly Input vs Output (bar chart)*  
     - *Annual Ratio (donut chart)*  
   - Highlights: Profitability Index, Ranking, Key Financial Metrics  

---

## Business Learnings  

- Dashboards must focus on **decision-driving metrics** (profitability, volume, seasonality)  
- Building a **data base sheet** improves organization and automation  
- The ideal dashboard is **one-page**, clean, and designed for fast understanding  
- Always start with **the client’s definition of value** — what information helps them make better decisions  

---

## Tools and Technologies  

- **Software:** Microsoft Excel  
- **Techniques:** Pivot Tables, SUMIFS, Charts, Conditional Formatting  
- **Focus:** Business Intelligence & Data Visualization  

---

# Versão em Português:
# Dashboard Financeiro – Análise de Faturamento e Despesas  
## Projeto de Inteligência de Negócios (BI)

### Visão Geral  
Este projeto tem como objetivo **criar um dashboard financeiro completo** para acompanhamento de **faturamento, despesas e lucro**.  
Desenvolvido em **Excel**, o painel traduz dados brutos de vendas e saídas em **indicadores visuais claros e estratégicos**, permitindo decisões rápidas e baseadas em dados.  

O conjunto de dados simula o funcionamento de uma empresa de pequeno porte, contendo **produtos, fornecedores, entradas (vendas) e saídas (custos)**, integrados por meio de fórmulas e tabelas dinâmicas.

---

## Objetivos do Projeto  

- Construir um **dashboard interativo** para controle financeiro  
- Visualizar **faturamento, despesas e margem de lucro**  
- Identificar os **5 produtos mais vendidos e mais lucrativos**  
- Comparar **entradas e saídas mensais**  
- Exibir indicadores-chave de desempenho (KPIs) anuais  

---

## Descrição das Bases de Dados  

| Base | Descrição | Exemplo de Colunas |
|------|------------|--------------------|
| **Produtos** | Cadastro e precificação dos itens | `Produto`, `Preço Unitário`, `Categoria` |
| **Fornecedores** | Cadastro de fornecedores | `Nome`, `Contato`, `Região` |
| **Entradas** | Registros de vendas | `Produto`, `Quantidade`, `Mês`, `Receita` |
| **Saídas** | Custos e despesas | `Produto`, `Mês`, `Custo` |

---

## Principais Insights  

- 💰 **Faturamento Total:** R$ 19.042,50  
- 💸 **Despesas Totais:** R$ 5.530,00  
- 📈 **Lucro:** 244%  
- ☕ **Produto Destaque:** Café — R$ 5.670,00 em vendas  
- 📊 **Picos de vendas:** Março, Julho e Setembro  

---

## Etapas da Construção  

1. **Limpeza de Dados**  
   - Padronização dos nomes e colunas  
   - Remoção de duplicados e inconsistências  

2. **Base de Cálculo e Visão Produto**  
   - Criação de uma planilha auxiliar para cálculos automáticos  
   - Uso de fórmulas dinâmicas e referências cruzadas  
   - Planilhas ocultas para manter o dashboard limpo e funcional  

3. **Criação do Dashboard**  
   - Layout em **página única**, ideal para gestores  
   - Gráficos e Indicadores:  
     - Faturamento x Despesa (linha)  
     - Top 5 produtos (barras)  
     - Entradas x Saídas Mensais (colunas)  
     - Proporção Anual (rosca)
