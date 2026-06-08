# Xhopii MVC

Projeto PHP em MVC para cadastro e consulta de clientes, funcionarios,
produtos, lojas e cupons da loja Xhopii.

## Estrutura

- `controller/`: controlador principal da aplicacao.
- `model/`: classes de dominio e acesso ao banco.
- `view/`: telas PHP da interface.
- `processamento/`: recebimento dos formularios.
- `assets/`: arquivos CSS, JS e imagens.
- `banco_xhopii.sql`: script para criar e popular o banco inicial.

## Como executar

1. Copie a pasta do projeto para o `htdocs` do XAMPP.
2. Inicie Apache e MySQL.
3. Importe `banco_xhopii.sql` no phpMyAdmin ou pelo terminal MySQL.
4. Acesse `http://localhost/xhoppi-BD/`.

O sistema usa o banco `xhopii_integrado` com usuario `root` e senha vazia,
conforme configurado em `controller/Controlador.php`.

## Acesso de teste

- E-mail: `funcionario@xhopii.com`
- Senha: `123456`
