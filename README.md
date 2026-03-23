# Turiya Terapia Holistica

Estrutura pronta para publicar o site institucional da Turiya Terapia Holistica no GitHub Pages.

## Arquivos

- `index.html`: site institucional da Turiya
- `CNAME`: domínio customizado do Pages
- `.nojekyll`: evita processamento Jekyll

## Publicação recomendada

1. Crie um repositório público no GitHub, por exemplo `turiya-terapia-holistica`.
2. Envie estes arquivos para a branch `main`.
3. No GitHub, abra `Settings > Pages`.
4. Em `Build and deployment`, escolha:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` e pasta `/ (root)`
5. Aguarde o primeiro deploy.
6. Confirme que o arquivo `CNAME` permaneceu no repositório.

## Domínio

Este projeto está configurado para:

- `www.turiyaterapiaholistica.com.br`

Configuração DNS recomendada:

- `www` como `CNAME` para `<seu-usuario>.github.io`
- domínio raiz `turiyaterapiaholistica.com.br` redirecionando para `www.turiyaterapiaholistica.com.br`

Se preferir trocar o domínio, edite o arquivo `CNAME`.
