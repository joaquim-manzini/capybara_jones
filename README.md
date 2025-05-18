# 🦫 Capybara Jones – AI Interface Project

Este repositório contém dois projetos integrados:

- 📦 **Backend**: Um serviço Python usando Flask e a API do Google Gemini.
- 🎨 **Frontend**: Uma aplicação Next.js estilizada com o moderno sistema de componentes **shadcn/ui**.

---

## 📁 Estrutura do Projeto

```
.
├── backend/     # Código Python + Flask + Google Gemini
│   └── capybara_jones.py
│
├── frontend/    # Aplicação Next.js com shadcn/ui
│   └── (componentes, páginas, etc.)
│
└── README.md
```

---

## 🚀 Como rodar o projeto

### ✅ Requisitos

- **Python 3.10+**
- **Node.js 18+**
- **Yarn**
- Conta e chave válida no **Google AI / Gemini API**

---

### 🔧 Rodando o Backend (Flask + Gemini)

```bash
cd backend
python capybara_jones.py
```

A API será iniciada localmente (por padrão, em `http://localhost:5000`).

---

### 💻 Rodando o Frontend (Next.js + shadcn/ui)

```bash
cd frontend
yarn install
yarn dev
```

A interface estará disponível em: `http://localhost:3000`.

---

## 🧠 Tecnologias usadas

### Backend
- Python
- Flask
- Google Gemini API

### Frontend
- Next.js
- React
- Tailwind CSS
- shadcn/ui

---

## 🛠️ Possibilidades futuras

- Integração com autenticação
- Histórico de conversas
- Armazenamento vetorial com embeddings
- Suporte a múltiplos modelos de IA

---

## 🤖 Capybara Jones?

Porque todo projeto sério merece um mascote carismático. 🦫💬

---

## 📄 Licença

Este projeto é open-source, sob a licença [MIT](LICENSE).
