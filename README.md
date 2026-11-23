# Biblioteca Digital UniFECAF

Primeira interface web da Biblioteca Digital UniFECAF, desenvolvida como projeto da disciplina **Design Web**. O site transforma um protótipo de baixa fidelidade em uma página moderna, responsiva e acessível, usando **apenas HTML e CSS**.

🔗 **Site:** https://vitorworldgeography.github.io/biblioteca-unifecaf/

## Objetivo

Facilitar o acesso dos estudantes a livros, materiais acadêmicos e conteúdos de apoio à aprendizagem, com uma experiência simples e intuitiva em computadores e smartphones.

## Seções do site

- **Cabeçalho:** marca e menu de navegação (menu hambúrguer no celular)
- **Destaque inicial:** título, campo de busca e números do acervo
- **Categorias:** oito áreas do conhecimento
- **Livros em destaque:** capas, categoria, título e autor
- **Serviços:** acesso ao acervo, pesquisa orientada, normas e atendimento
- **Chamada final e rodapé:** convite para acessar e informações de contato

## Tecnologias e recursos

- HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 com variáveis, Flexbox, Grid, `clamp()` e `aspect-ratio`
- Layout **mobile-first**, com ajustes para tablet (640 px) e desktop (900 px)
- Imagens vetoriais (SVG), leves e nítidas em qualquer tela
- Fontes **Poppins** (títulos) e **Inter** (textos), via Google Fonts

## Identidade visual

| Cor | Código | Uso |
|---|---|---|
| Azul-marinho | `#0A2A5E` | Cabeçalho, títulos e rodapé |
| Azul médio | `#1450B8` | Links e foco em campos |
| Laranja | `#F58220` | Botões e destaques |
| Cinza-azulado claro | `#F3F6FB` | Fundo de seções alternadas |

Todas as cores ficam centralizadas em variáveis no início do `style.css`, e os contrastes seguem o nível AA das diretrizes WCAG.

## Acessibilidade

- Idioma declarado (`pt-BR`) e títulos em ordem hierárquica
- Texto alternativo em todas as imagens
- Link "Pular para o conteúdo" e foco visível na navegação por teclado
- Campo de busca com rótulo associado
- Respeito à preferência por menos movimento (`prefers-reduced-motion`)

## Estrutura do projeto

```
biblioteca-unifecaf/
├── index.html
├── css/
│   └── style.css
└── assets/
    └── imagens/
```

## Como abrir

Baixe ou clone o repositório e abra o arquivo `index.html` no navegador.

## Autor

**Vitor Souza Ferreira** — RA 107889 — Turma CDC6NA

> Livros, autores e números exibidos no site são ilustrativos.
