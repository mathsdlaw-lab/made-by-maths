# Made by Maths

**Racismo Ambiental — Território em Debate** é uma página interativa, em arquivo único, sobre racismo ambiental, território e justiça climática no Brasil.

- **Site publicado:** https://mathsdlaw-lab.github.io/made-by-maths/
- **Idioma:** português (pt-BR)
- **Formato:** HTML, CSS e JavaScript em um único arquivo (`index.html`), sem dependências externas

## O que há no projeto

- **Quiz interativo:** 35 situações organizadas em três níveis de dificuldade (Fácil, Médio e Difícil), com rodadas de 3 cartas sorteadas, feedback imediato e placar da sessão.
- **Mapa de casos reais:** painel cartográfico com casos emblemáticos de desigualdade ambiental no Brasil, incluindo descrição, impactos e referências de imagem quando disponíveis.
- **Fontes e contexto:** seção com referências institucionais e bases de dados utilizadas como apoio ao conteúdo.
- **Personalização visual:** múltiplas paletas de cores (incluindo tema noturno), ajustes de aparência e efeitos visuais de fundo.
- **Experiência acessível:** estrutura semântica, link para pular ao conteúdo, estados de foco visíveis e suporte a navegação por teclado em componentes interativos.

## Como executar localmente

Por ser um site estático, não é necessário processo de build.

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` diretamente no navegador **ou** sirva a pasta com um servidor HTTP local.

Exemplo com Python:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Estrutura do repositório

```text
.
├── index.html      # Aplicação/página completa (conteúdo, estilos e scripts)
├── README.md       # Documentação do projeto
├── .gitattributes  # Configurações de atributos do Git
└── .nojekyll       # Publicação estática no GitHub Pages sem processamento Jekyll
```

## Conteúdo e metodologia

As perguntas do quiz são situações educativas elaboradas para estimular análise crítica; não descrevem literalmente um caso específico. O mapa e as fontes reúnem materiais de referência e exemplos reais para contextualizar o debate sobre racismo ambiental no Brasil.

## Publicação

O projeto está preparado para hospedagem como site estático (por exemplo, GitHub Pages). O arquivo `.nojekyll` indica que não há necessidade de processamento pelo Jekyll.
