# Formulário de Reembolso – CSAT5

Este repositório contém **exclusivamente o frontend estático** (HTML/CSS/JavaScript)
do formulário de solicitação de reembolso de despesas do projeto **CSAT5**.

O objetivo deste projeto é fornecer uma interface de preenchimento para os usuários,
integrada a um backend corporativo baseado em **Microsoft Power Automate**.

---

## 📌 Escopo do Repositório

- ✅ Interface de usuário (HTML, CSS e JavaScript puro)
- ✅ Validações básicas no lado do cliente
- ❌ **Nenhum backend**
- ❌ **Nenhum armazenamento de dados**
- ❌ **Nenhum log de informações pessoais**

Este repositório **não contém** regras de negócio, armazenamento ou processamento
de dados sensíveis.

---

## 🌐 Hospedagem do Frontend (Solução Transitória)

O formulário está hospedado temporariamente por meio do **GitHub Pages**.

Essa decisão foi tomada devido a limitações atuais de permissão para criação de
páginas ou hospedagem de conteúdo dinâmico no SharePoint corporativo no momento.

❗ O uso do GitHub Pages é **exclusivamente para a distribuição de conteúdo estático**
(HTML/CSS/JavaScript), sem qualquer tratamento ou persistência de dados.

---

## 🔐 Tratamento de Dados Pessoais (LGPD)

### Importante

Este repositório e o GitHub Pages **NÃO armazenam, processam ou registram** dados pessoais.

O fluxo de dados ocorre da seguinte forma:

1. O usuário preenche o formulário diretamente no navegador;
2. Os dados são transmitidos **via HTTPS** diretamente para um fluxo do
   **Power Automate** pertencente ao tenant corporativo da empresa;
3. O tratamento, processamento, armazenamento e auditoria dos dados ocorrem
   exclusivamente dentro do ecossistema **Microsoft 365** (Power Automate,
   Outlook, SharePoint e/ou OneDrive corporativos).

📌 **O GitHub não atua como operador nem controlador de dados pessoais**, servindo
apenas como repositório e hospedagem de código estático.

---

## 🏢 Controlador e Operador dos Dados

- **Controlador dos dados**: A própria empresa (proprietária do tenant Microsoft 365)
- **Operador dos dados**: Microsoft (conforme DPA e contratos vigentes)

Todo o tratamento de dados está em conformidade com a **Lei Geral de Proteção de Dados (LGPD)**,
considerando que não há tratamento de dados fora do ambiente corporativo.

---

## 🔄 Plano de Migração

Esta solução é considerada **TRANSITÓRIA**.

Assim que houver a liberação para criação de páginas formais no SharePoint ou adoção
de outra plataforma corporativa de frontend (ex.: Power Apps, Azure Static Web Apps),
o formulário será migrado **sem necessidade de alterações no backend**.

A arquitetura foi desenhada de forma desacoplada, permitindo que a migração ocorra
apenas com a substituição da URL de acesso ao formulário.

---

## ⚙️ Arquitetura Resumida

``
