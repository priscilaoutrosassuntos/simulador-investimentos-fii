# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Projeto desenvolvido como desafio da trilha de **Excel** da [DIO](https://www.dio.me/), com o objetivo de aplicar conceitos de fórmulas, automação de cálculos e organização de dados em uma ferramenta prática de simulação de investimentos em Fundos de Investimento Imobiliário (FIIs).

## 🎯 Objetivo do Projeto

Construir, no Excel, uma ferramenta que ajude um investidor a responder perguntas comuns antes de investir em FIIs, como:

- Quanto investir por mês?
- Por quanto tempo manter o investimento?
- Qual taxa de rendimento mensal considerar?
- Qual será o patrimônio acumulado e os dividendos mensais ao final do período?
- Como distribuir o valor investido entre os diferentes tipos de FII, de acordo com o perfil de risco (Conservador, Moderado ou Agressivo)?

A planilha automatiza esses cálculos, eliminando a necessidade de fazer contas manuais e oferecendo uma visão clara do potencial retorno do investimento.

## 🧠 Conceitos Aplicados

- Fórmulas financeiras (juros compostos aplicados a aportes mensais)
- Cálculo de patrimônio acumulado e dividendos mensais
- Cenários comparativos (2, 5, 10, 20 e 30 anos)
- Uso de tabelas de apoio para simular perfis de investidor (Conservador, Moderado, Agressivo)
- Distribuição percentual do valor investido entre categorias de FII (Papel, Tijolo, Híbridos, FoFs, Desenvolvimento, Hotelaria)
- Organização de dados em múltiplas abas (parâmetros de simulação separados da base de perfis)

## 🗂️ Estrutura da Planilha

O arquivo `Simulador_Investimentos_FIIs.xlsx` está organizado em duas abas:

### `Planilha1` — Simulador
| Seção | Descrição |
|---|---|
| **Configurações** | Dados de entrada, como salário e rendimento médio da carteira |
| **Investimento Mensal** | Valor a investir por mês, prazo (em anos) e taxa de rendimento mensal, com cálculo automático do patrimônio acumulado e dos dividendos mensais |
| **Cenários** | Comparação do patrimônio acumulado e dividendos projetados para 2, 5, 10, 20 e 30 anos |
| **Perfil** | Seleção do perfil de investidor (Conservador / Moderado / Agressivo) e valor mensal a investir |
| **Distribuição por Tipo de FII** | Percentual sugerido e valor calculado para cada categoria de fundo, de acordo com o perfil escolhido |

### `Planilha2` — Base de Perfis
Tabela de apoio com os percentuais de alocação recomendados para cada combinação de **perfil x tipo de FII**, utilizada como referência para preencher automaticamente a distribuição na `Planilha1`.

## ▶️ Como Usar

1. Baixe o arquivo `Simulador_Investimentos_FIIs.xlsx` deste repositório.
2. Abra no Excel (ou Google Sheets/LibreOffice Calc).
3. Preencha os campos de entrada:
   - Valor a investir por mês
   - Por quantos anos pretende investir
   - Taxa de rendimento mensal esperada
   - Perfil de investidor desejado
4. Confira automaticamente:
   - O patrimônio acumulado projetado
   - Os dividendos mensais estimados
   - A comparação entre diferentes horizontes de tempo (cenários)
   - A sugestão de distribuição do valor investido entre os tipos de FII

> ⚠️ Este projeto tem finalidade **exclusivamente educacional**, feito como exercício de aprendizado de Excel. Não constitui recomendação de investimento.

## 🖼️ Capturas de Tela

<!-- Adicione aqui prints da planilha em uso, salvos na pasta /images -->
<!-- Exemplo: -->
<!-- ![Simulador - Investimento Mensal](images/simulador-investimento-mensal.png) -->
<!-- ![Simulador - Distribuição por Perfil](images/simulador-distribuicao-perfil.png) -->

## 📚 Aprendizados

Durante o desenvolvimento deste desafio, pratiquei:

- Estruturação de uma planilha financeira com múltiplas seções lógicas
- Criação de fórmulas para simular juros compostos com aportes mensais
- Organização de dados de apoio em abas separadas para manter a planilha principal limpa
- Documentação técnica de um projeto para compartilhamento público

## 🚀 Tecnologias

- Microsoft Excel

## 📎 Sobre o Desafio

Este projeto faz parte da trilha de estudos da [Digital Innovation One (DIO)](https://www.dio.me/), no módulo de Excel, cujo objetivo é aplicar conhecimentos de fórmulas e automação de cálculos na construção de ferramentas práticas de simulação financeira.

---

Feito com 📈 para fins de estudo.
