# Exercício EBAC - Teste de API com Postman

## Objetivo
Realizar testes na API Hub de Leitura, validando a funcionalidade Catálogo de Livros.

## Ferramentas utilizadas
- Postman
- Node.js
- GitHub

## Cenários testados

### Positivos
- Login com credenciais válidas
- Listagem de livros
- Listagem por autor
- Listagem por categoria
- Consulta de categorias
- Consulta de autores
- Busca de livro por ID
- Criação de livro
- Atualização de livro
- Exclusão de livro

### Negativos
- Login inválido
- Criação sem token
- Criação com body inválido
- Busca de livro inexistente
- Atualização sem body
- Exclusão de livro inexistente

## Como executar
1. Suba a API localmente
2. Importe a collection JSON no Postman
3. Execute primeiro a requisição **Login Admin**
4. Rode as demais requisições

## Arquivo da collection
Use o arquivo JSON deste repositório para importar no Postman.
