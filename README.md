# Benefiz Command Center — Painel TV

MVP de um painel executivo para exibição contínua em TV/monitor de sala de comando.

> **Importante:** todos os números deste projeto são fictícios e servem exclusivamente para demonstração, prototipação e uso didático.

## Estrutura

- `html/` — versão didática em HTML + CSS + JavaScript puro. Não exige instalação.
- `react/` — versão evolutiva em React + TypeScript + Recharts.

## Testar a versão HTML

1. Baixe ou clone o repositório.
2. Entre na pasta `html`.
3. Abra `index.html` no navegador.
4. Pressione `F11` para simular a exibição em uma TV.

O painel possui 6 telas e avança automaticamente a cada 15 segundos. Os botões no rodapé permitem pausar e navegar manualmente.

## Executar a versão React

Requer Node.js instalado.

```bash
cd react
npm install
npm run dev
```

Para gerar uma versão de produção:

```bash
npm run build
```

## Telas do MVP

1. Visão Executiva
2. Comercial
3. Financeiro
4. Beneficiários
5. Operação & Atendimento
6. Saúde & Rede

## Objetivo didático

A versão HTML separa propositalmente responsabilidades em `index.html`, `css/style.css`, `js/dados.js` e `js/app.js`. Isso permite demonstrar aos alunos a relação entre estrutura, apresentação, dados e comportamento antes da introdução de frameworks.

## Próximas evoluções

- adequação fina à identidade visual da empresa;
- conexão com fontes de dados reais;
- metas e alertas parametrizáveis;
- atualização automática por API;
- modo kiosk para Smart TV/mini PC;
- painel administrativo;
- histórico e drill-down;
- publicação web controlada.
