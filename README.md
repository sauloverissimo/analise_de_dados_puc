# MVP - Análise de Dados PUC - Tier List de Pilotos de Fórmula 1

Este projeto tem como objetivo aplicar os conhecimentos de análise de dados e visualização para comparar, de forma justa e estruturada, o desempenho histórico de pilotos de Fórmula 1 com base em dados públicos. 
Ao final, apresentamos um ranking em formato de **Tier List** e um **gráfico de pódio** dos três melhores colocados.

## Objetivos
- Construir uma métrica objetiva que permita comparar pilotos de diferentes épocas
- Validar as hipóteses com base estatística
- Criar visualizações claras e de simples entendimento

## Hipóteses
1. É possível criar um score composto para medir desempenho global de um piloto ao longo da história da formula 1.
2. A visualização via **Tier List** permite uma interpretação mais clara dos resultados

## Base de Dados
Os dados foram obtidos da competição pública no Kaggle: 
[Formula 1 World Championship Data](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)

## Etapas do projeto
### Problema
- Descrição
- Hipoteses
- Tipo
### Coleta e Análise de Dados
#### Pré-Processamento de Dados:
- Exploração e limpeza dos dados
#### Modelagem
- Preparação de Tabelas
#### Pós-processamento
- Criação de KPIs relevantes (pontos por corrida, % de vitórias, etc.)
- Filtro de pilotos relevantes com mínimo de provas
- Cálculo do **score final** composto
- Criação da **Tier List** com faixas: S, AA+, A, B, C...
#### Visualização de Dados
- Visualização de resultados:
  - Tier List estilo "ranking visual"
  - Gráfico de Pódio com imagens dos 3 primeiros

## Principais Resultados
- **Lewis Hamilton** obteve o maior score da análise, sendo classificado #1 na S Tier
- **Max Verstappen** ficou na 2ª posição, seguido por **Juan Manuel Fangio**

## Visualizações
- ![Tier List] (https://github.com/sauloverissimo/analise_de_dados_puc/blob/main/img/TierList.png)
- ![Pódio](https://github.com/sauloverissimo/analise_de_dados_puc/blob/main/img/Podio.png)

## Execução
O notebook principal está disponível em:
```
https://raw.githubusercontent.com/sauloverissimo/analise_de_dados_puc/refs/heads/main/MVP_analise_de_dados_puc.ipynb
```
Recomenda-se abrir no Google Colab para execução.

## Requisitos
- Python 3.x
- Bibliotecas: `pandas`, `matplotlib`, `seaborn`, `Pillow`, `requests`

## Conclusão
A análise validou as hipóteses propostas, entregando um modelo claro, visual e estatisticamente coerente para comparar grandes nomes da F1. A Tier List final e o pódio são uma representação eficaz do desempenho histórico dos pilotos com base em dados reais.
