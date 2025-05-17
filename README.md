# 🧭 Roadmap Backend

> Este repositório é um **guia completo e progressivo** para quem deseja aprender **desenvolvimento backend com Node.js**, partindo dos fundamentos até práticas avançadas de produção. Ideal para iniciantes e para quem busca estruturar seus estudos com uma trilha moderna e prática.

![Repo size](https://img.shields.io/github/repo-size/your-username/roadmap-backend)
![Contributors](https://img.shields.io/github/contributors/your-username/roadmap-backend)
![Last commit](https://img.shields.io/github/last-commit/your-username/roadmap-backend)

---

## ▶️ Como usar este roadmap

1. Siga os módulos na ordem sugerida.
2. Leia os materiais e pratique com projetos próprios.
3. Marque como concluído cada item (✅) ou use sua própria cópia para acompanhar seu progresso.
4. Contribua com sugestões e melhorias!

---

## 🗺️ Visão Geral da Jornada

```mermaid
graph TD;
  Fundamentos["Fundamentos de Programação"]
  Web["Fundamentos da Web"]
  Node["Node.js"]
  Express["Express.js"]
  BD["Banco de Dados"]
  Auth["Autenticação e Autorização"]
  Arquitetura["Arquitetura e Boas Práticas"]
  Avancado["Integrações e Recursos Avançados"]
  Deploy["Deploy e Escalabilidade"]
  Projeto["Projeto Final"]

  Fundamentos-->Web-->Node-->Express-->BD-->Auth-->Arquitetura-->Avancado-->Deploy-->Projeto

---

## 🗂️ Sumário

1. [Módulo 1: Fundamentos da Programação](#módulo-1-fundamentos-da-programação)
2. [Módulo 2: Fundamentos da Web](#módulo-2-fundamentos-da-web)
3. [Módulo 3: Node.js](#módulo-3-primeiros-passos-com-nodejs)
4. [Módulo 4: Express.js](#módulo-4-expressjs-e-construção-de-apis)
5. [Módulo 5: Banco de Dados](#módulo-5-banco-de-dados)
6. [Módulo 6: Autenticação e Autorização](#módulo-6-autenticação-e-autorização)
7. [Módulo 7: Arquitetura e Boas Práticas](#módulo-7-avançando-com-backend)
8. [Módulo 8: Integrações e Recursos Avançados](#módulo-8-integrações-e-recursos-avançados)
9. [Módulo 9: Deploy e Escalabilidade](#módulo-9-deploy-e-escalabilidade)
10. [Módulo 10: Projeto Final](#módulo-10-projeto-final---backend-profissional)

---

## 📘 Módulo 1: Fundamentos da Programação

- ✅ Lógica de programação (variáveis, condições, loops, funções)
- ✅ Estruturas de dados (arrays, objetos, listas, mapas)
- ✅ Conceitos de algoritmos
- ✅ Git e GitHub  
  [Artigo - Alura](https://www.alura.com.br/artigos/o-que-e-git-github)

## 🌐 Módulo 2: Fundamentos da Web

- ✅ HTTP: métodos, status codes, headers  
  [Métodos HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Reference/Methods)  
  [Status HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Reference/Status)  
  [Headers](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Reference/Headers)

- ✅ Cliente x Servidor  
  [Cloudflare](https://www.cloudflare.com/pt-br/learning/serverless/glossary/client-side-vs-server-side/)

- ✅ APIs: REST e Endpoints  
  [REST API - RedHat](https://www.redhat.com/pt-br/topics/api/what-is-a-rest-api)  
  [Endpoints - IBM](https://www.ibm.com/br-pt/topics/api-endpoint)

- ✅ JSON e comunicação com frontend  
  [O que é JSON?](https://www.glideapps.com/blog/what-is-json)

## 🟢 Módulo 3: Primeiros Passos com Node.js

- ✅ Introdução ao Node.js  
  [Artigo - Alura](https://www.alura.com.br/artigos/node-js)

- ✅ Módulos nativos e servidor HTTP  
  [Criar servidor Node.js](https://www.alura.com.br/artigos/criar-servidor-node-js-sem-apoio-frameworks)

- ✅ npm/yarn  
  [O que é npm?](https://www.hostinger.com.br/tutoriais/o-que-e-npm)

- ✅ Organização de projeto  
  [Boas práticas - LogRocket](https://blog.logrocket.com/node-js-project-architecture-best-practices/)

## 🔧 Módulo 4: Express.js e Construção de APIs

- ✅ Criar API com Express  
  [Guia - Postman](https://blog.postman.com/how-to-create-a-rest-api-with-node-js-and-express/)

- ✅ Middlewares  
  [O que é Middleware?](https://www.redhat.com/pt-br/topics/middleware/what-is-middleware)

- ✅ Parâmetros de rota, query e body  
  [Explicação](https://medium.com/@aidana1529/understanding-the-difference-between-req-params-req-body-and-req-query-e9cf01fc3150)

- ✅ Validação com Joi  
  [Validação com Joi](https://abbaslanbay.medium.com/introduction-to-joi-validation-in-node-js-express-c33eba38f4ae)

- ✅ Upload de arquivos com Multer  
  [Tutorial](https://consolelog.com.br/upload-de-arquivos-imagens-utilizando-multer-express-nodejs/)

- ✅ Tratamento de erros  
  [Guia oficial](https://expressjs.com/en/guide/error-handling.html)

## 🗃️ Módulo 5: Banco de Dados

- ✅ SQL vs NoSQL
- ✅ PostgreSQL / MySQL: modelagem, joins, migrations
- ✅ MongoDB: coleções, documentos, queries
- ✅ ORMs / ODMs: Prisma, Sequelize, Mongoose

## 🔐 Módulo 6: Autenticação e Autorização

- ✅ JWT
- ✅ Sessões e Cookies
- ✅ Hash de senhas com Bcrypt
- ✅ Controle de acesso por perfil

## 🏗️ Módulo 7: Avançando com Backend

- ✅ Arquitetura MVC
- ✅ Services e Repositories
- ✅ SOLID, Clean Code
- ✅ Testes com Jest e Supertest
- ✅ Logs e exceções

## 🔌 Módulo 8: Integrações e Recursos Avançados

- ✅ Envio de e-mails (SMTP, SendGrid)
- ✅ Integrações externas (pagamento, APIs)
- ✅ WebSockets (tempo real)
- ✅ Filas e workers (Bull + Redis)

## 🚀 Módulo 9: Deploy e Escalabilidade

- ✅ Ambientes: dev e prod
- ✅ Variáveis de ambiente (.env)
- ✅ Docker e docker-compose
- ✅ Deploy: Heroku, Railway, Render, VPS, AWS
- ✅ Cache, balanceamento, rate limit

## 🎓 Módulo 10: Projeto Final - Backend Profissional

- ✅ Aplicação realista (e-commerce, sistema de usuários, etc.)
- ✅ Planejamento e arquitetura
- ✅ Construção com testes
- ✅ Documentação (Swagger, Postman)
- ✅ CI/CD e deploy final

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou pull request.

---

## 📜 Licença

MIT © [Seu Nome](https://github.com/seu-usuario)
