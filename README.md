# LVM — Interativos

Repositório estático para publicar visualizações matemáticas do Laboratório Virtual de Matemática (LVM).

## Estrutura

```text
lvm-interativos/
├── index.html
├── config.js
├── README.md
├── MANUAL_GITHUB_LVM.md
└── trionda/
    ├── index.html
    └── trionda-data.js
```

- `index.html`: página inicial dos interativos.
- `config.js`: local simples para colar links externos, como o Google Colab.
- `trionda/index.html`: visualizador Three.js da Trionda.
- `trionda/trionda-data.js`: geometria exportada do código Python.
- `MANUAL_GITHUB_LVM.md`: passo a passo para publicar no GitHub Pages e ligar ao LVM.

## Teste local

No terminal, dentro da pasta do repositório:

```bash
python3 -m http.server 8000
```

Depois abra `http://localhost:8000/`.

A visualização Three.js usa uma versão fixa da biblioteca carregada pelo CDN jsDelivr, portanto precisa de internet para abrir.
