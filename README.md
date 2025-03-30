# Sistema Bancário com POO em Python

## Índice

- [Descrição](#descrição)
- [Como Usar](#como-usar)
- [Exemplo de Saída Esperada](#exemplo-de-saída-esperada)
- [Pré-Requisitos](#pré-requisitos)
- [Contribua](#contribua)
- [Licença](#licença)
- [Contato e Network](#contato-e-network)


## Descrição

Este projeto implementa um **sistema bancário** utilizando **Programação Orientada a Objetos (POO)** em Python. O sistema permite a criação de clientes e contas bancárias, realizando operações como **depósitos**, **saques**, e **consultas de extrato**. O sistema utiliza conceitos de classes, herança, polimorfismo e encapsulamento para gerenciar as transações e a estrutura bancária.

### Funcionalidades:
- **Criação de Clientes:** O sistema permite a criação de novos clientes com informações como nome, CPF, data de nascimento e endereço.
- **Criação de Contas:** Cada cliente pode ter uma conta bancária associada, com um número e saldo inicial.
- **Operações Bancárias:**
  - **Depósito**: O cliente pode realizar depósitos em sua conta.
  - **Saque**: O cliente pode realizar saques, respeitando limites de saque e saldo.
  - **Extrato**: O cliente pode consultar o extrato da sua conta, visualizando transações realizadas.
- **Histórico de Transações**: O sistema mantém um histórico completo de todas as transações realizadas (saques e depósitos).

A abordagem orientada a objetos facilita a manutenção e expansão do sistema, permitindo adicionar facilmente novas funcionalidades ou alterar o comportamento das existentes.


## Como Usar

### 1. **Clone o Repositório**
   Para clonar este repositório em seu computador, execute o seguinte comando no terminal:
   ```bash
   git clone https://github.com/jacivaldocarvalho/sistema-bancario-poo-python.git
   ```

### 2. **Instale o Python**
   Este sistema foi desenvolvido utilizando **Python 3.x**. Se você não tem o Python instalado, baixe a versão mais recente [aqui](https://www.python.org/downloads/).

### 3. **Execute o Código**
   Após clonar o repositório e garantir que o Python esteja instalado, abra o terminal ou prompt de comando e navegue até o diretório do repositório clonado. Em seguida, execute o script com o seguinte comando:
   ```bash
   python sistema_bancario.py
   ```

### 4. **Menu Interativo**
   O sistema exibe um menu interativo no terminal onde o usuário pode escolher entre as seguintes opções:
   - **Novo Cliente (nu)**: Criar um novo cliente.
   - **Nova Conta (nc)**: Criar uma nova conta bancária para um cliente.
   - **Listar Contas (lc)**: Listar todas as contas bancárias cadastradas.
   - **Depositar (d)**: Realizar um depósito em uma conta.
   - **Sacar (s)**: Realizar um saque de uma conta.
   - **Extrato (e)**: Exibir o extrato de uma conta.
   - **Sair (q)**: Finalizar o programa.

### 5. **Exemplo de Uso**

   Após rodar o código, o menu será exibido no terminal. Aqui está um exemplo de como as operações funcionam:

   ```
   ============== BEM VINDO =============
   ================ MENU ================
   [nu] Novo Cliente
   [nc] Nova conta
   [lc] Listar contas
   [d] Depósito
   [s] Sacar
   [e] Extrato
   [q] Sair
   ======================================
   => nu
   Informe o CPF (somente número): 12345678900
   Informe o nome completo: João da Silva
   Informe a data de nascimento (dd-mm-aaaa): 01-01-1980
   Informe o endereço (logradouro, nro - bairro - cidade/sigla estado): Rua X, 123 - Centro - SP/SP
   === Cliente criado com sucesso! ===
   ```


## Exemplo de Saída Esperada

Aqui está um exemplo de como o sistema funciona:

1. **Criando um Cliente e Conta:**
   ```
   ============== BEM VINDO =============
   ================ MENU ================
   [nu] Novo Cliente
   [nc] Nova conta
   [lc] Listar contas
   [d] Depósito
   [s] Sacar
   [e] Extrato
   [q] Sair
   ======================================
   => nu
   Informe o CPF (somente número): 12345678900
   Informe o nome completo: João da Silva
   Informe a data de nascimento (dd-mm-aaaa): 01-01-1980
   Informe o endereço (logradouro, nro - bairro - cidade/sigla estado): Rua X, 123 - Centro - SP/SP
   === Cliente criado com sucesso! ===

   => nc
   Informe o CPF do cliente: 12345678900
   === Conta criada com sucesso! ===
   ```

2. **Depósito e Saque:**
   ```
   => d
   Informe o CPF do cliente: 12345678900
   Informe o valor do depósito: 500
   Depósito realizado com sucesso!

   => s
   Informe o CPF do cliente: 12345678900
   Informe o valor do saque: 200
   Saque realizado com sucesso!
   ```

---

## Pré-Requisitos

Este projeto foi desenvolvido utilizando **Python 3.x**. Não há dependências externas, então o único requisito é ter o Python instalado no seu sistema.

- **Python 3.x**: Para rodar o sistema bancário.


## Contribuições

Se você tiver sugestões de melhorias ou encontrar problemas com o script, sinta-se à vontade para abrir um **issue** ou submeter um **pull request**.

## Contatos e Network

- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/jacivaldocarvalho/) 👔
- **E-mail**: [E-mail](mailto:jacivaldocarvalho@gmail.com) 📧
- **GitHub**: [GitHub](https://github.com/jacivaldocarvalho) 🐙
- **Medium**: [Medium](https://medium.com/@jacivaldocarvalho) ✍️

Sempre aberto a novas conexões e oportunidades de aprendizado!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
