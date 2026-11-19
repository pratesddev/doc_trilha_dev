# 🚀 Trilha Dev – Roteiro de Estudos

**Objetivo:** Do zero até o deploy de uma aplicação full-stack com Next.js.

> ✅ Concluído · 🟡 Em andamento · ⏳ Planejado

---

## 📍 Visão Geral da Trilha

| # | Tema | Status | Estimativa |
| --- | ------ | -------- | ------------ |
| 01 | Git e GitHub | 🟡 Em andamento | 2–3 semanas |
| 02 | HTML e CSS | 🟡 Em andamento | 3–5 semanas |
| 03 | JavaScript | ⏳ Planejado | 6–10 semanas |
| 04 | Node.js + Express | ⏳ Planejado | 4–6 semanas |
| 05 | React | ⏳ Planejado | 6–8 semanas |
| 06 | Next.js | ⏳ Planejado | 6–10 semanas |

**Ordem recomendada:**  
`Git/GitHub → HTML/CSS → JavaScript → Node.js → React → Next.js`

---

## 01. Git e GitHub

**Objetivo:** Dominar versionamento e colaboração.

### Conteúdo essencial

- Conceitos: repositório, commit, branch, merge, pull request
- Comandos do dia a dia: `add`, `commit`, `status`, `log`, `diff`, `branch`, `checkout/switch`, `merge`, `rebase` (básico), `stash`
- GitHub: criar repositório, README, `.gitignore`, issues, pull requests
- Introdução a GitHub Actions
- Fluxo de trabalho: feature branch + PR
- Boas práticas: mensagens de commit semânticas e Conventional Commits

### Projetos práticos

- Repositório de anotações pessoais
- Pequeno projeto com histórico limpo e PRs simulados

---

## 02. HTML e CSS

**Objetivo:** Construir interfaces semânticas e responsivas.

Conteúdo essencial:

- HTML semântico (`header`, `nav`, `main`, `section`, `article`, `footer`, `form`...)
- Acessibilidade básica (`label`, `alt`, ARIA quando necessário)
- CSS moderno: **Flexbox** + **Grid** (prioridade máxima)
- Responsividade (mobile-first + media queries)
- Variáveis CSS (custom properties)
- Unidades modernas (`rem`, `clamp`, etc.)
- Pseudo-classes e pseudo-elementos
- Introdução a animações e transitions

Projetos práticos (ordem de complexidade):

1. Página de perfil / portfólio simples
2. Landing page responsiva
3. Formulário estilizado + tabela de dados
4. Clone de uma página simples (card de produto, dashboard básico)

---

## 03. JavaScript

**Objetivo:** Dominar a linguagem antes de frameworks.

Conteúdo essencial (ordem recomendada):

1. Fundamentos: variáveis, tipos, operadores, condicionais, loops
2. Funções (declaração, expressão, arrow), escopo e hoisting
3. Arrays e objetos (métodos importantes: `map`, `filter`, `reduce`, `find`...)
4. DOM: seleção, manipulação e eventos
5. Assincronismo: callbacks → Promises → `async/await`
6. Fetch API + JSON
7. Módulos (`import` / `export`)
8. ES6+: destructuring, spread/rest, template literals, optional chaining, nullish coalescing
9. `localStorage` / `sessionStorage`
10. Tratamento de erros (`try/catch`)

Projetos práticos:

- To-do list (CRUD no `localStorage`)
- Consumo de API pública (Weather, GitHub Users, PokéAPI...)
- Calculadora ou conversor
- Jogo simples (memory game ou quiz)

---

## 04. Node.js + Express

**Objetivo:** Entender o lado servidor e criar APIs.

Conteúdo essencial:

- O que é Node e visão geral do event loop
- NPM e `package.json`
- Módulos nativos e de terceiros
- Express: rotas, middlewares, tratamento de erros
- REST API (CRUD completo)
- Persistência simples (começar com JSON ou SQLite → depois MongoDB/PostgreSQL)
- Autenticação básica com JWT
- Variáveis de ambiente (`.env`)
- Estrutura de pastas de um projeto Node

