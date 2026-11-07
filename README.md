# Cartão profissional

Meu cartão de visita digital: uma página única, responsiva e acessível, com os links para meus perfis e um botão que salva meu contato direto na agenda do celular.

**Ver online:** https://ezimbrao.github.io/card-perfil/

<!-- TODO: tire um print do cartão já com seus dados reais, salve como preview.png
     na raiz do projeto e confira se a imagem aparece abaixo. -->
![Prévia do cartão profissional no desktop](preview.png)

## O que o projeto tem

- Layout responsivo, pensado primeiro para o celular (mobile-first)
- Tema claro e escuro automático, de acordo com a preferência do sistema
- Botão "Salvar contato" que baixa um arquivo `.vcf` (vCard)
- Links para GitHub, LinkedIn, e-mail e WhatsApp
- Metadados para o link aparecer com título e descrição ao ser compartilhado (Open Graph)

## Tecnologias

- HTML5 semântico
- CSS3 puro: variáveis, Flexbox, Grid e media queries
- Fontes: Bricolage Grotesque e Public Sans (Google Fonts)
- Sem JavaScript e sem dependências

## Acessibilidade

- Estrutura com `main`, `header`, `nav` e `footer`
- Foco visível ao navegar pelo teclado (`:focus-visible`)
- Contraste de cores conferido nos dois temas
- Animações desativadas para quem pede menos movimento (`prefers-reduced-motion`)
- Áreas de toque de pelo menos 48 px nos links e no botão

## Estrutura de arquivos

```
.
├── index.html     # conteúdo e metadados da página
├── style.css      # estilos (tokens, componentes e telas maiores)
├── contato.vcf    # contato baixado pelo botão "Salvar contato"
├── preview.png    # print usado neste README
└── README.md
```

## Como rodar no seu computador

1. Baixe ou clone o repositório.
2. Abra a pasta no VS Code e use a extensão **Live Server** ("Go Live"), ou abra o `index.html` direto no navegador.

## Como personalizar

Procure por `TODO` em `index.html` (Ctrl+F) e ajuste:

- cargo, bio e tecnologias
- links de LinkedIn, e-mail e WhatsApp
- os mesmos dados no `contato.vcf`
- foto de perfil, se quiser (instruções no comentário do HTML)
- `og:url` e `og:image`, depois que o site estiver publicado

## Como publicar

O projeto é estático, então qualquer hospedagem de arquivos serve. No GitHub Pages:
**Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.**

## O que aprendi

<!-- TODO: escreva com suas palavras 3 ou 4 aprendizados reais. Por exemplo:
     - o que mudou no seu jeito de pensar tamanhos com box-sizing
     - quando você escolheu Flexbox e quando escolheu Grid
     - como testou o layout em telas diferentes
     - o que ainda quer melhorar -->

## Próximos passos

- [ ] Ícones nos links (SVG inline)
- [ ] Botão para alternar o tema manualmente
- [ ] Botão para copiar o e-mail
- [ ] Seção de projetos

## Autor

**Enzo Zimbrão** · São Paulo, SP · [GitHub](https://github.com/ezimbrao)
