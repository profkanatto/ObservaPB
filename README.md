# Plataforma Web para Aumento da Participação na Fiscalização Legislativa

Este projeto de mestrado tem como objetivo desenvolver uma plataforma web que integra conjuntos de dados abertos das câmaras legislativas municipais do estado da Paraíba. O projeto visa aumentar a transparência legislativa e promover a participação da sociedade na fiscalização do legislativo municipal.

## Índice

- [Introdução](#introdução)
- [Objetivo](#objetivo)
- [Fonte de Dados](#fonte-de-dados)
- [Modelagem de Dados](#modelagem-de-dados)
- [Visualizações](#visualizações)
- [Instruções de Uso](#instruções-de-uso)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Introdução

Transformação digital e Governança Pública tem estado presente nos debates e planejamentos de diversas instituições em todo mundo na última década, impulsionados pela Lei da Transparência, Lei de Acesso à Informação e a chegada do governo eletrônico. Este trabalho desenvolve a concepção de uma plataforma web que integra conjuntos de dados abertos das câmaras legislativas municipais do estado da Paraíba.

## Objetivo

O objetivo geral deste projeto é desenvolver uma prova de conceito de uma plataforma web que integre conjuntos de dados abertos das câmaras legislativas municipais do estado da Paraíba, contribuindo para o aumento da participação da sociedade na Governança Pública da transparência legislativa.

## Ferramentas Utilizadas no Projeto
Foi utilizado apenas o Power BI para o desenvolvimento do Dashboard e uma paleta de cores para tornar o dashboard acessível a pessoas que possuem daltonismo

## Fonte de Dados

- **Dados Governamentais Abertos:** Informações obtidas de portais de transparência dos municípios da Paraíba.
- **ETL (Extrair, Transformar e Carregar):** Processo utilizado para extrair, transformar e carregar os dados das câmaras legislativas municipais.

## Modelagem de Dados

A modelagem de dados foi realizada utilizando a ferramenta Microsoft Power BI, integrando diferentes conjuntos de dados sobre a transparência administrativa e operacional das câmaras legislativas municipais. (Imagem - Relacionamentos)

### Relacionamentos
- $Atividades_Legislativa_CG.Vereador(1) - (1)$webscraping_cg.Parlamenta_nome = um para um (1-1)
- $consulta_cand_2020_PB.nm_ue(1) - (1)$Mapeamento ITPL.municipio = um para um (1-1)
-  $consulta_cand_2020_PB.nm_ue(1) - (1)$Dados_Pessoais_CG.municipio = um para um (1-1)
-  $Atividades_Legislativa_CG.Vereador(*) - (1)$Lista-Candidatos-Vereador-CAMPINA GRANDE.Nome Urna = muitos para um (*-1)

#### Bases de Dados
- Webscraping.Atividades_Legislativa
- Consulta_cand_2020_PB_TRE
- Webscraping.Dados_Pessoais
- Mapeamento ITPL




## Visualizações

### Dashboard da Concepção de uma Plataforma

#### Página Inicial
- (Imagem da Tela 1 - Página Inicial)

#### Casa Legislativa
- (Imagem da Tela 2 - Casa Legislativa)

#### Meu Representante
- (Imagem da Tela 3 - Meu Representante)

#### ITPL Municipal
- (Imagem da Tela 4 - Índice de Transparência)
