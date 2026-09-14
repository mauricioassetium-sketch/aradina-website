# Aradina Website

Sitio corporativo de Aradina Technologies LLC (aradina.net).

10 paginas estaticas (tema claro estilo Replit), CSS/JS inline, i18n ES/EN/AR.

## Deploy (GitHub Pages)

1. Repo Settings -> Pages -> Source: GitHub Actions
2. El workflow `.github/workflows/deploy.yml` publica en cada push a main.
3. Dominio custom: `aradina.net` (archivo CNAME en raiz).
4. DNS en GoDaddy: 4x A @ -> 185.199.108-111.153, CNAME www -> mauricioassetium-sketch.github.io
