# Programa de Orientação Acadêmica — Biomedicina UFPR

## Arquivos
- `index.html`: estrutura mínima da página.
- `styles.css`: aparência responsiva.
- `app.js`: renderização de conteúdo e interações.
- `dados.json`: conteúdo editável da página.

## Publicação no GitHub Pages
1. Envie os quatro arquivos para a raiz do repositório (ou para a pasta configurada no GitHub Pages).
2. Em Settings → Pages, escolha Deploy from a branch, branch `main`, pasta `/ (root)`.
3. Aguarde a publicação e teste a URL disponibilizada pelo GitHub.
4. No WordPress, insira a URL como **Link personalizado** no menu `MenuHorizontal`, como subitem de `A Coordenação`.

## Incorporação no WordPress
Em um bloco HTML personalizado, pode-se usar:

```html
<iframe title="Programa de Orientação Acadêmica — Biomedicina UFPR" src="https://SEU-USUARIO.github.io/SEU-REPOSITORIO/" style="width:100%;min-height:2400px;border:0" loading="lazy"></iframe>
```

O iframe tem altura fixa; o ajuste fino dependerá do conteúdo e do tema WordPress. Preferir link direto para evitar rolagem interna e problemas de altura.

## Manutenção
Edite `dados.json` mantendo aspas duplas, vírgulas e a estrutura JSON válida. Não adicione nomes de tutores nem links de regulamentos sem confirmação. O PDF fornecido possui número de instrução normativa em branco e não comprova, por si só, vigência atual.

## Teste local
Execute `python -m http.server 8000` na pasta e acesse `http://localhost:8000/`. Abrir `index.html` via `file://` pode bloquear o carregamento do JSON.
