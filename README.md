README.md — Pokédex React (Desafio CIAg)
==================
Pokédex React — Desafio Técnico CIAg

Este projeto foi desenvolvido como solução do Desafio 1 — Pokédex, conforme o documento oficial enviado no processo seletivo do CIAg.
A aplicação consome a PokeAPI, permite buscar Pokémon, visualizar detalhes e gerenciar favoritos com persistência em backend próprio.

Tecnologias utilizadas
Frontend

React 18

Vite

React Router DOM

Axios

CSS puro simples e responsivo

Backend

Node.js

Express

SQLite (better-sqlite3)

UUID para IDs únicos

CORS

Funcionalidades Entregues
Busca

Buscar Pokémon por nome ou ID

Exibir sprite, nome, número e informações complementares

Detalhes

Tipos

Habilidades

Stats

Visualização em modal

Favoritos

Adicionar Pokémon aos favoritos

Listar favoritos

Remover favoritos

Persistência completa no SQLite

Integração Completa

Frontend React consumindo:

PokeAPI

Backend em Node.js (CRUD para favoritos)

Estrutura do Projeto
pokedex-react/
 ├─ src/
 │   ├─ components/
 │   ├─ pages/
 │   ├─ services/
 │   ├─ App.jsx
 │   ├─ main.jsx
 │   └─ index.css
 ├─ package.json
 ├─ vite.config.js
 └─ index.html

Como rodar o projeto local
1. Baixe o repositório
git clone https://github.com/SEU-USUARIO/pokedex-react.git

Instale as dependências
npm install
Start do frontend
npm run dev


Acesse:
http://localhost:5173/

Backend (Favoritos)
Estrutura
backend/
 ├─ server.js
 ├─ package.json
 └─ favorites.db (gerado automaticamente)

Rodando o backend
cd backend
npm install
npm start


Roda em:
http://localhost:4000/api

Deploy
Frontend publicado em

GitHub Pages
GitHub Actions opcional
Deploy Vercel opcional

Backend sugerido

Railway
Render
Cyclic (gratuito)

Melhorias futuras

Paginação completa

Busca avançada por tipos

Filtros combinados

Interface com tema dark
Versão 100% PWA

Desenvolvido por

Núbia Zanchetta
Tecnologia da Informação | Desenvolvimento Front/Back | ADS

Este projeto foi entregue como solução oficial para o desafio técnico CIAg — Desafio 1 (Pokédex).
