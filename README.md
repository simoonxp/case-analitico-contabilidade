# 📊 Case Analítico — Projeção de Mercado e Estratégia de Aquisição

<p align="left">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tipo-Case%20Analítico-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Setor-Contabilidade%20Digital-orange?style=for-the-badge" />
</p>

---

## 📌 Visão Geral

Quis testar até onde uma análise de dados poderia ir quando o objetivo não fosse apenas prever um número, mas transformá-lo em uma decisão de negócio.

O resultado foi este case: uma projeção do volume de abertura de empresas no Brasil em 2026, com diagnóstico de incerteza por setor e simulação de estratégia de aquisição para uma contabilidade digital.

---

## 🎯 Pergunta de Negócio

> **Quantas empresas serão abertas no Brasil em 2026 — e o que uma contabilidade digital deveria fazer com essa informação?**

---

## 🛠️ Stack Utilizada

| Ferramenta | Uso |
|---|---|
| **Python** | Linguagem principal |
| **Pandas** | Manipulação e análise de dados |
| **NumPy** | Cálculos estatísticos |
| **Matplotlib / Seaborn** | Visualização de dados |
| **Estatística descritiva** | Média, desvio, sazonalidade |
| **Séries temporais** | Análise de tendência e ciclos |
| **Forecasting** | Projeção com índices sazonais |

---

## 🔄 Pipeline do Projeto

```
Dados brutos
    → Tratamento e limpeza
    → Análise exploratória (EDA)
    → Identificação de sazonalidade
    → Projeção 2026
    → Validação e diagnóstico de erro
    → Simulação de market share
    → Estratégia de aquisição
```

---

## 📊 Estrutura do Case

### 1. Panorama Histórico (2018–2025)
- Volume mensal de abertura de empresas no Brasil
- Crescimento de **140 mil (2018)** para **335 mil (2025)** aberturas/ano
- Sazonalidade clara: pico em julho e agosto; queda em dezembro

### 2. Projeção 2026

**Método:** multiplicação dos índices sazonais mensais históricos pela tendência de crescimento médio dos últimos 3 anos (2023–2025).

**Resultado:**
- **Projeção central:** 373.408 empresas
- **Intervalo:** 334 mil – 413 mil

> **Nota metodológica:** o intervalo foi calculado aplicando ±1 desvio padrão dos erros históricos do modelo sobre a projeção central — não se trata de um intervalo de confiança estatístico formal (como 95% em modelos ARIMA), mas de uma faixa de variação realista baseada no comportamento passado do modelo.

### 3. Diagnóstico de Incerteza
- Erro médio do modelo por setor
- Setor mais volátil: Psicologia (erro médio de 17,4%)
- Causa: mudança estrutural regulatória + crescimento variando de +16% a +90% sem padrão repetível

### 4. Simulação de Market Share

> **Cenário hipotético:** em uma simulação de 20% de participação de mercado — uma meta ambiciosa usada aqui para fins de dimensionamento — seria necessário atingir **74.682 contratos** em 2026, distribuídos mensalmente conforme os índices sazonais.

### 5. Estratégia de Aquisição
- **LinkedIn:** público de decisão racional (TI, Consultoria, Advocacia)
- **Instagram / WhatsApp:** decisão rápida (Medicina, Psicologia)
- **Timing:** concentrar investimento 2 meses antes do pico sazonal
- **Prioridade:** defender setores consolidados + capturar setor em aceleração regulatória

---

## 📂 Arquivo

| Arquivo | Descrição |
|---|---|
| `Case_Portfolio.pptx` | Apresentação completa do case |

---

## 👨‍💻 Autor

**Felipe Simon**
- 🎓 Ciência de Dados — FATEC
- 📍 São Bernardo do Campo, SP
- 💼 [LinkedIn](https://www.linkedin.com/in/felipe-simon-83ba10352)
- 📧 simonhot.com@gmail.com
