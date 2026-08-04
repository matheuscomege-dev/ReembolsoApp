# Reembolso App

SaaS multi-tenant para gestão de reembolsos e despesas corporativas.

🔗 **Web:** https://www.reembolsoapp.com.br/
📱 **Mobile:** Responsivo pelo site no momento

---

## O que é

O Reembolso App é uma plataforma B2B para empresas gerenciarem solicitações de reembolso de despesas de forma centralizada, com hierarquia de permissões e exportação de dados prontos para contabilidade/financeiro.

## Funcionalidades

- ✅ Cadastro e acompanhamento de solicitações de reembolso
- ✅ Hierarquia de três níveis: dono / admin / usuário
- ✅ Exportação em `.xlsx` com mapeamento de colunas configurável por carteira
- ✅ Download de anexos em ZIP com link tokenizado (acesso temporário e seguro)
- ✅ Multi-tenant: cada empresa opera de forma isolada na mesma plataforma

## Stack

| Camada | Tecnologia |
|---|---|
| Backend | Flask (Python) |
| Autenticação / Dados | Firebase Auth, Firebase Storage, Realtime Database |
| Proxy | PHP |
| Exportação de dados | SheetJS (`.xlsx`) |
| Infraestrutura | AWS Lightsail (Debian 12) |

## Screenshots

<!-- Adicionar prints aqui -->
<!-- ![Dashboard de reembolsos](./screenshots/dashboard.png) -->
<!-- ![Nova solicitação](./screenshots/nova-solicitacao.png) -->
<!-- ![Exportação xlsx](./screenshots/exportacao.png) -->

---

Desenvolvido por [Matheus Comege](https://matheuscomege.com.br)
