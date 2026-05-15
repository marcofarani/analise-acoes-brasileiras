# 📊 Análise Comparativa de Ações Brasileiras

> Projeto desenvolvido para a disciplina de **Lógica de Programação**, com foco em análise exploratória de dados do mercado financeiro brasileiro utilizando Python.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![yfinance](https://img.shields.io/badge/yfinance-API-orange)
![Status](https://img.shields.io/badge/Status-Concluído-success)

---

## 🎯 Objetivo

Realizar uma análise comparativa do desempenho de **4 grandes empresas da B3** (Bolsa de Valores brasileira) entre **janeiro de 2023 e maio de 2026**, utilizando bibliotecas de ciência de dados em Python.

## 🏢 Empresas Analisadas

| Empresa | Ticker | Setor |
|---------|--------|-------|
| 🏭 **Vale S.A.** | VALE3.SA | Mineração |
| 🍺 **Ambev S.A.** | ABEV3.SA | Bebidas |
| 🏦 **Itaú Unibanco** | ITUB4.SA | Financeiro |
| 🏦 **Banco do Brasil** | BBAS3.SA | Financeiro |

---

## 🛠️ Tecnologias Utilizadas

- **Python 3** — linguagem principal
- **yfinance** — coleta de dados históricos da Yahoo Finance
- **Pandas** — manipulação e análise dos dados
- **Matplotlib** & **Seaborn** — visualização gráfica
- **Google Colab** — ambiente de desenvolvimento

---

## 📈 Análises Realizadas

- ✅ Coleta automatizada de dados históricos via API
- ✅ Cálculo de **estatísticas descritivas** (média, máximo, mínimo, desvio padrão)
- ✅ Análise da **variação percentual** no período
- ✅ Visualização gráfica da **evolução do preço de fechamento**
- ✅ Comparativo entre as empresas

---

## 🚀 Como Executar

### Opção 1 — Google Colab (recomendado)
1. Clique no arquivo `analise_acoes_brasileiras.ipynb`
2. Clique no botão **"Open in Colab"** no topo
3. Execute as células em sequência (`Shift + Enter`)

### Opção 2 — Localmente
```bash
# Clone o repositório
git clone https://github.com/marcofarani/analise-acoes-brasileiras.git

# Acesse a pasta
cd analise-acoes-brasileiras

# Instale as dependências
pip install yfinance pandas matplotlib seaborn jupyter

# Abra o notebook
jupyter notebook analise_acoes_brasileiras.ipynb
```

---

## 📊 Principais Resultados

O notebook apresenta gráficos individuais para cada ativo, mostrando a evolução dos preços de fechamento ao longo do período analisado, além de tabelas com estatísticas detalhadas que permitem comparar o desempenho das empresas.

---

## 👨‍🎓 Autor

**Marco Peixoto Farani**  
📚 Disciplina: Lógica de Programação  
👨‍🏫 Professor: Sérgio  
📅 2026

[![GitHub](https://img.shields.io/badge/GitHub-marcofarani-181717?logo=github)](https://github.com/marcofarani)

---

⭐ Se este projeto te ajudou de alguma forma, deixe uma estrela no repositório!
