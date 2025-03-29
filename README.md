# ETL do Banco Central do Brasil

Dicionário de dados

|Nome	|Tipo	|Título	|Descrição |
| --- | --- | --- | --- |
|trimestre	|texto	|Trimestre	|Corresponde ao ano e trimestre das informações|
|nomeBandeira	|texto	|Bandeira do cartão	|Corresponde ao nome da bandeira do cartão|
|nomeFuncao	|texto	|Função do cartão	|Corresponde ao nome da função do cartão (crédito, débito e pré-pago)|
|produto	|texto	|Produto do cartão	|Categoria atribuída a um cartão de pagamento.|
|qtdCartoesEmitidos	|inteiro	|Quantidade de cartões emitidos	|Corresponde ao estoque de cartões emitidos, apurado no trimestre, ou seja, os cartões que foram emitidos em todos os períodos anteriores até o final do trimestre de referência. Os cartões cancelados não integram esta estatística.|
|qtdCartoesAtivos	|inteiro	|Quantidade de cartões ativos	|Corresponde ao estoque de cartões ativos, apurado no final do trimestre. São considerados como ativos os cartões que foram utilizados pelo menos uma vez no período que abrange os doze meses anteriores ao último dia do trimestre de referência.|
|qtdTransacoesNacionais	|inteiro	|Quantidade de transações nacionais com cartão	|Corresponde à quantidade de transações com cartão realizadas no país|
|valorTransacoesNacionais	|decimal	|Valor de transações nacionais com cartão	|Corresponde ao valor em reais de transações com cartão realizadas no país.|
|qtdTransacoesInternacionais	|inteiro	|Quantidade de transações internacionais com cartão	|Corresponde à quantidade de transações com cartão realizadas fora do país.|
|valorTransacoesInternacionais	|decimal	|Valor de transações internacionais com cartão	|Corresponde ao valor em reais de transações com cartão realizadas fora do país.|
