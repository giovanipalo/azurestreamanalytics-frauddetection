# Análise de Streaming de Dados com Azure Stream Analytics e Power BI

Este projeto demonstra como realizar análise de streaming de dados utilizando o Azure Stream Analytics em conjunto com o Power BI. Utilizaremos um aplicativo cliente fornecido pela Microsoft Azure para gerar dados em tempo real de chamadas telefônicas, incluindo chamadas fraudulentas. Esses dados serão processados pelo Azure Stream Analytics para detecção de fraudes e, em seguida, automaticamente enviados para o Power BI, onde os resultados podem ser visualizados em um dashboard. O objetivo principal é detectar e analisar chamadas fraudulentas em um fluxo contínuo de dados gerados por um aplicativo cliente.

## Pré-requisitos
Antes de começar, é necessário ter:

- Uma [assinatura do Azure](https://azure.microsoft.com/pt-br/free/).
- O [aplicativo gerador de eventos](https://aka.ms/asatelcodatagen).
- Uma [conta do Power BI](https://powerbi.microsoft.com/pt-br/).

## Passos

1. **Entrar no Azure:**
   Acesse o [portal do Azure](https://portal.azure.com/) e faça login.

2. **Criar um Hub de Eventos:**
   - Crie um namespace para os Hubs de Eventos.
   - Crie um hub de eventos dentro desse namespace.
   - Obtenha a cadeia de conexão para o hub de eventos.

3. **Iniciar o Aplicativo Gerador de Eventos:**
   - Configure o aplicativo para enviar dados para o hub de eventos.
   - Execute o aplicativo gerador de eventos para começar a enviar dados simulados.

4. **Criar um Trabalho de Stream Analytics:**
   - Crie um novo trabalho de Stream Analytics no portal do Azure.
   - Configure a entrada para ler os dados do hub de eventos.
   - Configure a saída para enviar os dados transformados para o Power BI.

5. **Configurar Consultas para Transformar Dados em Tempo Real:**
   - Teste consultas para visualizar e transformar os dados.
   - Exemplo de consultas: projeção de colunas, contagem de chamadas por região, detecção de fraudes SIM.

6. **Iniciar o Trabalho e Visualizar a Saída:**
   - Inicie o trabalho de Stream Analytics.
   - Visualize os resultados no Power BI criando um dashboard com os dados transformados.

## Recursos Adicionais
- [Referência de linguagem de consulta do Stream Analytics do Azure](https://docs.microsoft.com/pt-br/azure/stream-analytics/stream-analytics-query-language-reference)
- [Documentação do Power BI](https://docs.microsoft.com/pt-br/power-bi/)
