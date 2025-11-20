# 🏥 FarmaHub API

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

> **API RESTful** para gerenciamento de Marketplace Farmacêutico, focada em controle de estoque, fluxo de vendas e segurança.

---

## 💻 Sobre o Projeto

A **FarmaHub API** é o back-end robusto de um sistema de e-commerce voltado para farmácias. O projeto foi desenvolvido com foco em **Clean Code** e arquitetura escalável, gerenciando o fluxo completo entre **Farmacêuticos** (Administradores) e **Compradores**.

O sistema implementa regras de negócio complexas, como validação de estoques em tempo real, aplicação de cupons de desconto com verificação de validade e controle de acesso baseado em cargos (RBAC).

---

## 🚀 Tecnologias e Ferramentas

O projeto utiliza as principais tecnologias do mercado atual:

- **Linguagem:** [TypeScript](https://www.typescriptlang.org/) (Superset JavaScript)
- **Runtime:** [Node.js](https://nodejs.org/)
- **Framework:** [Express](https://expressjs.com/)
- **Database & ORM:** [SQLite](https://www.sqlite.org/) com [TypeORM](https://typeorm.io/)
- **Validação:** [Zod](https://zod.dev/) (Schema Validation)
- **Segurança:** - [Passport-JWT](https://www.passportjs.org/) (Estratégia de Autenticação)
  - [Bcrypt](https://www.npmjs.com/package/bcrypt) (Hashing de senhas)

---

## ⚙️ Funcionalidades Principais

### 🔐 Segurança e Acesso (RBAC)
- **Autenticação JWT:** Login seguro com tokens de sessão.
- **Farmacêutico:** Permissão total para gestão de produtos e criação de campanhas (cupons).
- **Comprador:** Acesso exclusivo às funcionalidades de compra, carrinho e favoritos.

### 📦 Gestão de Estoque
- CRUD completo de produtos.
- **Trava de Estoque:** O sistema impede automaticamente a venda de itens sem quantidade suficiente.

### 🛒 Fluxo de Venda
- **Carrinho Inteligente:** Adição e remoção dinâmica de itens.
- **Sistema de Cupons:** Validação de códigos promocionais, verificando existência e data de expiração.
- **Favoritos:** Lista de desejos persistente por usuário.
- **Pedidos:** Finalização de compra com baixa automática no banco de dados.

---

## 🛠️ Instalação e Execução

Siga os passos abaixo para rodar a API localmente:

### Pré-requisitos
- Node.js (v18+)
- Git

### Passo a passo

1. **Clone o projeto ou baixe os arquivos.**

