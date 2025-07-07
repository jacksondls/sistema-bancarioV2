# sistema-bancarioV2
# 🏦 Sistema Bancário em Python

Este é um sistema bancário desenvolvido em Python como parte do **Bootcamp Santander 2025**, com foco no uso de **Programação Orientada a Objetos (POO)**, boas práticas e organização de código.

## 📌 Funcionalidades

- Criar novo cliente
- Criar conta corrente
- Depósito em conta
- Saque com limite e controle de quantidade
- Histórico de transações com data e hora
- Visualização de extrato
- Listagem de contas cadastradas

## 📂 Estrutura do Projeto

O sistema é baseado em conceitos de orientação a objetos:

- `Cliente` (classe base)
- `PessoaFisica` (herda de Cliente)
- `Conta` e `ContaCorrente`
- `Transacao`, `Saque` e `Deposito` (com uso de classe abstrata)
- `Historico` para armazenar as movimentações

## 🧠 Conceitos Aprendidos

- Classes e Herança
- Métodos e Propriedades
- Métodos Estáticos e de Classe
- Encapsulamento com `@property`
- Polimorfismo
- List Comprehensions
- Manipulação de datas com `datetime`
- Abstração com `abc` (classe abstrata)

## 📷 Exemplo de uso

```bash
=============== MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo cliente
[q] Sair
=>