Projetos práticos:

- API de tarefas (To-do)
- API de blog simples (posts + comentários)
- Sistema de autenticação (register / login)

---

## 05. React

**Objetivo:** Componentização e gerenciamento de estado no front-end.

Conteúdo essencial:

- JSX e componentes funcionais
- Props e State (`useState`)
- `useEffect` e ciclo de vida
- Listas e keys
- Formulários controlados
- Context API (ou Zustand / Redux Toolkit mais à frente)
- React Router
- Hooks customizados
- Organização de pastas e boas práticas

Projetos práticos:

- To-do list em React
- Dashboard consumindo a API criada no Node
- Clone de interface (parte do X/Twitter, YouTube ou Netflix)

---

## 06. Next.js

**Objetivo:** Aplicação full-stack moderna.

Conteúdo essencial:

- App Router (padrão atual)
- Server Components vs Client Components
- Roteamento, layouts, loading e error
- Data fetching e Server Actions
- Route Handlers (API Routes)
- Autenticação (NextAuth ou Clerk)
- Deploy na Vercel
- Otimizações (`next/image`, `next/font`, Metadata)

Projeto final sugerido:

Aplicação completa (ex: blog com autenticação + CRUD de posts, ou sistema de gestão simples) usando Next.js + API (própria do Next ou a do Node).

---

## 🏅 Certificações Recomendadas (Trilha Dev)

| Certificação | Foco | Nível | Observação |
| -------------- | ------ | ------- | ------------ |
| **freeCodeCamp** (Responsive Web Design + JavaScript + Front End Libraries + Back End) | HTML/CSS/JS/React/Node | Iniciante → Intermediário | Gratuita e muito boa para portfólio |
| **Meta Front-End Developer Professional Certificate** (Coursera) | HTML, CSS, JS, React | Intermediário | Boa qualidade e reconhecimento |
| **Meta Back-End Developer Professional Certificate** | Node, APIs, bancos | Intermediário | Complementa bem a trilha |
| **AWS Certified Cloud Practitioner** | Cloud fundamental | Iniciante | Excelente porta de entrada para o ecossistema AWS |
| **Microsoft Azure Fundamentals (AZ-900)** | Cloud fundamental | Iniciante | Alternativa à AWS |
| **AWS Certified Developer – Associate** | Desenvolvimento na AWS | Intermediário | Recomendada depois de ter experiência com deploy |

### Prioridade sugerida

1. freeCodeCamp (gerar certificados + projetos)
2. Meta Front-End (se quiser algo mais formal)
3. AWS Cloud Practitioner
4. AWS Developer Associate (mais à frente)

---

## 📂 Sugestão de organização no repositório

Use o padrão de prefixos já definido:

| Prefixo | Conteúdo |
| --------- | ---------- |
| `git_` | Git e GitHub |
| `fe_` | Front-end (HTML, CSS, JS, React) |
| `be_` | Back-end (Node.js) |
| `fs_` | Full-stack (Next.js e projetos integrados) |

**Exemplos de pastas:**

- `git_comandos_essenciais`
- `fe_html_css_portfolio`
- `fe_javascript_todo`
- `be_nodejs_api_tarefas`
- `fs_react_dashboard`
- `fs_nextjs_blog`

Cada projeto deve conter um `README.md` com:

- O que o projeto faz
- Tecnologias usadas
- Como rodar localmente
- O que você aprendeu
- Decisões técnicas importantes

---

## 💡 Dicas finais

- Priorize **projetos** em vez de apenas consumir conteúdo.
- Documente tudo o que quebrar e o que funcionar (esse é o espírito do repositório).
- Depois de JavaScript + Node, já comece a integrar front e back.
- O projeto final com Next.js deve ser o seu cartão de visitas.

---

⭐ Continue registrando a jornada. O progresso acumulado é o que realmente conta.
