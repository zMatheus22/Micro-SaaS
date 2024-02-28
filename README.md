# Micro-SaaS

## Tecnologias

Neste projeto foram escolhida as seguintes tecnologias.

Bun -> como run time.
NextJS -> como framework web
Tailwind -> como estilizador do site.

```bash
bun create next-app
# Configuração utilizado para o projeto.
#✔ What is your project named? … my-app
#✔ Would you like to use TypeScript with this project? Yes
#✔ Would you like to use ESLint with this project? Yes
#✔ Would you like to use `src/` directory with this project? Yes
#✔ Would you like to use experimental `app/` directory with this project? Yes
#✔ What import alias would you like configured? No
```

Shadcn UI -> como um auxiliar de estilo na criação dos componentes.

```bash
# No momento índico utilizar o `npx` pois o `bunx` não esta funcionando corretamente.
npx shadcn-ui@latest init
# or
npx shadcn-ui@latest init
# or
pnpm dlx shadcn-ui@latest init
# or
bunx --bun shadcn-ui@latest init
```

Adicionar os componentes ao projeto.

```bash
# No momento índico utilizar o `npx` pois o `bunx` não esta funcionando corretamente.
npx shadcn-ui@latest add
# or
npx shadcn-ui@latest add
# or
pnpm dlx shadcn-ui@latest add
# or
bunx --bun shadcn-ui@latest add
```

React-hook-form -> para auxiliar nos formulários do projeto.

```bash
bun add react-hook-form
```

Next-Auth -> para ser um autenticador do sistema.

```bash
bun add next-auth@beta
```

## Getting Started

Primeiro, rodar o server como desenvolvedor:

```bash
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
