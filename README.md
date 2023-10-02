# Projeto de Gerenciamento de Produtos - SQL

Este repositório contém um projeto de gerenciamento de produtos usando SQL. O projeto inclui uma série de operações SQL para criar uma tabela de produtos, inserir dados nessa tabela e realizar consultas para obter informações relevantes sobre os produtos.

## Estrutura do Banco de Dados

O banco de dados consiste em uma única tabela chamada "TABELA_PRODUTOS". Cada registro nessa tabela representa um produto e inclui informações como nome, preço, estoque, perecibilidade, marca e nacionalidade.

### Esquema da Tabela

- `id_produto`: Chave primária para identificação única do produto.
- `nome`: Nome do produto (até 50 caracteres).
- `preco`: Preço do produto com até 10 dígitos, 2 casas decimais.
- `estoque`: Quantidade em estoque do produto (número inteiro).
- `perecivel`: Indicação se o produto é perecível (até 3 caracteres).
- `marca`: Marca do produto (até 50 caracteres).
- `nacionalidade`: Nacionalidade do produto (até 50 caracteres).

## Operações SQL

As operações SQL realizadas no projeto incluem:

- Criação da tabela "TABELA_PRODUTOS".
- Inserção de dados na tabela "TABELA_PRODUTOS".
- Seleção de todos os registros na tabela "TABELA_PRODUTOS".
- Contagem de registros na tabela "TABELA_PRODUTOS".
- Cálculo da média de preços dos produtos.
- Cálculo da média de preços dos produtos agrupados por "perecivel".
- Cálculo da média de preços dos produtos agrupados por "nome".
- Cálculo da média de preços e soma do estoque de todos os produtos.
- Seleção de produtos com o preço máximo.
- Seleção de produtos com preço superior à média de preços de todos os produtos.
- Contagem de produtos por nacionalidade.

