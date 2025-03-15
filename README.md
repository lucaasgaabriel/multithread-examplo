# Multithread com paralelismo - Exemplo

### Exemplo de gerenciamento multithread com processamentos múltiplos de itens

O que este código faz:

* Cada thread executa a função ```processar_itens``` para um item específico.
* A função ```executar_itens_simultaneamente``` cria múltiplas threads para processar diversos itens ao mesmo tempo.
* O incremento de índice de itens é sempre de +60, mas pode ser alterado conforme a necessidade.
* A quantidade de ```max_workers``` como parâmetro dentro de ```with ThreadPoolExecutor()``` pode ser ajustada conforme a necessidade de paralelismo desejado, e com isso irá substituir o processamento simulado pelo seu próprio código de processamento real.
