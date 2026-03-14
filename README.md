# 📊 Pipeline de Dados das ações do Mercado Financeiro Brasileiro

Este projeto é um **pipeline completo de coleta, padronização e enriquecimento de dados do mercado acionário brasileiro**, utilizando fontes como **B3, CVM e Fundamentus**.

O objetivo é construir uma **base estruturada e consistente de dados históricos de empresas listadas na B3**, incluindo:

- Cotações históricas  
- Proventos  
- Informações cadastrais das empresas  
- Demonstrações financeiras (BP e DRE)  
- Indicadores financeiros anuais e trimestrais  

---

# 🧠 Visão Geral do Pipeline

O pipeline executa as seguintes etapas:

1. Coleta de cotações históricas da B3  
2. Obtenção de metadados das empresas  
3. Correção de tickers com nomenclatura antiga  
4. Coleta de cotações ajustadas  
5. Coleta de proventos  
6. Extração de dados financeiros da CVM (BP e DRE) 
7. Cálculo de indicadores financeiros (anuais e trimestrais)  

O resultado final é um **dataset consolidado contendo histórico completo das empresas listadas**.

---

# 📥 Fontes de Dados

O projeto utiliza múltiplas fontes para aumentar a confiabilidade e cobertura dos dados.

| Fonte | Tipo de Dados |
|-----|-----|
| B3 | Cotações históricas, metadados das empresas |
| Fundamentus | Cotações ajustadas e proventos históricos |
| CVM | Demonstrações financeiras (BP e DRE) |

A estratégia é sempre **priorizar a fonte mais oficial disponível** e usar outras apenas para **complementação de lacunas**.

---

# ⚠️ Observações

- Algumas fontes podem apresentar **lacunas ou inconsistências históricas**.
- Os dados foram coletados para **uso em projetos didáticos e experimentais**.
- Devido a algumas **divergências entre as fontes**, foram aplicadas correções e ajustes durante o processo de tratamento dos dados.
- Mesmo após essas correções, **ainda podem existir algumas inconsistências**. No entanto, para os objetivos deste projeto, os dados coletados **já são suficientes para a realização de estudos experimentais**.
- Os arquivos de dados extraídos não foram incluídos neste repositório, devido ao seu grande tamanho.
