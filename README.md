
![DIO](https://img.shields.io/badge/DIO-Desafio%20Projeto-blueviolet?style=for-the-badge)
![NotebookLM](https://img.shields.io/badge/Google-NotebookLM-4285F4?style=for-the-badge&logo=google)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![Tema](https://img.shields.io/badge/Tema-Educação%20Financeira-gold?style=for-the-badge)

# 💰 Mini Guia de Estudo: Educação Financeira e Primeiros Passos em Investimentos

> Projeto prático desenvolvido para o desafio da [DIO (Digital Innovation One)](https://www.dio.me),
> utilizando o **Google NotebookLM** como ferramenta de aprendizagem ativa com IA.

---

## 📋 Sumário

- [Contexto e Objetivos](#-contexto-e-objetivos)
- [Curadoria de Fontes](#-curadoria-de-fontes)
- [Engenharia de Prompts e Cicatrizes](#-engenharia-de-prompts-e-cicatrizes)
- [Miniguia de Estudo](#-miniguia-de-estudo)
- [Aplicação Prática com IA](#-aplicação-prática-tomada-de-decisão-com-ia)
- [Prompts Reutilizáveis](#-prompts-reutilizáveis)
- [Aprendizados e Próximos Passos](#-aprendizados-e-próximos-passos)

---

## 🎯 Contexto e Objetivos

O tema escolhido para este caderno temático foi **Educação Financeira e Primeiros Passos em Investimentos**.

Em um cenário onde o excesso de informações de "gurus financeiros" nas redes sociais gera confusão,
este projeto foca em fontes oficiais e institucionais, transformando conteúdo técnico em decisões práticas.

**Objetivos do projeto:**

| # | Objetivo |
|---|----------|
| 📊 | Consolidar fundamentos de finanças pessoais com base em fontes confiáveis |
| 🛡️ | Compreender opções de investimento seguras para iniciantes |
| 🤖 | Utilizar o NotebookLM como ferramenta de curadoria e síntese de conhecimento |
| 🧠 | Demonstrar como a IA pode apoiar a tomada de decisão baseada em dados |

---

## 📚 Curadoria de Fontes

Foram selecionadas **4 fontes institucionais** para garantir credibilidade e precisão técnica:

| Fonte | Descrição | Link |
|-------|-----------|------|
| 🏦 Banco Central do Brasil | Educação financeira, orçamento familiar e prevenção de dívidas | [bcb.gov.br](https://www.bcb.gov.br/cidadaniafinanceira) |
| 📈 CVM – Portal do Investidor | Introdução ao mercado de capitais e direitos do investidor | [investidor.gov.br](https://www.investidor.gov.br) |
| 💵 Tesouro Direto | Guia prático sobre títulos públicos e rentabilidade | [tesouro.fazenda.gov.br](https://www.tesouro.fazenda.gov.br/tesouro-direto) |
| 🛒 IDEC | Direitos do consumidor em serviços financeiros | [idec.org.br](https://idec.org.br) |

**Critérios de seleção:**
- ✔ Credibilidade institucional (órgãos governamentais e de defesa do consumidor)
- ✔ Conteúdo técnico com linguagem acessível para iniciantes
- ✔ Disponibilidade gratuita e aberta

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

Esta seção documenta a evolução das interações com a IA, incluindo erros, ajustes e aprendizados reais.

### 🔹 Prompt 1 — Genérico

**Input:**
```
"Quais são os principais investimentos para iniciantes?"
```

**Resultado:** Resposta superficial (Poupança, CDB, Tesouro Direto sem aprofundamento).

**Problema identificado:** Ausência de contexto → IA generalizou sem basear-se nas fontes.

---

### 🔹 Prompt 2 — Contextualizado

**Input:**
```
"Com base nos materiais do Banco Central e Tesouro Direto, compare
Poupança e Tesouro Selic considerando liquidez e segurança."
```

**Resultado:** Resposta precisa, com referência às fontes carregadas.

**Aprendizado:**
- ✔ Delimitar as fontes aumenta significativamente a qualidade da resposta
- ✔ Reduz o risco de alucinação da IA

---

### 🔹 Prompt 3 — Didático

**Input:**
```
"Explique juros compostos como se eu fosse um adolescente de 15 anos,
usando um exemplo com investimento em títulos públicos."
```

**Resultado:** Boa simplificação, com cuidado para manter precisão técnica ao especificar o contexto.

---

### ⚠️ Principais Cicatrizes (Lições Aprendidas)

| Problema | Causa | Solução Aplicada |
|----------|-------|------------------|
| Respostas genéricas | Prompt sem contexto delimitado | Especificar fontes e recorte temático |
| Mistura de conceitos fora do escopo | IA tende a extrapolar | Instruir: "use apenas as fontes fornecidas" |
| Perda de precisão técnica | Linguagem simplificada em excesso | Solicitar exemplo prático com termos corretos |

> 💡 **Insight-chave:** A IA não substitui o pensamento crítico; ela **amplifica sua qualidade**.

---

## 📖 Miniguia de Estudo

### 📌 1. Fundamentos — Por Onde Começar

```
Orçamento → Reserva de Emergência → Investimento
```

| Etapa | Descrição |
|-------|-----------|
| 💼 Orçamento | Controle de receitas e despesas mensais |
| 🛡️ Reserva de Emergência | 3 a 6 meses de custos fixos em ativos de alta liquidez |
| 📈 Investimento | Iniciar após estabilidade financeira conquistada |

---

### 📌 2. Glossário de Conceitos Essenciais

| Termo | Definição |
|-------|-----------|
| **Selic** | Taxa básica de juros da economia brasileira, definida pelo COPOM |
| **CDI** | Taxa de referência para empréstimos entre bancos; benchmark da renda fixa |
| **Liquidez** | Velocidade com que um investimento pode ser convertido em dinheiro disponível |
| **CDB** | Certificado de Depósito Bancário, título emitido por bancos para captar recursos |
| **FGC** | Fundo Garantidor de Créditos, proteção ao investidor até R$ 250 mil por instituição |
| **Juros Compostos** | Juros calculados sobre o capital + juros já acumulados ("juros sobre juros") |
| **Rentabilidade Real** | Retorno do investimento descontada a inflação (IPCA) |
| **Risco Soberano** | Garantia oferecida pelo próprio Governo Federal (ex: Tesouro Direto) |

---

### 📌 3. Comparativo de Investimentos para Iniciantes

| Produto | Risco | Liquidez | Garantia | Rentabilidade Aprox. |
|---------|-------|----------|----------|----------------------|
| Poupança | Baixo | Alta | FGC (R$ 250k) | ~70% da Selic |
| Tesouro Selic | Muito baixo | Alta | Governo Federal | ~100% da Selic |
| CDB (grandes bancos) | Baixo | Variável | FGC (R$ 250k) | 100–110% do CDI |

---

## 🤖 Aplicação Prática: Tomada de Decisão com IA

### 📊 Cenário

> Investidor iniciante com **R$ 5.000** busca: segurança, liquidez e baixo risco.

**Prompt utilizado no NotebookLM:**
```
"Com base nos materiais do Banco Central e Tesouro Direto, compare
Poupança e Tesouro Selic para um investidor iniciante que prioriza
segurança e liquidez."
```

### 📌 Análise Gerada

| Critério | Poupança | Tesouro Selic |
|----------|----------|---------------|
| Liquidez | Alta | Alta |
| Rentabilidade | ~70% Selic | ~100% Selic |
| Garantia | FGC | Governo Federal |
| Ideal para reserva de emergência | ✔ | ✔✔ |

### ⚙️ Decisão Recomendada: **Tesouro Selic**

**Justificativa:**
- Melhor eficiência financeira no longo prazo
- Segurança garantida pelo Governo Federal (risco soberano)
- Ideal para compor reserva de emergência com rendimento superior à poupança

**⚠️ Limitações da análise via IA:**
- Não considera perfil comportamental do investidor
- Resultado depende da qualidade e atualização das fontes fornecidas
- Não substitui orientação de um profissional certificado (CFP)

> 🚀 **Insight estratégico:** A IA não substitui a decisão financeira,
> ela melhora a qualidade do raciocínio ao organizar informações complexas de forma estruturada.

---

## 🔁 Prompts Reutilizáveis para Revisão

```markdown
1. "Explique [conceito] com base apenas nas fontes fornecidas."
2. "Compare [A] vs [B] em formato de tabela, considerando [critério]."
3. "Liste os 3 principais riscos e vantagens de [investimento]."
4. "Crie 5 perguntas de múltipla escolha para testar meu entendimento sobre [tema]."
5. "Resuma este documento em tópicos objetivos, do mais ao menos relevante."
6. "Analise [documento] e identifique os conceitos que um iniciante precisa dominar primeiro."
```

---

## 🌱 Aprendizados e Próximos Passos

### O que aprendi

- Prompts genéricos geram respostas genéricas — **contexto é tudo**
- A IA é mais útil como ferramenta de **estruturação do que de resposta pronta**
- Delimitar fontes no NotebookLM reduz alucinações e aumenta a confiabilidade
- Documentar erros e ajustes é tão valioso quanto o resultado final

### Próximos Passos

- [ ] Aplicar a mesma metodologia para análise de dados em marketing digital
- [ ] Integrar IA com dados reais (GA4 / BigQuery) para insights automatizados
- [ ] Explorar automação de relatórios financeiros com Python + IA
- [ ] Criar caderno temático sobre **Data Engineering com NotebookLM**

---

## 👩‍💻 Autora

**Marina Vieira Nagashima**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/marinanagashina/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/maryvnagashima/)

---

*Feito com 💜 como parte do ecossistema de aprendizagem da [DIO](https://www.dio.me)*
