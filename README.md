# Node.js + MySQL + JWT template (v1)

Esse é um template criado por mim para facilitar a criação de novos projetos de API's back-end (Node, Typescript, Express, MySQL + JWT). Ele é utilizado em outros templates com diferentes variações.

## Setup

- `mv env-example .env`;
- `docker compose up --build -d`

## Template tree

```
├── Node.js template
│   └── Node.js + MySQL template
│   |   ├── Node.js + MySQL + JWT template
│   |   └── Node.js + MySQL + OAuth template
```

#### Node.js template

- Node.js
- Express.js
- Typescript
- Jest
- ESlint
- Prettier
- Husky + lint-staged (pre-commit / pre-push)
- Path map (tsc-alias, tsconfig-paths)

#### Node.js + MySQL template

- Docker
- MySQL
- Dotenv

#### Node.js + MySQL + JWT template

- JWT Authentication
