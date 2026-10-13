# Projeto React Alura

Versão personalizada do **Organo**, o organograma de times do curso de React da Alura: um formulário cadastra colaboradores, que aparecem em cards agrupados por time (Back-End, Front-End, Data Science, Devops etc.).

> 📦 **Projeto de estudo** — não recebe mais atualizações.

## Contexto

Feito em agosto de 2023, com base no projeto [`organo`](https://github.com/marcio-sgomes/organo) e acrescentando um componente de plano de fundo (`BackGround`), banner animado e ícones de redes sociais.

## Tecnologias

- **React 18** — componentes e estado com `useState`.
- **Create React App (react-scripts 5)** — build e servidor de desenvolvimento.
- **CSS por componente** — estilos ao lado de cada componente em `src/componentes/`.

## Como rodar

Pré-requisito: Node.js (versão LTS) e npm.

```bash
npm install
npm start
```

O app abre em <http://localhost:3000>. Outros scripts: `npm run build` e `npm test`.

## Estrutura

- `src/App.js` — times e estado dos colaboradores.
- `src/componentes/` — BackGround, Banner, Formulario, CampoTexto, ListaSuspensa, Botao, Time e Colaborador.
- `public/imagens/` — banner, fundo, logo e ícones de redes sociais.
