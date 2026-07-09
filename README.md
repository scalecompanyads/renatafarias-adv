# Landing Page — Dra. Renata Farias

Landing page de captação via WhatsApp para advocacia especializada em regularização de imóveis (usucapião extrajudicial) — Vila Velha/ES.

Página estática, arquivo único (`index.html`, CSS/JS embutidos), sem build. Pode ser hospedada em qualquer serviço estático (Vercel, Netlify, Hostinger, GitHub Pages).

## Antes de publicar — TROCAR

1. **Número do WhatsApp** — em `index.html`, na constante `WHATSAPP_NUMBER` (fim do arquivo). Trocando ali, todos os botões da página atualizam. Formato: `55` + DDD + número.
2. **OAB/ES** — no rodapé, buscar pelo comentário `<!-- TROCAR -->` e substituir `OAB/ES nº 00.000`.
3. **Open Graph** — ajustar `og:image`/`og:url` para a URL absoluta do domínio final.

## Estrutura

- `index.html` — página completa (7 seções da copy aprovada + rodapé de conformidade OAB, Provimento 205/2021)
- `assets/` — imagens otimizadas usadas pela página (~390 KB no total)
- `originais/` — arquivos-fonte da marca em alta resolução (não são referenciados pela página)
