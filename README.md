# Projeto: Modelo de Banco de Dados para Sistema de Vendas

## Descrição do Desafio

Este projeto tem como objetivo desenvolver um esquema conceitual para um sistema de vendas. O esquema deverá ser adicionado a um repositório no GitHub para avaliação e integração em seu portfólio.

O modelo apresentado foi refinado para incluir os seguintes elementos:
- **Cliente PJ e PF**: Uma conta pode ser registrada como Pessoa Jurídica (PJ) ou Pessoa Física (PF), mas nunca ambas.
- **Pagamento**: Possibilidade de cadastrar mais de uma forma de pagamento para maior flexibilidade.
- **Entrega**: Controle de entregas com status atual e código de rastreamento para acompanhamento do cliente.

## Objetivo

O objetivo deste projeto é desenvolver um modelo conceitual que atenda às necessidades de um sistema de vendas robusto e funcional, incluindo:
1. Implementar o refinamento do modelo sugerido.
2. Subir o esquema para um repositório próprio no GitHub.
3. Criar um README detalhado para contextualizar e documentar o esquema conceitual.

Este desafio não apenas aprimora as habilidades técnicas de modelagem de banco de dados, mas também fortalece seu portfólio com um projeto real e aplicado.

## Contexto do Projeto

O esquema foi projetado para gerenciar os seguintes aspectos principais:
- **Clientes**:
  - Cadastro separado entre Pessoa Física (CPF e dados pessoais) e Pessoa Jurídica (CNPJ e informações empresariais).
  - Garantir que uma conta contenha informações de apenas um tipo.
- **Pagamentos**:
  - Cada cliente pode registrar múltiplas formas de pagamento (ex.: cartão de crédito, boleto, PIX, etc.).
- **Entregas**:
  - Controle rigoroso do status do pedido (ex.: pendente, enviado, entregue).
  - Inclusão de um código de rastreamento para consulta.

## Tecnologias Utilizadas

- **draw.io**: Para modelagem e criação do diagrama do banco de dados.
- MySQL Workbench ou DB Designer como alternativa para modelagem do banco de dados.
- Git e GitHub para versionamento de código e apresentação do projeto.
