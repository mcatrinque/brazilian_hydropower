# Análise Geoespacial no Setor Hidrelétrico Brasileiro

## Introdução

Este projeto realiza uma análise geoespacial no setor hidrelétrico brasileiro, visando fornecer insights para a tomada de decisão na construção de usinas hidrelétricas em locais estratégicos. Utilizando dados sobre precipitação, densidade demográfica por bacia hidrográfica e capacidade de geração de energia por estado, o projeto oferece uma visão abrangente do cenário energético no Brasil.

## Conjunto de Dados Utilizados

1. **Estados Brasileiros**
   - Origem: IBGE
   - Descrição: Limites territoriais e informações sobre estados brasileiros.

2. **Precipitação Anual**
   - Origem: Sistema Nacional de Informações sobre Recursos Hídricos (SNIRH)
   - Descrição: Dados de precipitação média anual no Brasil (1977-2006).

3. **Densidade Demográfica por Bacia Hidrográfica (2010)**
   - Origem: Instituto Brasileiro de Geografia e Estatística (IBGE)
   - Descrição: Dados de densidade demográfica por bacia hidrográfica no Censo de 2010.

4. **Potencial de Geração de Energia por Usina Hidrelétrica**
   - Origem: IBGE
   - Descrição: Capacidade de geração de energia por usina hidrelétrica, agrupada por estado.

## Visualizações

### 1. Precipitação no Território Brasileiro
   - Visualização do volume de chuvas por estado.
   - [Link para Visualização](path/to/8_br_mean_rainfall.png)

### 2. Densidade Demográfica por Bacia Hidrográfica
   - Mapa da densidade demográfica em diferentes bacias hidrográficas.
   - [Link para Visualização](path/to/dens_dem_bacia.png)

### 3. Produção Energética por Estados
   - Mapa da capacidade de geração de energia por estado.
   - Destaque para a localização e potência das usinas hidrelétricas.
   - [Link para Visualização](path/to/2_br_hidropower_cap.png)

## Requisitos de Ambiente

- Python 3.x
- Bibliotecas: geopandas, numpy, pandas, matplotlib

## Como Executar

1. Clone este repositório.
2. Abra o notebook no ambiente Colab ou execute localmente em um ambiente Python.
3. Certifique-se de instalar as bibliotecas necessárias (`geopandas`, `numpy`, `pandas`, `matplotlib`) se estiver executando localmente.
4. Execute cada seção do código conforme necessário.

Este projeto fornece uma visão abrangente do setor hidrelétrico brasileiro, utilizando análises espaciais para apoiar decisões estratégicas na construção de usinas hidrelétricas.
