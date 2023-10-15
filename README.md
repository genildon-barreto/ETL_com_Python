# ETL_com_Python
Repositório do desafio de Extract Transform &amp; Load da trilha Santander Ciência de Dados com Python

## Contexto

Este projeto visa a criação de um serviço que realiza a conversão de dados de arquivos Excel para PDF, incorporando mensagens personalizadas. O principal objetivo é identificar os clientes que estão prestes a fazer aniversário e gerar mensagens de felicitações personalizadas para eles.

## Descrição do Serviço

O serviço consiste em:

- Realizar a conversão dos dados contidos em arquivos Excel para um único arquivo PDF.
- Identificar os clientes que aniversariam durante a semana com base na data de aniversário contida na coluna D do Excel.
- Incrementar uma mensagem promocional para cada cliente aniversariante. A mensagem incluirá o nome do cliente, que está na coluna A do Excel, seguindo o formato a seguir:

```
"Olá {nome}, tudo bem? Essa semana você está aniversariando
e para comemorar estamos com uma promoção! A partir de R$30
em compras com pagamento por PIX, ganhe 10% de cashback na
sua conta!"
```

- Inserir as mensagens personalizadas no PDF com um espaçamento de duas linhas entre elas.

## Requisitos

Para executar este projeto, você precisará do seguinte:

- Um arquivo Excel contendo os dados dos clientes, com as colunas A contendo o nome completo e a coluna D contendo a data de aniversário.

## Como Usar

1. Clone este repositório.
2. Certifique-se de que você tem um arquivo Excel válido com os dados dos clientes.
3. Execute o serviço de conversão para gerar o PDF personalizado.

## Entregáveis Esperados

Após a execução do serviço, você obterá um único arquivo PDF contendo todas as mensagens personalizadas conforme os critérios mencionados.

## Observações Adicionais

Este projeto é uma ótima maneira de automatizar a felicitação de clientes em seus aniversários e pode ser útil para campanhas promocionais e interações personalizadas com os clientes. Sinta-se à vontade para contribuir e melhorar este serviço.
