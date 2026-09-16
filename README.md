# Bússola de Estilo — Quiz Decorafit

Quiz de 10 perguntas para descobrir o estilo de decoração de interiores (Contemporâneo, Japandi, Minimalista Aconchegante, Escandinavo, Boho Chic, Industrial, Orgânico Moderno, Mid-century Modern, Clássico Contemporâneo). Pensado como link de bio/story do Instagram da Decorafit.

## Estrutura

- `index.html` — página única (HTML + CSS + JS), sem dependências além das fontes do Google Fonts.
- `img/` — fotos de resultado de cada estilo.

## Rodar localmente

Basta abrir `index.html` no navegador, ou servir a pasta com qualquer servidor estático:

```
python -m http.server 8000
```

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e suba esta pasta (`git push`).
2. Em **Settings → Pages**, selecione a branch `main` e a pasta raiz (`/`).
3. O quiz fica disponível em `https://<seu-usuario>.github.io/<repo>/`.

Esse link pode ser usado direto no Instagram.
