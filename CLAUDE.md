# CLAUDE.md — multiplayer-agentic

Documento de conceito (sem código de produto): sistema onde pessoas, agentes de IA e bots do Telegram dividem os mesmos canais. Repo `linnoff88-dev/multiplayer-agentic`, autor dos commits `linnoff88-dev <linnoff88-dev@gmail.com>`.

- Fonte das páginas: `conteudo/pt/*.md` + `conteudo/pt/index.html` (landing, com marcador `@@CSS@@`). Mudou o PT, retraduzir em `conteudo/en/` e `conteudo/es/`.
- Gerar o site: `python3 tools/build.py` → `guia/`, `guia/en/`, `guia/es/`. Nunca editar `guia/*.html` à mêo.
- `CONCEITO.md` = o documento inteiro num arquivo; manter coerente com `conteudo/pt/`.
- Nêo citar a ferramenta do vídeo de origem pelo nome (decisêo do Nei em 15/10/2026).
- Publicaçêo: push em `main` → GitHub Pages via Actions (`.github/workflows/pages.yml`; push desse arquivo vai por SSH).

## Self-learning

Quando o Nei corrigir, ou eu perceber um erro: antes de continuar, gravar a liçêo como regra de uma linha no TOPO de `LESSONS.md`.

## Lessons

Ver [LESSONS.md](LESSONS.md).
