<div align="center">
  <h1>Olá, eu sou o Luiz 👋</h1>
  <p><b>Desenvolvedor Fullstack • Focado em Backend com Node.js</b></p>
</div>

### 🧩 Sobre mim

Sou um desenvolvedor focado em construir o que não aparece na tela, mas que faz tudo funcionar. Gosto da complexidade do backend: organizar rotas, garantir que o banco de dados responda rápido e, principalmente, entender como cada peça se encaixa na arquitetura.

---

### 🛠️ Tech Stack

* **Linguagens & Frameworks:** Node.js, Express, NestJS, JavaScript, TypeScript.
* **Banco de Dados:** PostgreSQL, MySQL, PrismaORM e TypeORM.
* **Segurança & Validação:** CORS, Helmet, rate-limit, JWT, Bcrypt para criptografia e Zod para garantir a integridade dos dados.
* **Workflow:** Git/GitHub para versionamento, Insomnia/Postman para testes de API e Docker para conteinerização.

---

### 📂 No que tenho trabalhado?

#### 📝 [TaskAPI](https://github.com/luiz-fardim/taskflow-api)
API de gerenciamento de tarefas construída como laboratório prático de autenticação JWT — implementando o fluxo completo do zero: registro, hash de senha, geração de token e middleware de proteção de rotas.
* **Arquitetura:** Camadas bem definidas (Controller → Service → Banco), com schemas de validação isolados e middlewares próprios para auth, validação e rate limit.
* **Autenticação:** Registro e login com JWT + bcrypt, rotas de tarefas protegidas por Bearer Token.
* **Segurança:** Helmet e rate limiting configurados para reforçar a postura de segurança da API.
* **Validação:** Schemas com Zod garantindo integridade de dados em todas as entradas.
* **Funcionalidades:** CRUD de tarefas por usuário autenticado (criar, listar, atualizar e remover).
* **Stack:** Node.js, TypeScript, Express, Prisma ORM e MySQL.
* **Próximos passos:** refresh token, testes automatizados com Jest, documentação via Swagger, paginação e roles de usuário.

#### ⚽ [Bet Tracker API](https://github.com/luiz-fardim/bet-tracker)
Projeto que nasceu de um problema real: ajudar meu pai a organizar as apostas esportivas dele e entender se estava saindo no lucro ou no prejuízo. Hoje já é uma API completa, em produção, e caminhando para virar um produto de verdade.
* **Arquitetura:** Modular (NestJS), com separação clara entre `auth`, `bets`, `users` e `guards`.
* **Autenticação & Autorização:** Login via JWT, rotas protegidas com Guards e controle de acesso por Roles (RBAC — admin/user).
* **Regras de negócio:** Cálculo automático de lucro/prejuízo por aposta (`(odd × valor) - valor` em caso de vitória) e resumo do lucro total acumulado por usuário.
* **Funcionalidades:** CRUD de apostas com paginação e filtro por status (pending/won/lost), cada usuário só acessa as próprias apostas.
* **Qualidade:** Validação global de dados com class-validator e documentação interativa via Swagger.
* **Stack:** NestJS, TypeScript, TypeORM, PostgreSQL, Docker & Docker Compose.
* **Deploy:** [API em produção](https://bet-tracker-api-ynry.onrender.com/) • [Documentação Swagger](https://bet-tracker-api-ynry.onrender.com/api)
* **Próximos passos:** integração com API-Football para atualização automática de resultados, filas com BullMQ + Redis, bot no Telegram para notificações e um dashboard em React/Next.js com gráficos de desempenho.

---

### 🏗️ O que estou aprendendo agora?

* 🧪 **Testes Automatizados** — Garantindo a qualidade e estabilidade com **Jest** e **Supertest**.
* 🚀 **Cloud & Deploy** — Tirando os projetos do "localhost" e levando para o mundo real via **Railway/Render**.

---

### 📫 Vamos conversar?

Se você curte falar sobre arquitetura backend, desafios de código ou tem uma vaga de Júnior no time, bora trocar uma ideia:

- **LinkedIn:** [linkedin.com/in/luiz-fardim](https://linkedin.com/in/luiz-fardim)
- **E-mail:** luizfernandofardim@gmail.com

<div align="center">
  <sub>Construindo soluções, um commit de cada vez 🚀</sub>
</div>
