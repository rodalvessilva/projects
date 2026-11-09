# WeePulse Design System

Catálogo gerado pela skill `extract-ds` a partir de https://weepulse.com.br/ em 2026-11-09.

- `design-system.html`: entrada do catálogo, com as abas **Overview** e **Components**.
- `assets/overview/`: cópia funcional do site (HTML, CSS, scripts e assets), com a copy editorial trocada por Lorem Ipsum.
- `assets/overview/components.html`: biblioteca de fundamentos e componentes extraída do Overview.

## Como abrir

O site usa ES modules, então precisa de um servidor estático:

```bash
cd weepulse-design-system && python3 -m http.server 8080
```

Depois acesse http://localhost:8080/design-system.html.

## Observação

Os 97 frames da animação do personagem do hero (46 MB) não estão neste repositório. Sem eles, o hero exibe o poster estático do personagem; o restante das animações funciona normalmente.
