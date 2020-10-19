
<h1 align="center">
    <img alt="Happy" title="Happy" src="./.github/assets/images/happy-logo.png"/>
</h1>

<p align="center">
    <img src="https://img.shields.io/badge/NEXT%20LEVEL%20WEEK-3-15C3D6?style=flat-square">
    <img src="https://img.shields.io/badge/LICENSE-MIT-15C3D6?style=flat-square">
</p>

<p align="center">
    <a href="#-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-preview">Preview</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-instalação">Instalação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-licença">Licença</a>
</p>

## 📋 Sobre
O happy é uma aplicação que facilita a visitação à casas  de acolhimento institucional, com o objetivo de conectar mais pessoas a esse espaço tão importante.

## 📷 Preview
<img src="./.github/assets/gifs/preview-happy.gif" alt="Demonstração da plataforma Happy" />

## 🚀 Tecnologias
Foram utilizadas as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)

## 💾 Instalação
Este é um monorepositório, portanto possui as fontes do projeto web, api e mobile. Para executa-lo, é necessário utilizar, ou o npm, ou o yarn, e também instalar as dependências de cada parte do projeto separadamente.

**Web:**
```bash
> cd happy/web
> npm install
```

Para executa-lo é necessário um token de autenticação da API do MapBox. Acesse o site [MapBox](https://account.mapbox.com/) para adquirir o seu. Quando estiver com ele, crie um arquivo `.env` e coloque seu token como valor, vide o exemplo: 

`REACT_APP_MAPBOX_TOKEN=seutoken`

Após os procedimentos:
```bash
> npm start
```

**Back-End**
```bash
> cd happy/backend
> npm install
```

Para criar um banco e startar o servidor: 
```bash
> npx typeorm migration:run
> npm run dev
```

## 📝 Licença
Esse projeto está sob a licença [MIT](./LICENSE). 
