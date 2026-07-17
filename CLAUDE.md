# CLAUDE.md — videos-edit-cria

A skill **Forja Reel** (Claude Code) — meta-skill que gera seu editor de reels.
Ver [[videos-edit-curso]] pro curso completo em 4 trilhas (repo irmão, separado
deste em 2026-07-17 — antes eram um único repo `videos-edit`).

## Git / autor

Este repo vive na conta GitHub **`inematds`**.

- `git config` (local) = `inematds <inematds@gmail.com>`.
- Remote: `git@github.com:inematds/videos-edit-cria.git`.
- Renomeado de `inematds/videos-edit` (era um repo só, misturando skill + curso)
  — a URL antiga `inematds/videos-edit` redireciona automaticamente pro nome
  novo no GitHub, mas o remote local já foi atualizado.

## Estrutura

- `download/forja-reel.skill` — arquivo pronto pra instalar no Claude Code.
- `doc/` — **gitignored**, materiais de referência não publicáveis (originais
  em espanhol, arquivos com autoria) — nunca commitar.
- `guia/index.html` — landing + guia de uso (`projetos-landing-guia`), publicado
  em `https://inematds.github.io/videos-edit-cria/guia/`.
- `capa/capa.png` — capa oficial do catálogo (convenção `<url>/capa/capa.png`).

## Deploy = sempre via git

Publicar = `commit + push` no `origin`. GitHub Pages via Actions
(`build_type=workflow`, não legacy). Deploy automático — não cutucar
dashboard/status.
