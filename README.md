# Global-Solution - Carbon360

## Sobre o Projeto

O Carbon360 é uma plataforma de dados voltada para monitoramento ambiental, sustentabilidade e gestão de créditos de carbono. O projeto foi desenvolvido como parte da Global Solution FIAP e tem como objetivo centralizar, processar e disponibilizar dados ambientais provenientes de diversas fontes públicas e privadas, apoiando análises relacionadas à biodiversidade, emissões de carbono, queimadas, uso do solo e projetos de compensação ambiental.

A solução utiliza uma arquitetura moderna de dados baseada em Data Lakehouse, permitindo ingestão, transformação, armazenamento e consumo de grandes volumes de informações ambientais de forma escalável.

## Objetivos

* Consolidar dados ambientais em uma única plataforma.
* Monitorar indicadores de sustentabilidade e biodiversidade.
* Integrar informações de créditos de carbono e projetos ambientais.
* Apoiar análises para tomada de decisão baseada em dados.
* Disponibilizar informações confiáveis para acompanhamento de métricas ESG.

<img width="1536" height="1024" alt="Carbon360 - Arquitetura de dados" src="https://github.com/user-attachments/assets/b9b57424-0383-409c-830d-5593a79ec203" />

## Fontes de Dados

O projeto integra dados provenientes de diferentes organizações e plataformas, incluindo:

* IBGE
* Verra Registry
* GBIF (Global Biodiversity Information Facility)
* Landsat (NASA/USGS)
* MapBiomas
* OpenWeather
* Outras fontes públicas relacionadas a meio ambiente e sustentabilidade

## Arquitetura

O Carbon360 segue a arquitetura Medallion:

### Bronze Layer

Dados brutos ingeridos diretamente das fontes de origem.

### Silver Layer

Dados tratados, padronizados e enriquecidos.

### Gold Layer

Dados consolidados e preparados para consumo analítico e dashboards.

## Tecnologias Utilizadas

* Python
* Apache Spark
* Databricks
* Delta Lake
* SQL
* GitHub
* APIs REST
* Data Lakehouse Architecture

## Estrutura do Repositório

```text
carbon360/
│
├── docs/
│   ├── arquitetura/
│   ├── diagramas/
│   └── documentação_funcional/
│
├── src/
│   ├── ingestion/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── utils/
│
├── notebooks/
│
├── datasets/
│
├── tests/
│
└── README.md
```

---

## Principais Indicadores

* Emissões de carbono
* Créditos de carbono gerados
* Projetos ambientais registrados
* Cobertura vegetal
* Ocorrências de biodiversidade
* Dados climáticos
* Monitoramento de queimadas

## Equipe
- Alex Junior
- Felipe Alves
- Isabella Heder

Projeto desenvolvido para a Global Solution FIAP com foco em inovação, sustentabilidade e tecnologia aplicada à gestão ambiental.
