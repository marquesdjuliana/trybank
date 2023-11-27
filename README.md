**olá, olá!** Bem-vinda(o) ao repositório do projeto **Trybank**. 

Este é meu primeiro projeto em C#! Foi desenvolvido durante a Eletiva C# da Trybe e representa a implementação inicial de um sistema bancário.

## Sobre o Projeto

O Trybank consiste em um sistema que gerencia contas bancárias e operações financeiras básicas, incluindo verificação de saldo, depósito, saque e transferência de dinheiro. Não persiste dados, utilizando um array multidimensional para armazenar as informações das contas.

## Funcionalidades Implementadas

#### Cadastro de Novas Contas
O sistema permite o registro de novas contas, verificando a existência prévia da combinação de número e agência para evitar duplicatas.

#### Login e Logout
Os usuários podem fazer login e logout, sendo controlado o estado de usuário logado e validada a combinação de número, agência e senha.

#### Verificação de Saldo
Possibilidade de consultar o saldo da conta do usuário logado.

#### Depósito de Dinheiro
Funcionalidade para depositar valores na conta do usuário logado.

#### Saque de Dinheiro
Permite a retirada de valores da conta do usuário logado.

#### Transferência entre Contas
Capacidade de transferir dinheiro entre contas, validando o saldo e a existência das contas envolvidas.

## Habilidades Aplicadas

Durante a realização deste projeto, algumas habilidades foram exercitadas:

- Manipulação de arrays multidimensionais para armazenamento temporário de dados.
- Implementação de funções com validações e tratamento de exceções para garantir a integridade das operações financeiras.
- Separação de responsabilidades e construção de funcionalidades em ordem para facilitar a evolução do sistema.

## Instalação e Execução
Se deseja experimentar o projeto em sua máquina local, siga estas etapas:

1. Clone o repositório:
```sh
git clone git@github.com:marquesdjuliana/trybank.git
```
2. Entre na pasta do repositório:
```sh
cd trybank 
```
2. Instale as dependências:
Entre na pasta:
```sh
cd src/ 
```
Execute o comando:
```sh
dotnet restore 
```
Sinta-se à vontade para explorar este projeto, acompanhar meu crescimento e contribuir, se desejar. Se você tiver alguma sugestão, feedback ou quiser trocar conhecimentos, será um prazer conectar com você no LinkedIn!
