# Sistema de Baralho Front - End

Projeto desenvolvido para exame de Front-end usando Next.js.

## Tecnologias Usadas

- Next.js 14
- React
- TypeScript
- CSS Modules

## Instruções

1. Instalar dependências:
```
npm install
```

2. Criar arquivo .env.local na raiz do projeto:
```
AUTH_PASSWORD=sua_senha
```

3. Executar o projeto:
```
npm run dev
```

4. Acessar http://localhost:3000

## Deploy na Vercel

Link do deploy: ( ainda nao feito )

Configurar variável de ambiente AUTH_PASSWORD na Vercel.



## Estrutura do Projeto

```
├── app/
│   ├── api/
│   │   └── auth/
│   │       └── route.ts          # Rota de autenticação
│   ├── login/
│   │   ├── page.tsx              # Página de login
│   │   └── login.module.css      # Estilos do login
│   ├── globals.css               # Estilos globais
│   ├── layout.tsx                # Layout raiz
│   ├── page.tsx                  # Página principal (baralho)
│   └── home.module.css           # Estilos da home
├── types/
│   └── card.ts                   # Tipos TypeScript
├── .gitignore
├── next.config.js
├── package.json
├── README.md
└── tsconfig.json
```

# Exame-Front--End
