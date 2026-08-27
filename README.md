# Evolução da Rede Metroferroviária de São Paulo

## Sobre o projeto

Projeto acadêmico desenvolvido em equipe na Universidade Federal do ABC (UFABC), utilizando conceitos da Teoria dos Grafos para analisar a evolução estrutural da rede metroferroviária da Região Metropolitana de São Paulo em diferentes períodos históricos.
As estações foram modeladas como vértices e as conexões ferroviárias como arestas, permitindo analisar características como conectividade, densidade, grau, diâmetro, distância média dos caminhos mínimos e ciclos.

## Objetivo

Analisar como a expansão da rede metroferroviária da Região Metropolitana de São Paulo influenciou sua conectividade, integração e organização estrutural ao longo do tempo, utilizando métricas da Teoria dos Grafos para comparar diferentes períodos históricos.

## Modelagem da rede

A rede foi representada como um grafo simples, não direcionado e não ponderado.

- **Vértices:** representam as estações da rede metroferroviária.
- **Arestas:** representam as conexões ferroviárias entre estações consecutivas.
- **Estações de integração:** são representadas por um único vértice conectado às diferentes linhas.
- **Grafo não direcionado:** as conexões podem ser percorridas nos dois sentidos.
- **Grafo não ponderado:** não foram considerados atributos como distância física, tempo de viagem ou fluxo de passageiros.

## Períodos analisados

Os períodos foram selecionados a partir de marcos históricos que provocaram mudanças relevantes na configuração da rede.

| Período | Marco histórico |
|---|---|
| **1974** | Início das operações comerciais do Metrô |
| **1979** | Primeira integração entre linhas |
| **1994–1996** | Incorporação das linhas da CBTU e FEPASA à CPTM |
| **2010** | Expansão da rede e início das concessões |
| **2019** | Consolidação da rede integrada |
| **2026** | Configuração mais recente da rede analisada |

O projeto completo contempla seis períodos históricos. Neste repositório estão disponíveis os notebooks e arquivos de grafos referentes aos períodos de **1974, 1979 e 1994–1996**, trabalhados pela autora deste repositório.

## Métricas analisadas

Foram utilizadas diferentes propriedades estruturais para comparar a evolução da rede:

- Número de vértices;
- Número de arestas;
- Número de componentes conectados;
- Densidade;
- Grau dos vértices;
- Diâmetro;
- Distância média dos caminhos mínimos;
- Ciclos.

A análise dessas métricas permitiu observar o crescimento da rede e as mudanças em sua conectividade e estrutura ao longo dos períodos históricos.

## Tecnologias utilizadas

- **Python**
- **NetworkX**
- **Gephi**

O Python e a biblioteca NetworkX foram utilizados na construção e modelagem dos grafos. Os grafos também foram exportados para o Gephi para visualização e análise.

## Minha contribuição

Este projeto foi desenvolvido em equipe. Minha participação envolveu a elaboração do projeto e a modelagem da rede em grafos, incluindo a construção dos grafos referentes aos períodos de **1974, 1979 e 1994–1996** e sua exportação para o Gephi.
Também participei parcialmente da validação dos dados utilizados e da escrita e formatação do artigo.

## Estrutura do repositório

```text
analise-grafos-metro-sp/
│
├── gephi/
│   ├── grafo_1974.gexf
│   ├── grafo_1979.gexf
│   └── grafo_1996.gexf
│
├── grafos_metroferroviarios_1974_1979_1994_1996.ipynb
│
└── README.md
