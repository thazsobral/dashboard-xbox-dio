# Análise de Vendas: Xbox Game Pass Subscriptions

Este projeto foi desenvolvido como parte de um curso de **Análise de Dados com Excel**, com o objetivo de processar, analisar e visualizar métricas de desempenho de assinaturas do serviço Xbox Game Pass. O foco principal recai sobre a distribuição de planos, renovação automática e o impacto financeiro de serviços adicionais (add-ons).

## 📌 Visão Geral do Projeto

O conjunto de dados simula o histórico de vendas de assinaturas, permitindo uma análise profunda sobre o comportamento dos assinantes e a receita gerada. Através deste projeto, foram respondidas perguntas estratégicas de negócio para auxiliar na tomada de decisão sobre promoções e retenção de clientes.

## 📂 Estrutura do Repositório

O arquivo principal `xbox-data.xlsx` está organizado nas seguintes seções (convertidas para CSV para facilitar a visualização no GitHub):

* **`Bases`**: Contém o dataset bruto com informações detalhadas de cada assinante.
* **`Cálculos`**: Tabela dinâmica e fórmulas utilizadas para extrair os principais KPIs.
* **`Detalhes`**: Filtros específicos aplicados para auditoria de planos anuais e renovações.
* **`Dashboard`**: Estrutura visual consolidada para apresentação dos resultados.
* **`Assets`**: Identidade visual (paleta de cores e logos) utilizada no projeto.

## 📊 Dicionário de Dados

Os dados brutos na aba `Bases` contêm as seguintes colunas:

| Coluna | Descrição |
| :--- | :--- |
| **Subscriber ID** | Identificador único do assinante. |
| **Name** | Nome do cliente. |
| **Plan** | Tipo de plano (Core, Standard, Ultimate). |
| **Start Date** | Data de início da assinatura. |
| **Auto Renewal** | Indica se a renovação automática está ativa (Yes/No). |
| **Subscription Type** | Periodicidade do pagamento (Monthly, Quarterly, Annual). |
| **EA Play / Minecraft** | Indica se o usuário adquiriu passes de temporada adicionais. |
| **Total Value** | Valor total da transação, considerando plano e extras. |

## 💡 Perguntas de Negócio Respondidas

A análise focou em quatro pilares principais (Aba `Cálculos`):

1.  **Faturamento Total de Planos Anuais**: Consolidação de toda a receita proveniente de compromissos de longo prazo.
2.  **Impacto da Renovação Automática**: Comparação de faturamento entre planos anuais com e sem renovação automática (fator crítico para previsibilidade de caixa).
3.  **Desempenho de Add-ons (EA Play)**: Total de vendas geradas pela integração com o serviço EA Play.
4.  **Engajamento com Minecraft**: Volume de vendas do passe de temporada do Minecraft, segmentado por tipo de plano.

## 🛠️ Ferramentas Utilizadas

* **Microsoft Excel**: Utilizado para limpeza de dados, criação de tabelas dinâmicas e construção do dashboard final.
* **Análise Estatística**: Aplicação de funções agregadas e filtros avançados para extração de insights.

## 📈 Insights Principais

* Os planos do tipo **Ultimate** apresentam maior taxa de adesão a serviços adicionais (EA Play e Minecraft).
* Assinaturas com **Renovação Automática** representam uma parcela significativa da receita em planos trimestrais, indicando uma oportunidade de conversão para o modelo anual.

---
**Autor:** [Thalles Sobral]
**Data:** Abril de 2026
