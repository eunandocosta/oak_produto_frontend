# Oak Produtos Frontend

## Descrição

Este é um exemplo de um aplicativo simples de listagem de produtos usando HTML, CSS e JavaScript, com comunicação assíncrona via API REST. Este aplicativo foi desenvolvido para registrar e exibir produtos em uma lista.

## Funcionalidades

- **Registro de Produto:** Os usuários podem inserir o nome, o valor e a disponibilidade de um produto em um formulário.
- **Exibição da Lista de Produtos:** A lista de produtos é exibida abaixo do formulário de registro.
- **Comunicação com o Servidor:** Os dados do produto são enviados para um servidor local executando uma API REST.
- **Atualização Automática:** A lista de produtos é atualizada automaticamente a cada 5 segundos.

## Pré-requisitos

Para executar este aplicativo, você precisará ter:

- Um navegador da web atualizado.
- Um servidor local em execução com uma API REST. Recomenda-se usar Spring Boot para o servidor. Certifique-se de que o servidor esteja configurado para responder às solicitações nos endpoints `/api/inserir` e `/api/receber`.

## Como usar

1. Clone este repositório em sua máquina local.
2. Certifique-se de que o servidor esteja em execução e configurado corretamente.
3. Abra o arquivo `index.html` em um navegador da web.
4. Preencha o formulário de registro com os detalhes do produto e envie.
5. A lista de produtos será exibida abaixo do formulário.
6. Os dados enviados serão salvos no servidor e a lista de produtos será atualizada automaticamente.

## Estrutura do Projeto

- **index.html:** Contém a estrutura HTML, o formulário de registro e a lista de produtos.
- **style.css:** Arquivo de estilo para estilização do aplicativo.
- **script.js:** Arquivo JavaScript para manipulação do DOM e comunicação com o servidor.

## Observações

- Este aplicativo é apenas um exemplo simples e pode ser expandido para incluir mais funcionalidades, como edição e exclusão de produtos, autenticação de usuários, etc.
- Certifique-se de configurar corretamente o servidor e ajustar os endpoints da API REST, se necessário, para que o aplicativo funcione corretamente.

