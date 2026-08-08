# Portfólio — Engenharia de Computação

Portfólio pessoal estático feito apenas com HTML, CSS e JavaScript.

## Como usar no GitHub Pages

1. Crie um repositório no GitHub.
2. Coloque o arquivo `index.html` na raiz do repositório.
3. Abra:
   `Settings > Pages`
4. Em "Build and deployment", selecione:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
5. Salve e aguarde a publicação.

## Personalização

Abra `index.html` e procure:

```js
const CONFIG = {
  nome: "Seu Nome",
  github: "SEU_USUARIO",
  linkedin: "SEU_USUARIO",
  email: "seuemail@email.com"
};
```

Troque pelos seus dados.

### Foto

O código tenta usar automaticamente sua foto do GitHub:

```text
https://github.com/SEU_USUARIO.png
```

Portanto, basta colocar seu usuário correto em `CONFIG.github`.

### Links dos projetos

Os três cards da seção "Projetos selecionados" estão preparados para receber links.

Procure:

```html
<a class="project-link" href="#" onclick="return false;">
```

e troque `#` pelo endereço do seu projeto ou repositório.

## Estrutura

```text
portfolio/
└── index.html
```

O projeto foi feito em um único arquivo para facilitar a publicação no GitHub Pages.
