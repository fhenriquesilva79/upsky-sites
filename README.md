# UPSky - Site (modular)

Projeto modular do site institucional UPSky Digital Identity.

## Estrutura
- `index.html` - página principal
- `css/styles.css` - estilos
- `js/app.js` - scripts
- `assets/` - imagens e svg

## Como testar localmente
1. Abra o `index.html` no navegador.
2. Ou rode um servidor local (recomendado):
   - Python 3: `python -m http.server 8000`
   - Acesse `http://localhost:8000`

## Deploy na Vercel
1. Crie repo no GitHub e faça push.
2. Importe o repo no Vercel (New Project → Import).
3. Vercel faz deploy automático em cada push.

## Observações
- Substitua contatos e número do WhatsApp pelas informações reais.
- Para capturar leads em produção, configure Netlify Forms, Formspree, ou endpoint serverless.
- Ajuste imagens em `assets/` com versões otimizadas (webp/png/svg).



