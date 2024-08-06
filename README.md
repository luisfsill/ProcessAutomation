# Automação de Processo em Python

Este projeto automatiza o processo de login e cadastro de produtos em um sistema de gestão de produtos utilizando Python e a biblioteca `pyautogui`.

## Descrição do Projeto

O script executa as seguintes etapas:
1. Abre o navegador e entra no sistema da empresa.
2. Faz login no sistema.
3. Importa a base de dados de produtos.
4. Cadastra cada produto no sistema, preenchendo os campos necessários.

## Requisitos

- Python 3.x
- Bibliotecas: `pyautogui`, `time`, `pandas`

## Instalação

1. Clone este repositório.
2. Instale as bibliotecas necessárias com o comando:
    ```bash
    pip install pyautogui pandas
    ```

## Passo a Passo do Projeto

### Passo 1: Entrar no Sistema da Empresa

Acesse o sistema da empresa pelo link:
[https://dlp.hashtagtreinamentos.com/python/intensivao/login](https://dlp.hashtagtreinamentos.com/python/intensivao/login)

### Passo 2: Fazer Login

Preencha os campos de login com seu email e senha, e clique no botão de login.

### Passo 3: Importar a Base de Produtos

Carregue a base de dados de produtos a partir de um arquivo CSV.

### Passo 4: Cadastrar um Produto

Para cada produto na base de dados, preencha os campos de cadastro no sistema, incluindo código, marca, tipo, categoria, preço unitário, custo e observações, e clique no botão de enviar.

### Passo 5: Repetir o Processo de Cadastro

O script irá repetir o processo de cadastro até o final da tabela de produtos.

## Observações

- Certifique-se de que os campos no sistema e no arquivo `produtos.csv` correspondem.
- Ajuste as coordenadas dos cliques conforme necessário para o seu sistema.
