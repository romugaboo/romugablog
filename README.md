# Romugablog

Blog com área de administração, feito em Node.js. Os artigos ficam organizados por categoria e cada um ganha uma URL própria a partir do título. Só quem faz login consegue criar, editar ou apagar artigos, categorias e usuários.

## Tecnologias

Node.js, Express, EJS, Sequelize, MySQL, express-session e bcryptjs (para as senhas).

## Como rodar

1. Crie no MySQL um banco chamado `guidepress`. O usuário e a senha ficam em `database/database.js` (o padrão é `root` / `root`).
2. Instale as dependências e suba o servidor:

```bash
npm install
npm start
```

3. Abra http://localhost:8080.

Na primeira vez, descomente as linhas `sync` no fim de cada arquivo em `models/` para o Sequelize criar as tabelas, e depois comente de novo.

<br/>

<div align="center">
<sub>made with love by <a href="https://romugaboo.github.io">romugaboo</a> from brazil ✧ silly online ♡</sub>
</div>
