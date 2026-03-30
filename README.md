# 📊 Superstore Sales Analysis

## O Contexto

A Superstore é uma rede varejista americana com operações em todo o território nacional.
Apesar do crescimento consistente no volume de vendas nos últimos anos, a liderança identificou
uma preocupação: **algumas regiões e categorias geravam alto faturamento, mas margens de lucro
preocupantemente baixas — ou até negativas.**

Fui designado como analista responsável por investigar os dados de vendas entre 2016 e 2019,
com o objetivo de identificar os principais gargalos de rentabilidade e apresentar insights
que pudessem orientar decisões estratégicas da empresa.

---

## 🎯 Perguntas de Negócio

As investigações foram guiadas por quatro perguntas centrais:

1. **Quais subcategorias de produtos geram prejuízo mesmo com alto volume de vendas?**
2. **O desconto concedido nas vendas prejudica a rentabilidade do negócio?**
3. **Qual segmento de cliente é proporcionalmente mais lucrativo?**
4. **Quais cidades estão entre as maiores em vendas, mas operam com margens negativas?**

---

## 🔍 Principais Descobertas

**Subcategorias com prejuízo**
Tables e Bookcases figuram entre as subcategorias mais vendidas, porém operam
com prejuízo acumulado. A análise indica que os descontos aplicados nessas categorias
superam a margem do produto — sinalizando a necessidade de revisão da política de preços.

**Impacto do desconto**
Foi identificada uma correlação negativa de -0.22 entre desconto e lucro.
Pedidos com desconto acima de 20% concentram a maior parte dos prejuízos registrados,
evidenciando que a prática indiscriminada de descontos compromete diretamente a rentabilidade.

**Segmento mais eficiente**
O segmento Home Office, embora com o menor faturamento absoluto ($ 429.653),
apresenta a melhor margem de lucro (14%) — superando Consumer (11.5%) e Corporate (13%).
Isso indica que clientes Home Office geram mais valor por real vendido.

**Cidades com margem negativa**
Philadelphia (-12.7%), Houston (-15.7%) e Chicago (-13.7%) estão entre as Top 10 cidades
em volume de vendas, porém operam com margens negativas — ou seja, quanto mais vendem,
mais prejuízo acumulam. New York City, por outro lado, lidera em vendas ($ 256.368)
com margem saudável de 24.2%, servindo como referência de operação eficiente.

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Finalidade |
|---|---|
| Python 3.x | Linguagem principal |
| Pandas | Manipulação e limpeza dos dados |
| Matplotlib | Visualizações gráficas |
| Seaborn | Gráficos estatísticos |
| Jupyter Notebook | Ambiente de análise |

---

## 📁 Estrutura do Projeto

```
superstore-analysis/
│
├── analise.ipynb        # Notebook com análise completa
├── README.md            # Este arquivo
└── data/
    └── superstore.csv   # Dataset utilizado
```

---

## ▶️ Como Executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/superstore-analysis

# Instale as dependências
pip install pandas matplotlib seaborn jupyter

# Execute o notebook
jupyter notebook analise.ipynb
```

---

## 📌 Sobre o Dataset

- **Fonte:** [Superstore Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Período:** 2016 a 2019
- **Volume:** 9.994 registros de vendas
- **Variáveis:** categoria, subcategoria, região, cidade, segmento, vendas, lucro e desconto

---

## 👨‍💻 Autor

**Felipe Feliciano**
Profissional de TI em transição para Análise de Dados e Business Intelligence
10+ anos de experiência em ambientes corporativos | SAP & SAP BW | MBA em Data Science

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Felipe_Feliciano-blue)](https://www.linkedin.com/in/felipefeliciano-dados)
