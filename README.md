# Descrição do projeto

Este projeto, desenvolvido em parceria com a Escola DNC, teve como objetivo criar um dashboard analítico e dinâmico para a Athos Digital, uma agência de marketing digital, com foco no setor de produção agropecuária e, especificamente, em operações de Barter. O sistema se integra aos dados de ERPs dos clientes para fornecer dashboards personalizáveis, buscando expandir a variedade de modelos existentes.

A base de dados foi estruturada em cinco planilhas no Google Sheets—Dados das Operações, Insumos Aplicados, Lista de Insumos, Projeção Financeira e Dados sobre o Compromisso (CPR)—e alimentada com dados de operações de soja, alguns gerados por IA e outros baseados em dados reais.

O projeto resultou na criação de um relatório no Power BI para uma cooperativa fictícia, a "SoyCoop", com quatro painéis: Visão Geral, Informações Técnicas de Produção e Produtos, Financeiro das Operações e Simulação. Os dashboards foram projetados para serem claros e orientados para a tomada de decisão, utilizando KPIs de produção, financeiro e de risco. O painel de simulação permite testar cenários e o impacto de variações em fatores como preço e custo.  

*Projeto realizado com mais dois membros e todas as decisões foram tomadas em conjunto.

---
 ## Sobre os dados

*Os dados apresentados neste dashboard são inteiramente fictícios e foram gerados exclusivamente para fins de demonstração. Não representam informações reais de empresas, clientes ou operações comerciais. Essa abordagem foi adotada para garantir a privacidade e a confidencialidade de dados sensíveis.*

---

## Visão Geral:​

KPIs: Faturamento Esperado, Custo Total, Margem Projetada, Quantidade de Sacas Projetadas e Quantidade Total de Sacas Comprometidas.​

Gráficos comparativos agrupados por estado, como: Barras com a produtividade média por hectare; Barras empilhadas mostrando a proporção do custo total tomado pelo valor negociado no barter; Barras comparando faturamento médio por hectare vs. custo médio por hectare.​

Tabela detalhada com informações financeiras e produtivas das fazendas SoyCoop, agrupadas por estado.​

![Visão Geral](https://github.com/rafaelaraujomj/Projeto-Barter/blob/main/Vis%C3%A3o%20Geral.png?raw=true)

---

## Análise de produção

### Análise técnica e produtiva:​

Filtros: Fazenda e Estado.​

KPIs: Média de Hectares, Média de Sacas Produzidas, Média de Sacas Produzidas por Hectare, Média de Sacas Comprometidas por Hectare e Média do Break-even por Hectare.​

Gráficos:​

- Barras verticais 100% empilhadas mostrando a proporção das sacas comprometidas em relação às sacas esperadas;​
- Treemap dos insumos mais utilizados pelas fazendas, agrupados por categoria e unidades utilizadas.​
- Mapa geográfico apontando as fazendas e sua contribuição produtiva;​
- Gráfico de Linhas comparando produção por hectare com o Break-Even de sacas por hectare.​

![Painel de Produtividade](https://github.com/rafaelaraujomj/Projeto-Barter/blob/main/Painel%20de%20Produtividade.png?raw=true)

---

## Análise Financeira

Filtros: Fazenda e Estado.​

KPIs: Faturamento Esperado, Custo Total, Margem Projetada e valor do Barter.​

Gráficos:​

- Gráfico de barras verticais mostrando a margem esperada por fazenda, com formatação condicional para destacar as margens negativas.​
- Gráfico de pizza mostrando a divisão de gastos.​
- Gráfico de Linhas comparando o custo por hectare e receita.​
- Gráfico de faixas mostrando o ROI% de cada fazenda com formatação condicional destacando os valores negativos.
- Mapa geográfico apontando as fazendas e sua contribuição financeira;​

![Painel Financeiro](https://github.com/rafaelaraujomj/Projeto-Barter/blob/main/Painel%20Financeiro.png?raw=true)

---

## Simulador

Para tornar a página de simulação funcional foi utilizado o recurso de parâmetro de intervalo numérico, disponível na aba de Modelagem de Dados do Power BI.​ Foram criados seis slicers, cada um representando um fator. A proposta é simular como as variações percentuais em cada fator impactam os KPIs principais de cada fazenda.​

​

KPIs: Faturamento simulado, custo simulado, margem simulada e produção simulada​

Gráficos:​

- Gráfico de Linhas comparando a produção simulada por hectare e o break-even.​
- Gráfico de barras verticais mostrando a margem esperada por fazenda.​
- Gráfico de faixas mostrando o ROI% de cada fazenda com formatação condicional destacando os valores negativos.​

![Simulador](https://github.com/rafaelaraujomj/Projeto-Barter/blob/main/Paiinel%20de%20Simula%C3%A7%C3%A3o.png?raw=true)
