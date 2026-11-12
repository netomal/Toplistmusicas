# Toplistmusicas

Página web que reúne **12 músicas muito bem avaliadas em quatro categorias** (Rock, MPB, Pop, Hip hop e eletrônica), com resumo, nota e link para ouvir. Um formulário permite sugerir novas músicas, que entram na lista e ficam salvas no navegador.

Projeto de Desenvolvimento Front-end para Web, com HTML5 semântico, acessibilidade, formulários e JavaScript.

## Tecnologias

- HTML5
- CSS3
- JavaScript (sem bibliotecas)
- Git e GitHub

## O que o projeto faz

- **HTML semântico:** `header`, `nav`, `main`, `section`, `article` e `footer`. Cada seção é ligada ao seu título por `aria-labelledby`.
- **Acessibilidade:** link "Pular para o conteúdo", foco visível, `label` em todos os campos, `fieldset` e `legend` no formulário, mensagens com `role="status"` e respeito a `prefers-reduced-motion`.
- **CSS:** tema roxo escuro com variáveis CSS, layout geral com Grid, cards responsivos com `auto-fit`/`minmax`, menu fixo com Flexbox e ajuste para telas estreitas.
- **JavaScript:** as músicas ficam em um array de objetos. A página classifica cada uma pela nota, destaca a melhor de cada categoria e calcula o painel de resumo com `map`, `filter` e `reduce`.
- **Formulário:** valida nome, artista, categoria, nota (0 a 10) e link. As sugestões ficam no `localStorage`.
- **Links externos:** abrem em nova aba com `target="_blank"` e `rel="noopener noreferrer"`.

## Estrutura

```
css/
└── style.css
js/
└── main.js
index.html
README.md
```

## Como executar

```
git clone https://github.com/SEU-USUARIO/Toplistmusicas.git
```

Abra o `index.html` no navegador ou use o **Live Server** no VS Code.

## Como personalizar

Edite o array `musicas` em `js/main.js` para trocar músicas, notas e resumos. As notas são opiniões, então coloque as suas.

## Autor

**José Ferreira da Silva Neto**
