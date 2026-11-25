# TechPulse | Portal de Notícias de Tecnologia

Página inicial demonstrativa, desenvolvida com HTML5 semântico e CSS3 externo. O projeto prioriza leitura clara, hierarquia editorial e adaptação a telas de celular e computador.

## Como visualizar

Abra `index.html` em um navegador conectado à internet. A fotografia principal e as fontes tipográficas são carregadas de serviços externos; o restante da página é composto por HTML e CSS, sem dependências de JavaScript.

## Especificações técnicas

- **HTML5:** estrutura do documento, metadados, títulos, navegação, conteúdo editorial e rodapé.
- **CSS3:** identidade visual, componentes, espaçamento e layout responsivo via Grid, Flexbox e media queries.
- **Fontes:** Space Grotesk nos títulos e na marca para uma presença editorial contemporânea; DM Sans no texto corrido e navegação por sua leitura confortável em telas pequenas. Fontes servidas pelo Google Fonts, com Arial como alternativa.
- **Imagem:** fotografia do planeta Terra hospedada no Unsplash, com texto alternativo descritivo para leitores de tela.
- **Tecnologias e serviços editoriais:** inteligência artificial, computação em nuvem e segurança digital estruturam as três editorias iniciais do portal.
- **Acessibilidade:** idioma `pt-BR`, navegação identificada por rótulos, textos alternativos, foco visível, hierarquia de títulos e suporte a preferência por movimento reduzido.
- **Responsividade:** layout em colunas no desktop, reorganizado em uma coluna em telas menores; navegação, cartões, tipografia e espaçamentos adaptam-se por media queries.
- **Separação de responsabilidades:** toda a apresentação fica em `styles.css`; o HTML contém conteúdo e semântica.

## Justificativas visuais

### Cores

| Cor | Hexadecimal | Uso e intenção |
|---|---|---|
| Azul vivo | `#3B5BFF` | Marca, links e ações; transmite energia e destaca elementos interativos. |
| Azul profundo | `#111A2E` | Títulos e superfícies escuras; cria contraste e sensação de confiança. |
| Ciano | `#48D9D0` | Acentos na faixa editorial e no painel de análise; sugere inovação. |
| Fundo claro | `#F7F8FC` | Fundo principal; reduz o brilho e mantém os cartões em evidência. |
| Cinza de texto | `#4D586B` | Parágrafos e informação secundária; mantém boa distinção visual. |
| Branco | `#FFFFFF` | Cartões e áreas de respiro. |

As cores usam variáveis CSS para facilitar manutenção e consistência. Os links também são identificados por texto e forma, não apenas pela cor.

### Tipografia e hierarquia

Space Grotesk dá personalidade aos títulos (`h1`, `h2`, `h3`) e reforça o caráter tecnológico. DM Sans mantém os parágrafos e rótulos legíveis. Títulos alinhados à esquerda, subtítulos mais curtos e metadados em caixa alta conduzem a leitura do destaque para as notícias.

### Espaços e Box Model

O conteúdo usa uma largura máxima de 1120 px e margens laterais automáticas. Seções recebem espaço vertical generoso para separar grupos editoriais; cartões usam padding interno e borda sutil; a grade usa gaps consistentes. O modelo `border-box` simplifica o cálculo das larguras. Nas telas menores, margens, padding e colunas diminuem ou se reorganizam para evitar rolagem horizontal.

## Sitemap Visual

```text
TechPulse
└── Página inicial (/)
    ├── Destaque editorial
    │   ├── Apresentação do portal
    │   └── Chamada para explorar notícias
    ├── Notícias
    │   ├── Inteligência artificial
    │   ├── Computação em nuvem
    │   └── Segurança digital
    ├── Análises
    │   ├── Tendências e contexto
    │   └── Impacto da tecnologia
    ├── Guias
    │   ├── Inteligência artificial
    │   ├── Computação em nuvem
    │   └── Segurança digital
    ├── Newsletter
    │   └── Acompanhar o TechPulse
    └── Sobre
        ├── Propósito editorial
        └── Links de navegação
```

### Hierarquia e taxonomia

A página inicial ocupa o primeiro nível e agrupa o conteúdo por espaços editoriais no segundo nível: Notícias, Análises, Guias, Newsletter e Sobre. Dentro de Notícias e Guias, o terceiro nível usa uma taxonomia temática compartilhada — inteligência artificial, computação em nuvem e segurança digital — para que o público encontre assuntos equivalentes em formatos diferentes. Análises organiza conteúdo por função (contexto e impacto), distinguindo-o das notícias factuais.

> Escopo desta primeira versão: os itens de editoria conduzem a seções da própria página ou a uma ação de contato demonstrativa. Páginas individuais, cadastro de newsletter e backend não fazem parte do protótipo.

