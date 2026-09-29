# BMW Used Cars — Data Cleaning & Data Quality

## Sobre o projeto

Este projeto tem como objetivo realizar o tratamento, a validação e a documentação de uma base de dados de veículos BMW usados, transformando os dados originais em uma base estruturada e preparada para futuras análises.

O projeto representa a primeira etapa de um fluxo de análise de dados, com foco em **Data Cleaning, Data Quality e documentação dos dados**.

## Objetivos

- Identificar e tratar inconsistências na base original;
- Tratar valores ausentes;
- Padronizar e estruturar os dados;
- Criar novas variáveis relevantes para análise;
- Definir regras de validação e qualidade dos dados;
- Criar documentação das variáveis do dataset;
- Preparar a base para análises e visualizações futuras.

## Ferramentas utilizadas

- Microsoft Excel
- Power Query

## Processo

### 1. Dados originais

A base original foi preservada separadamente para manter os dados de origem disponíveis para consulta e comparação.

### 2. Data Cleaning

Foi criada uma versão tratada da base, incluindo:

- tratamento de valores ausentes;
- verificação dos tipos de dados;
- padronização dos dados;
- criação de variáveis derivadas;
- preparação da estrutura para análise.

### 3. Variáveis derivadas

Novas variáveis foram criadas para ampliar as possibilidades de análise da base, incluindo indicadores relacionados a:

- eficiência de combustível;
- idade do veículo;
- segmento de preço;
- conversões de unidades;
- classificação de eficiência.

### 4. Validação dos dados

Foi criada uma camada de validação contendo, para cada variável:

- tipo de dado esperado;
- regra de validação;
- valores ou intervalos permitidos;
- ação em caso de erro;
- status da validação;
- observações relevantes.

Essa etapa permite verificar a consistência da base e facilita futuras atualizações dos dados.

### 5. Documentação

Foi desenvolvido um dicionário de dados contendo:

- nome da variável;
- descrição;
- tipo de dado;
- unidade;
- exemplo;
- origem;
- observações.

O objetivo é tornar o dataset compreensível e reutilizável sem depender do conhecimento de quem realizou o tratamento.

## Estrutura do projeto

```text
data/
├── raw/
│   └── bmw_data_original.xlsx
│
└── processed/
    └── bmw_data_clean.xlsx
        ├── Data Clean
        ├── Validações
        └── Documentação
```

## Próximas etapas

A base tratada será utilizada na próxima etapa do projeto para desenvolvimento de uma análise exploratória e visualização dos dados utilizando **Power BI**.

Essa etapa buscará transformar os dados preparados em indicadores, visualizações e insights relacionados ao mercado de veículos BMW usados.

## Autor

**Heraldo C. Alves**

Estudante de Ciências Atuariais — UERJ  
Interesses: Dados, Risco e Análise Quantitativa
