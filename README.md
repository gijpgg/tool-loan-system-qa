# Sistema de Gerenciamento de Ferramentas Emprestadas

Este projeto foi desenvolvido com o objetivo de gerenciar o empréstimo de ferramentas, permitindo o controle de cadastros, empréstimos, devoluções e relatórios.

O projeto inclui documentação completa de requisitos, user stories, testes de aceitação e cenários de teste, com foco em Qualidade de Software (QA).

---

## 🎯 Objetivo

Controlar o empréstimo de ferramentas entre usuários, garantindo rastreabilidade, organização e validação de regras de negócio.

---

## ⚙️ Funcionalidades

- Cadastro de ferramentas (nome, marca, custo)
- Cadastro de amigos (nome e telefone)
- Registro de empréstimos
- Registro de devoluções
- Relatório de ferramentas
- Relatório de empréstimos
- Validação de regras (ex: impedir empréstimo com pendências)
- (Extra) Integração com agenda

---

## 🧾 User Stories

### 📦 Cadastro de ferramentas
Como usuário, desejo cadastrar ferramentas com nome, marca e custo de aquisição para acessar facilmente informações dos produtos.

---

### 👥 Cadastro de amigos
Como usuário, desejo cadastrar amigos com nome e telefone para ter controle e contato de quem utiliza os serviços.

---

### 🔄 Registro de empréstimos
Como usuário, desejo registrar empréstimos com data de retirada e devolução para controlar quem devolveu ou não.

Como usuário, desejo ser informado se o cliente possui pendências antes de realizar um novo empréstimo.

---

### 📊 Relatórios
Como usuário, desejo visualizar relatórios de ferramentas e empréstimos para controlar custos e acompanhar devoluções pendentes.

---

## 🧪 Testes de Aceitação (Exemplos)

### Cadastro de ferramentas

- [ ] Cadastro válido com todos os campos preenchidos
- [ ] Exibir erro ao tentar cadastrar sem campos obrigatórios
- [ ] Editar ferramenta existente
- [ ] Excluir ferramenta
- [ ] Visualizar lista de ferramentas cadastradas

---

### Cadastro de amigos

- [ ] Cadastro válido com nome e telefone
- [ ] Exibir erro ao faltar informações obrigatórias
- [ ] Editar cadastro
- [ ] Excluir amigo
- [ ] Visualizar lista de amigos

---

### Empréstimo de ferramentas

- [ ] Registrar empréstimo com dados válidos
- [ ] Impedir empréstimo para usuário com pendências
- [ ] Validar datas inválidas (devolução < empréstimo)
- [ ] Atualizar status da ferramenta para indisponível

---

### Relatório de empréstimos

- [ ] Exibir lista de empréstimos (ativos e concluídos)
- [ ] Registrar devolução
- [ ] Destacar empréstimos pendentes
- [ ] Atualizar status após devolução

---

## 📋 Requisitos Funcionais

- O sistema deve permitir cadastro, edição e exclusão de ferramentas e usuários
- O sistema deve validar disponibilidade de ferramentas
- O sistema deve impedir empréstimos com pendências
- O sistema deve validar datas de empréstimo
- O sistema deve gerar relatórios de ferramentas e empréstimos
- O sistema deve destacar empréstimos em atraso

---

## 🔄 Fluxo do Sistema

Cadastro → Ferramenta disponível → Empréstimo → Indisponível → Devolução → Disponível

---

## 🧠 Regras de Negócio

- Não permitir empréstimos para usuários com pendências
- Não permitir datas inválidas
- Ferramentas emprestadas ficam indisponíveis
- Empréstimos em atraso devem ser destacados

---

## 🐞 Pontos de melhoria identificados

- Implementar notificações de atraso
- Melhorar validações de entrada
- Criar histórico detalhado de empréstimos
- Melhorar integração com agenda

---

## 📊 Documentação do Projeto

O projeto inclui:

- User Stories  
- Testes de aceitação  
- Requisitos funcionais  
- Diagramas UML (classe, sequência, casos de uso)  
- Modelo ER do banco de dados  

---

## Projeto original

As user stories e organização inicial foram realizadas no Trello:

👉 https://trello.com/b/OKOSxJvn

---

Este projeto foi desenvolvido durante minha graduação, com foco em aplicar conceitos de engenharia de software e qualidade.

## 👩‍💻 Minha participação
Responsável pela modelagem de requisitos, definição de user stories e criação de cenários de teste.
