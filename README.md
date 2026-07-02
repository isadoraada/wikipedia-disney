# Wikipedia Clone — Mickey Mouse

Projeto desenvolvido como parte dos desafios práticos da [DIO (Digital Innovation One)](https://www.dio.me/), com o objetivo de replicar o layout da Wikipedia utilizando apenas **HTML** e **CSS**.

## 📄 Sobre o projeto

A página apresenta um artigo sobre **Mickey Mouse** seguindo a estrutura visual e semântica da Wikipedia, com sidebar de navegação, conteúdo principal dividido em seções e painel de âncoras lateral.

## 🗂️ Estrutura de arquivos

```
wikipedia/
├── index.html
└── assets/
    ├── css/
    │   └── style.css
    └── images/
        ├── icon.png
        ├── logo.png
        └── mickey.png
```

## 🧱 Seções da página

- **Header** — logo do Mickey Mouse
- **Nav** — barra de navegação com links para cada seção do artigo
- **Sidebar** — links para personagens relacionados do universo Disney
- **Main** — conteúdo principal com as seções:
  - Introdução
  - História
  - Voz e Dublagem (com tabela de dubladores)
  - Domínio Público
  - Aparições Notáveis
  - Curiosidades
  - Personagens Relacionados
- **Anchors** — índice lateral com âncoras para navegação interna (sticky)
- **Footer** — créditos, fonte e licença

## ♿ Acessibilidade

- `lang="pt-br"` definido na tag `<html>`
- `alt` descritivo em todas as imagens
- Elementos semânticos: `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`, `<figure>`, `<table>`
- `aria-label` nas regiões de navegação e complementares
- `focus-visible` estilizado para navegação por teclado
- `scope` nos cabeçalhos de tabela

## 🚀 Como executar

Basta abrir o arquivo `index.html` diretamente no navegador, ou usar a extensão **Live Server** do VS Code:

1. Clique com o botão direito em `index.html`
2. Selecione **Open with Live Server**

Nenhuma dependência ou instalação necessária.

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura e semântica |
| CSS3 | Estilização e layout (CSS Grid) |

## 📚 Referências

- [Wikipedia — Mickey Mouse](https://pt.wikipedia.org/wiki/Mickey_Mouse)
- [DIO — Digital Innovation One](https://www.dio.me/)
