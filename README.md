# GeoSaudeBrasil

[![Licença](https://img.shields.io/badge/licence-MIT-blue.svg)](LICENSE)

**GeoSaudeBrasil** é um banco de dados geoespacial abrangente que integra informações cruciais para a análise da infraestrutura de saúde no Brasil. Ele combina dados de leitos hospitalares do DATASUS com projeções populacionais do IBGE, permitindo análises temporais (2007-2024) e regionais em diversas escalas geográficas.

## Conteúdo do Repositório

* **Banco de Dados PostgreSQL/PostGIS:**
    * Estrutura relacional otimizada para consultas espaciais e temporais eficientes.
    * Tabelas com dados de estabelecimentos de saúde, leitos hospitalares e projeções populacionais.
    * Metadados detalhados para cada tabela e atributo.
* **Dados Georreferenciados:**
    * Localização geográfica dos estabelecimentos de saúde, obtida através da API do Google Geocoding.
    * Shapefiles das unidades geográficas do IBGE.

## Objetivos

* Fornecer uma base de dados confiável e atualizada para estudos sobre a infraestrutura hospitalar no Brasil.
* Permitir a identificação de disparidades regionais na oferta de leitos hospitalares.
* Auxiliar na formulação de políticas públicas mais eficazes para a área da saúde.
* Promover a pesquisa e o desenvolvimento de soluções inovadoras para a gestão da saúde pública.

## Público-Alvo

* Pesquisadores da área de geoinformação e saúde pública.
* Gestores públicos e analistas de saúde.
* Profissionais interessados em desenvolver estratégias baseadas em dados para a melhoria da acessibilidade e infraestrutura hospitalar no Brasil.

## Como Começar

1.  **Pré-requisitos:**
    * PostgreSQL com extensão PostGIS instalada.
    * Python 3.x com as bibliotecas GeoPandas, Pandas e Matplotlib.
    * QGIS (opcional, para visualização de mapas).
2.  **Instalação do Banco de Dados:**
    * Clone este repositório.
    * Restaure o banco de dados PostgreSQL a partir do arquivo `GeoSaudeBrasil.backup`.
3.  **Visualização no QGIS:**
    * Abra os projetos QGIS no diretório `qgis`.


## Contribua

* Este repositório é um projeto de código aberto e convida a colaborações.
* Contribua com sugestões, correções ou novos recursos.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

## Contato

* [Jefferson Vinícios/ Mestrando em Ciências da Computação na UFSJ]
* [jeffersonvinicius@aluno.ufsj.edu.br]
