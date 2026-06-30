# 💰 Dashboard de Finanças Pessoais — Excel

**Stack:** Microsoft Excel (Tabelas Dinâmicas, PROCV, SOMASE, Gráficos Dinâmicos, Slicers)
**Tema:** Controle e análise de receitas, despesas e saldo financeiro pessoal
**Objetivo:** Organizar 636 lançamentos financeiros (2023-2025) em um dashboard interativo que permite acompanhar a saúde financeira por mês, categoria e tipo

---

## 📖 O Contexto

Esta planilha simula o controle financeiro pessoal de um período de aproximadamente 3 anos (2023, 2024 e 2025), cobrindo receitas (salário, renda extra, renda passiva) e despesas por categoria (moradia, subsistência, transporte, saúde, lazer e vestuário). A estrutura foi construída em 5 abas interligadas — base de lançamentos, aba de análise e dashboard.

---

## 🗂️ Estrutura da Planilha

| Aba | Conteúdo |
|---|---|
| `Base` | 636 lançamentos com data, tipo, categoria, descrição, valor e saldo acumulado |
| `Análise Gabarito` | 8 tabelas dinâmicas consolidando receitas, despesas e saldos por período e categoria |
| `Dashboard Gabarito` | Painel visual com 13 gráficos dinâmicos e slicers interativos |
| `Análise do Zero` | Aba em branco para exercício próprio |
| `Dashboard do Zero` | Aba em branco para exercício próprio |

---

## ⚙️ Recursos Utilizados

- **8 Tabelas Dinâmicas** alimentando os indicadores do dashboard
- **13 Gráficos Dinâmicos** para visualização de receitas, despesas, saldo e categorias
- **PROCV (VLOOKUP):** busca e categorização de lançamentos
- **SOMASE (SUMIF):** soma condicional por categoria e tipo
- **SE (IF) e SEERRO (IFERROR):** tratamento de exceções e lógica condicional
- **TEXTO (TEXT):** formatação de datas para agrupamento mensal
- **Slicers** para filtro interativo por mês e tipo de lançamento

---

## 📊 Principais Números (2023-2025)

### 💵 Visão Geral

| Indicador | Valor |
|---|---|
| Receita total | R$ 328.865,00 |
| Despesa total | R$ 315.976,00 |
| Saldo líquido | R$ 12.889,00 |
| Taxa de poupança média | ~3,9% da receita |
| Total de lançamentos | 636 registros |

---

### 📈 Receita por Categoria

| Categoria | Total |
|---|---|
| Salário | R$ 252.496,00 |
| Renda extra | R$ 49.671,00 |
| Renda passiva | R$ 16.497,00 |
| Retirada de aplicações | R$ 10.201,00 |

**Insight:** O salário representa **76,8%** da receita total. A renda extra (freelas e comissões) contribui com quase R$ 50 mil — 15,1% da receita. Uma renda passiva de R$ 16 mil indica algum nível de investimento já em andamento.

---

### 📉 Despesa por Categoria

| Categoria | Total | % do Total |
|---|---|---|
| Moradia | R$ 147.088,00 | 46,5% |
| Subsistência | R$ 56.915,00 | 18,0% |
| Transporte | R$ 41.876,00 | 13,2% |
| Saúde | R$ 40.689,00 | 12,9% |
| Lazer | R$ 15.160,00 | 4,8% |
| Vestuário | R$ 14.248,00 | 4,5% |

**Insight:** Moradia isolada consome **46,5%** de toda a despesa — padrão acima do recomendado por educadores financeiros (que sugerem até 30%). Saúde (R$ 40,6 mil) supera Transporte em relevância, o que aponta investimento considerável nessa categoria.

---

### 📅 Meses com Saldo Negativo

| Mês | Saldo |
|---|---|
| Março | -R$ 6.897,00 |
| Setembro | -R$ 3.596,00 |
| Agosto | -R$ 1.629,00 |

**Insight:** 3 meses do período registraram saldo negativo (despesas superaram receitas). Março foi o pior — quase R$ 7 mil negativos, possivelmente relacionado a IPTU/IPVA ou outros gastos sazonais de início de ano.

---

## 🧠 Sobre as Habilidades Aplicadas

Nível: **intermediário em Excel** — construção e interpretação de tabelas dinâmicas, uso de PROCV e PROCH para relacionar dados entre abas, SOMASE para consolidação por categoria, e análise de indicadores para extrair insights financeiros. Neste projeto especificamente, aplicado por meio de 8 tabelas dinâmicas, 13 gráficos dinâmicos e fórmulas de busca e agregação distribuídas entre as abas.

---

## 🎥 Demonstração

![Dashboard em funcionamento](dashboard.gif)

---

## 📁 Estrutura do Projeto

```
Dashboard-Financas-Pessoais-Excel/
├── Dashboard_Finanças_Pessoais.xlsx  # Planilha completa (5 abas)
├── dashboard.gif                      # Demonstração interativa do dashboard
└── README.md                          # Este arquivo
```

---

## 🚀 Como Usar

1. Baixe o arquivo `Dashboard_Finanças_Pessoais.xlsx`
2. Abra no Microsoft Excel
3. Use os **slicers** no Dashboard para filtrar por mês ou tipo de lançamento
4. Adicione novos lançamentos na aba `Base` e atualize as tabelas dinâmicas para ver os dados refletidos no dashboard

---

📫 **Contato:** [LinkedIn](https://www.linkedin.com/in/simaosantana-a744372a7) · simaojoaosantana@gmail.com
