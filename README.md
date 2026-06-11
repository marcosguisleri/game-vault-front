<div align="center">

<img src="public/images/game-vault-logo.png" alt="Game Vault Logo" width="180"/>

# 🎮 Game Vault — Front-end

### Interface web para sua biblioteca de jogos

[![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

</div>

---

## 📖 Sobre

Front-end em **Angular 22** para o [Game Vault API](https://github.com/marcosguisleri/game-vault) — uma interface visual para gerenciar sua biblioteca de jogos.

> 🔗 O back-end (Java + Quarkus) está no repositório **[game-vault](https://github.com/marcosguisleri/game-vault)**.

---

## 🏗️ Estrutura

```
src/app/
├── components/
│   ├── header/        # Cabeçalho com logo e navegação
│   └── footer/        # Rodapé
└── pages/
    ├── home/          # Landing page com hero section
    └── library/       # Página da biblioteca (em desenvolvimento)
```

---

## 🧰 Tecnologias

| Tecnologia | Uso |
|---|---|
| Angular 22 | Framework principal |
| TypeScript 6 | Tipagem e lógica de componentes |
| Tailwind CSS 4 | Estilização utilitária |
| RxJS | Programação reativa |
| Angular Router | Navegação entre páginas |

---

## ▶️ Como executar

**Pré-requisitos:** Node.js 20+, npm 11+ e a **[Game Vault API](https://github.com/marcosguisleri/game-vault) rodando em `localhost:8080`**.

```bash
# Clone o repositório
git clone https://github.com/marcosguisleri/game-vault-front.git
cd game-vault-front

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start
```

Acesse em: **`http://localhost:4200`**

---

## 🗺️ Roadmap

- [x] Estrutura base do projeto com Angular 22
- [x] Roteamento entre páginas (`/` e `/biblioteca`)
- [x] Header com logo e navegação
- [x] Footer
- [x] Home page com hero section
- [ ] Listagem de jogos consumindo a API
- [ ] Capas automáticas via RAWG API
- [ ] Adicionar, editar e excluir jogos
- [ ] Filtros, busca e ordenação
- [ ] Página de detalhe do jogo

---

## 👨‍💻 Autor

Desenvolvido por **Marcos Guisleri**

[![GitHub](https://img.shields.io/badge/GitHub-marcosguisleri-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marcosguisleri)
