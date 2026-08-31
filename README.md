# srisainath.in

Static personal site. Zero build step — plain HTML/CSS/JS in one file.

## Deploy (Cloudflare Pages, free)

1. Push this folder to a GitHub repo.
2. Cloudflare dash → Workers & Pages → Create → Pages → connect the repo.
3. Build command: *(none)*. Output directory: `/`.
4. Custom domains → add `srisainath.in` and `www.srisainath.in`.

## Project subdomains

Each side project gets its own repo + Pages project, then a custom domain
like `autosre.srisainath.in`. Free, unlimited.

## Local preview

    python3 -m http.server 8080
