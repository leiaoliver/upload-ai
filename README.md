<h1 align="center" style="text-align: center;">
  upload.ai
</h1>

> Projeto desenvolvido na Trilha Mastery da NLW IA da Rocketseat.

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<h2 id="project">📁 Projeto</h2>

O projeto consiste num gerador de descrições e títulos para vídeos do YouTube a partir da transcrição do conteúdo.

<h2 id="technologies">💻 Tecnologias</h2>

Este projeto foi desenvolvido utilizando tecnologias como:

- Node.js
- TypeScript
- Fastify
- Prisma
- Dotenv
- OpenAI
- Zod

<h2 id="usage">💡 Utilização</h2>

Para executar a aplicação em sua máquina localmente, certifique-se de ter o `Node.js` e o `npm` instalados antes de prosseguir com as etapas abaixo:

1. Clone o projeto:

```
$ git clone https://github.com/madalena-rocha/upload-ai-api
```

2. Acesse a pasta do projeto:

```
$ cd upload-ai-api
```

3. Instale as dependências:

```
$ npm install
```

4. Execute as migrações:

```
$ npx prisma migrate dev
```

5. Inicie o servidor:

```
$ npm run dev
```

⚠️ **Importante**: Crie um arquivo .env de acordo com o arquivo .env.example. No campo DATABASE_URL, especifique a URL do banco de dados que deseja utilizar. Crie uma conta no site [OpenAI](https://openai.com/), obtenha sua chave da API e preencha o campo OPENAI_KEY com sua chave.

<h2 id="license">📝 Licença</h2>

Este projeto está sob a licença MIT.

---

Feito com 💜 by Léia 👋🏾

<div style="display: flex;">
  <a href="https://www.linkedin.com/in/l%C3%A9ia-silva-de-oliveira/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="margin-right: 2vw" target="_blank"></a>
  <a href="https://www.instagram.com/leiaoliver388/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
</div>
