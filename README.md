<p align="center">
  <img src="credito_capa.png" alt="Análise de Crédito Bancário" width="700"/>
</p>

# Análise de Crédito Bancário com Classificação de Risco por Inadimplência

### Equipe: Mariah Lisboa
### JuLho/2025

## Contexto

Com a queda nas taxas de juros no mercado financeiro, houve um aumento expressivo na demanda por crédito. Muitos clientes
passaram a ver esse cenário como uma oportunidade para financiar grandes compras ou consolidar dívidas, o que elevou
significativamente o número de solicitações de empréstimo no banco “Super Caja”.

A equipe de análise de crédito passou a lidar com uma alta demanda de pedidos, todos avaliados manualmente. Esse processo,
além de moroso, tornou-se ineficiente diante do novo volume de solicitações.

Diante desse cenário, o objetivo é apoiar o banco na automação do processo de análise de crédito, utilizando técnicas avançadas
de análise de dados para aumentar a eficiência, precisão e agilidade na concessão de empréstimos.

## Objetivos

- Automatizar e tornar mais eficiente o processo de análise e concessão de crédito;
- Aperfeiçoar e integrar a métrica de identificação de clientes inadimplentes;
- Identificar perfis de risco por meio de um score de inadimplência.
<br>

<details>
  <summary><strong>⚙️ Ferramentas e Tecnologias: </strong></summary>
  <br>
  
- **BigQuery (utilizando SQL)**
- **Google Colab (utilizando Python)**
- **Looker Studio (elaboração do EDA e dashboard final)**
- **Notion (gerenciamento de tempo e progresso)**
- **Google Documentos (montagem da ficha técnica)**
  <br>

</details>

<details>
  <summary><strong>📂 Processamentos e Tratamento dos Dados: </strong></summary>
  <br>
  
Nesta fase, os dados brutos foram limpos e tratados para padronizar formatos, remover inconsistências e lidar com valores
ausentes. Também foram realizadas transformações necessárias para viabilizar as análises posteriores, como a normalização de
variáveis numéricas e a codificação de variáveis categóricas.
<br>
  
  - **1. Imporatação dos dados** 
  - **2. Limpeza e tratamento dos dados** 
  - **3. Criação de novas variáveis**
  - **4. Unir tabelas** 

</details>

<details>
  <summary><strong>🔍 Exploração e Análise dos Dados: </strong></summary>
  <br>
  
Foram geradas estatísticas descritivas e visualizações para compreender o perfil geral dos clientes, identificando
tendências e comportamentos que poderiam influenciar o risco de crédito. Essa etapa também ajudou a levantar hipóteses
iniciais para as análises mais detalhadas.

<br>
  
  - **1. Análise Exploratória** 
  - **2. Processo inicial do cálculo de risco relativo** 
  - **3. Investigando relações e sinais iniciais de risco**

</details>

<details>
  <summary><strong>🧭 Técnicas Aplicadas</strong></summary>
  <br>
  
Foram empregadas técnicas estatísticas e de modelagem, com foco no cálculo do **Risco Relativo**, permitindo comparar a
probabilidade de inadimplência entre diferentes grupos. A aplicação dessas técnicas possibilitou quantificar o impacto de
variáveis específicas sobre o risco de crédito.
<br>
  
- **1. Cálculo de risco relativo**
- **2. Aplicar segmentação por score de risco**
  
</details>

<details>
  <summary><strong>⚠️ Análise de Risco Agravante + Reavaliação das Variáveis: </strong></summary>
  <br>
  
Nesta etapa, as variáveis inicialmente consideradas foram reavaliadas com base nos resultados preliminares. Identificaram-se
fatores agravantes que aumentavam significativamente o risco de inadimplência, possibilitando um refinamento das variáveis
mais relevantes para o modelo.
<br>

- **Criação do grupo de risco agravante (Q5)**
- **Ponto de corte com o grupo de risco agravado (Q5)**
- **Reavaliação das variáveis: força preditiva e otimização do score**
- **Fechamento das análises**
    
</details>

<details>
  <summary><strong>🏁 Resultados e Conclusões</strong></summary>
<br>
  
A análise mostrou que determinadas características dos clientes — como histórico de atraso e relação entre renda e valor
do crédito — têm impacto significativo no risco relativo. As conclusões oferecem suporte a estratégias de mitigação de
risco e aprimoramento das políticas de concessão de crédito.
<br>

- **Principais descobertas e insights**
- **Recomendações de aplicação do modelo**
- **Direcionamentos finais**

</details>

## 🔗 Links Úteis:
<br>

  - 📘 [Relatório Documentado (Notion)](https://www.notion.so/Projeto-3-Risco-Relativo-An-lise-de-Inadimpl-ncia-Banco-Super-CAJA-2327ef1bfdb7801caccefcef3e5ce0d2?source=copy_link)
  - 📊 [Dashboard de análise de risco (Looker Studio)](https://lookerstudio.google.com/reporting/c7b30c46-1079-4e1e-81f1-aa0a853ef78c)
  - 🎞️ [Vídeo-Apresentação (Loom)](https://www.loom.com/share/c4006626d2434be5813790263032164b?sid=79857de8-08b1-4e95-8f3b-10e6059138ce)
  - 🗂️ [Link para o notebook (Google Colab)](https://colab.research.google.com/drive/1xbJOS6PkGWwDDtFKd59mnrByAr9Jd7Gk?usp=sharing)

  
