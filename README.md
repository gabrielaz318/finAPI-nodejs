## FinAPI - Financeira

---

### Requisitos

- [x] deve ser possível criar uma conta
- [x] deve ser possível buscar o extrato bancário do cliente
- [x] deve ser possível realizar um depósito
- [x] deve ser possível realizar um saque
- [x] deve ser possível buscar o extrato bancário do cliente por data
- [x] deve ser possível atualizar dados da conta do cliente
- [x] deve ser possível deletar uma conta
- [x] deve ser possível retornar o saldo

---

### Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente
- [x] Não deve ser possível visualizar o saldo de uma conta não existente