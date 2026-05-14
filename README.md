# Portfolio | Figma Vibe

Esse é o repositório do meu portfolio pessoal. Ele é um arquivo HTML que simula a interface do Figma — porque eu passo o dia no Figma mesmo, então por que meu portfolio seria diferente?

## O que é isso, exatamente?

Um portfolio interativo com canvas, zoom, pan, sidebar de camadas, painel de inspetor, galeria arrastável, lightbox, modo apresentação fullscreen e troca de idioma. Tudo em **um único arquivo HTML**, sem frameworks, sem build, sem dependências.

A ideia não foi deixar a IA resolver. Foi enxergar uma oportunidade onde ninguém olhou ainda, e usar a tecnologia pra executar o que eu já sabia pensar.

## Por que open source?

Conhecimento bom é conhecimento compartilhado.

Se você quiser construir o seu próprio portfolio assim, pode usar esse código como base e se divertir.

## Como rodar

Não tem build. Não tem npm install. Abre o `index.html` no navegador e é isso.

```bash
git clone https://github.com/seu-usuario/portfolio-neitam-2026
cd portfolio-neitam-2026
# abre index.html no navegador
```

## Como personalizar

1. Edite o objeto `P[]` no JavaScript pra colocar seus projetos
2. Atualize o objeto `UI` com seus textos em PT e EN
3. Substitua as URLs de imagem pelas suas (recomendo Cloudinary)
4. Troque o logo SVG na `.tb-logo`
5. Sobe no GitHub Pages

## Deploy (GitHub Pages)

1. Cria um repositório público
2. Coloca o `index.html` na raiz
3. Cria a pasta `images/` com as capas dos projetos
4. Ativa em **Settings → Pages → Branch: main**
5. Em ~1 minuto fica no ar

## Stack

| O que | Como |
|---|---|
| Linguagem | HTML + CSS + JS vanilla |
| Fonte | Onest (Google Fonts) |
| Imagens | Cloudinary CDN |
| Deploy | GitHub Pages |
| Gerado com | Claude (Anthropic) |

## Licença

O **código** está sob [licença MIT](LICENSE) — pode usar, modificar e distribuir, desde que mantenha os créditos.

Os **textos, imagens, identidade visual e conceito criativo** são de autoria de Neitam Albrecht e **não estão incluídos na licença**. Esses elementos são protegidos por direitos autorais e não podem ser reproduzidos ou adaptados sem autorização.

## Contato

- LinkedIn: [nathanalbrecht](https://www.linkedin.com/in/nathanalbrecht/)
- Instagram: [@itsneitam](https://www.instagram.com/itsneitam)
- Behance: [cartoonate](https://www.behance.net/cartoonate)

---

Feito com 🤙 e Claude.
