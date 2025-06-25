#  Análise de Evasão de Clientes – Telecom X

## Descrição do Projeto

Este projeto tem como objetivo analisar o comportamento dos clientes da empresa fictícia **Telecom X**, com foco em compreender os principais fatores que levam à evasão (churn).

Através da aplicação de técnicas de ETL (Extração, Transformação e Análise de Dados), foi desenvolvida uma análise exploratória utilizando Python e bibliotecas como `pandas`, `matplotlib` e `seaborn`.

## Tecnologias Utilizadas

- Python 3.x  
- Google Colab  
- pandas  
- seaborn  
- matplotlib

##  Etapas do Projeto

1. **Extração de Dados:**  
   Os dados foram extraídos diretamente de um arquivo `.json` hospedado no GitHub.

2. **Transformação dos Dados:**  
   - Tratamento de valores ausentes  
   - Tradução das variáveis para português  
   - Expansão de colunas aninhadas (dicionários)

3. **Análise Exploratória:**  
   - Criação de gráficos de barras e distribuição  
   - Identificação de padrões como:  
     - Tipo de contrato  
     - Forma de pagamento  
     - Tempo como cliente  
     - Gastos mensais

## Principais Resultados

- Contratos mensais apresentam maior índice de evasão.
- Clientes com pouco tempo de vínculo tendem a cancelar com mais frequência.
- Pagamentos por boleto bancário ou cartões pré-pagos estão mais associados ao churn.

## Conclusões e Recomendações

- Incentivar contratos de longo prazo com benefícios.
- Estimular o uso de débito automático.
- Acompanhar de perto os primeiros meses do cliente.

## Autora

Vanessa Borges de Souza  
Desenvolvido como parte do desafio **Telecom X – Análise de Dados**
