# Mini Projeto — Análise de Vendas de Halloween

Mini projeto desenvolvido no curso de Inteligência Artificial do SENAI, com o objetivo de praticar análise e tratamento de dados utilizando Python e Pandas.

## Objetivo

Analisar uma base fictícia de vendas de produtos relacionados ao Halloween, identificando inconsistências nos dados e padrões que possam apoiar decisões de negócio.

## Base de dados

O arquivo `halloween_vendas.csv` possui 1.500 registros contendo informações como:

- data da venda;
- produto e categoria;
- canal de venda;
- quantidade;
- preço e custo unitário;
- desconto;
- status do pedido;
- data de entrega.

## Etapas realizadas

O projeto foi organizado em cinco sprints:

### Sprint 1 — Leitura e exploração dos dados

- Importação da base CSV;
- verificação das colunas;
- identificação de valores ausentes;
- análise inicial das categorias e canais de venda.

### Sprint 2 — Limpeza e padronização

- Padronização da coluna `categoria`;
- utilização de função e expressão regular;
- padronização dos canais de venda;
- identificação de registros inconsistentes.

### Sprint 3 — Validação dos dados numéricos

- Conversão de quantidade e preço;
- identificação de valores inválidos;
- identificação dos pedidos afetados por problemas numéricos.

### Sprint 4 — Regras de negócio e datas

- Teste de hipótese sobre pedidos sem data de entrega;
- conversão das datas de venda;
- identificação de datas inválidas;
- criação das colunas de ano, mês, dia, hora e período.

### Sprint 5 — Análises de negócio

- Quantidade de pedidos por período;
- comparação entre 2024 e 2025;
- pedidos por canal;
- faturamento por período e canal;
- ticket médio;
- margem bruta;
- margem percentual;
- comparação dos principais indicadores.

## Principais resultados

A análise identificou que:

- Outubro de 2025 foi o período de maior faturamento, com R$ 63.464,38;
- a Web apresentou forte participação em quantidade de pedidos e faturamento, principalmente em setembro e outubro;
- a Loja física apresentou maior força em novembro;
- o canal Mercado apresentou o maior ticket médio em todos os períodos analisados;
- o Mercado também apresentou a maior margem percentual média, com aproximadamente 53,52%;
- o faturamento de outubro de 2025 cresceu 10,93% em relação a outubro de 2024;
- novembro de 2025 apresentou crescimento de 10,12% em relação ao mesmo mês de 2024.

## Tecnologias utilizadas

- Python
- Pandas
- Jupyter Notebook
- Git
- GitHub

## Arquivos principais

- `halloween_vendas.csv` — base de dados utilizada;
- `projeto_dia_das_bruxas_final.ipynb` — notebook final com todo o desenvolvimento;
- `report.md` — relatório com os principais resultados e conclusões.

## Autor

Guilherme Scherer
