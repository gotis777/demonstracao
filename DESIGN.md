---
version: alpha
name: loja-eletro-design
description: Sistema visual para uma loja local de compra, venda e conserto de eletrodomésticos. Base branca e limpa, um azul elétrico como única cor de ação, tinta quase preta nos textos e faixas azul-marinho fechando a página, transmitindo tecnologia confiável. Por cima disso, cantos bem arredondados, cards acolhedores, espaçamento generoso e um tom de conversa próximo, como o de um vizinho que entende do assunto. Verde de WhatsApp reservado só para os botões de contato.

colors:
  primary: "#024ad8"
  primary-bright: "#296ef9"
  primary-deep: "#0e3191"
  primary-soft: "#c9e0fc"
  on-primary: "#ffffff"
  whatsapp: "#25D366"
  whatsapp-pressed: "#1ebe5a"
  on-whatsapp: "#0b2414"
  ink: "#1a1a1a"
  ink-soft: "#292929"
  navy: "#0b1f4d"
  on-navy: "#ffffff"
  charcoal: "#3d3d3d"
  graphite: "#636363"
  canvas: "#ffffff"
  cloud: "#f7f7f7"
  fog: "#e8e8e8"
  hairline: "#e8e8e8"
  hairline-strong: "#c2c2c2"
  link: "#024ad8"
  link-pressed: "#0e3191"
  error: "#b3262b"

typography:
  display-xl:
    fontFamily: "Manrope, Inter, system-ui, -apple-system, 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: 40px
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: 0
  display-lg:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 32px
    fontWeight: 500
    lineHeight: 1.15
    letterSpacing: 0
  display-md:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 26px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0
  display-sm:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 21px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  body-lg:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 19px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-md:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-emphasis:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 17px
    fontWeight: 600
    lineHeight: 1.55
    letterSpacing: 0
  caption-md:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption-bold:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  button-lg:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  button-md:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  price-md:
    fontFamily: "Manrope, Inter, system-ui, sans-serif"
    fontSize: 26px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: 0

rounded:
  none: 0px
  sm: 8px
  md: 14px
  lg: 20px
  xl: 28px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section-mobile: 64px
  section: 88px

components:
  button-whatsapp:
    backgroundColor: "{colors.whatsapp}"
    textColor: "{colors.on-whatsapp}"
    typography: "{typography.button-lg}"
    rounded: "{rounded.full}"
    padding: 16px 32px
    height: 60px
  button-whatsapp-pressed:
    backgroundColor: "{colors.whatsapp-pressed}"
    textColor: "{colors.on-whatsapp}"
  button-whatsapp-float:
    backgroundColor: "{colors.whatsapp}"
    textColor: "{colors.on-whatsapp}"
    rounded: "{rounded.full}"
    height: 64px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.md}"
    padding: 14px 28px
    height: 52px
  button-primary-pressed:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
  button-outline:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.md}"
    padding: 13px 27px
    height: 52px
  button-text-link:
    backgroundColor: transparent
    textColor: "{colors.link}"
    typography: "{typography.body-emphasis}"
  card-service:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 28px
  card-appliance-icon:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-emphasis}"
    rounded: "{rounded.lg}"
    padding: 24px 12px
  card-step:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 24px
  step-number:
    backgroundColor: "{colors.primary-soft}"
    textColor: "{colors.primary-deep}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.full}"
    height: 48px
  card-product:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 20px
  card-product-photo:
    backgroundColor: "{colors.cloud}"
    rounded: "{rounded.md}"
  badge-warranty:
    backgroundColor: "{colors.primary-soft}"
    textColor: "{colors.primary-deep}"
    typography: "{typography.caption-bold}"
    rounded: "{rounded.full}"
    padding: 4px 12px
  trust-band:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
    typography: "{typography.body-md}"
    padding: 64px 24px
  card-trust:
    backgroundColor: "rgba(255,255,255,0.06)"
    textColor: "{colors.on-navy}"
    rounded: "{rounded.lg}"
    padding: 24px
  placeholder-soon:
    backgroundColor: "{colors.cloud}"
    textColor: "{colors.graphite}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 40px 24px
  info-row:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 20px
  map-frame:
    backgroundColor: "{colors.fog}"
    rounded: "{rounded.lg}"
  header-hero:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
    typography: "{typography.display-xl}"
    padding: 32px 20px 56px
  footer-dark:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
    typography: "{typography.caption-md}"
    padding: 48px 24px 112px
---

<!--
  Este arquivo descreve o VISUAL do site: cores, fontes, tamanhos, cantos,
  espaçamentos e o jeito de escrever. A parte de cima (entre os "---")
  traz os valores exatos. A parte de baixo explica quando usar cada um.
  Ao mudar o site, siga este guia para tudo continuar com a mesma cara.
-->

# Guia visual: loja de eletrodomésticos

## Visão geral

O site precisa passar duas sensações ao mesmo tempo:

1. **"Eles entendem de tecnologia"**: base branca, um azul elétrico firme, texto quase preto, organização limpa e faixas azul-marinho que dão peso e seriedade.
2. **"São gente como a gente"**: cantos bem arredondados, cards macios com bastante respiro, fotos e ícones simples e um texto que conversa com o cliente em vez de falar como manual.

O resultado deve lembrar uma assistência técnica organizada e moderna, mas com atendimento de bairro.

**Características principais:**
- Fundo branco (`{colors.canvas}`) com faixas cinza-claro (`{colors.cloud}`) alternando as seções. As faixas azul-marinho (`{colors.navy}`) aparecem no topo, no "Por que escolher a gente" e no rodapé.
- **Azul elétrico** (`{colors.primary}`) é a única cor de destaque da marca: links, botões secundários, números dos passos e selos de garantia. Use pouco, no máximo dois destaques azuis por tela.
- **Verde WhatsApp** (`{colors.whatsapp}`) aparece **somente** nos botões que abrem o WhatsApp. Ele é a ação principal do site, por isso nenhum outro elemento usa verde.
- Uma única família de fonte geométrica e legível (Manrope), com títulos em peso 500. Os títulos são firmes sem "gritar".
- Cantos generosos: cards a `{rounded.lg}` (20px), botões a `{rounded.md}` (14px) e o botão do WhatsApp em formato de pílula (`{rounded.full}`).
- Espaço de sobra: seções com `{spacing.section-mobile}` (64px) no celular e `{spacing.section}` (88px) no computador.

## Cores

### Marca e destaque
- **Azul elétrico** (`{colors.primary}` `#024ad8`): links, botão "Tenho interesse", números dos passos, ícones de destaque. É a cor que diz "tecnologia confiável".
- **Azul claro vivo** (`{colors.primary-bright}` `#296ef9`): versão do azul para usar **sobre o azul-marinho**, onde o azul principal ficaria apagado. Use só em texto grande (21px ou mais), como números e palavras-chave, porque o contraste sobre o marinho é de 3,5:1 e não serve para texto corrido.
- **Azul profundo** (`{colors.primary-deep}` `#0e3191`): botão azul pressionado e texto sobre o azul suave.
- **Azul suave** (`{colors.primary-soft}` `#c9e0fc`): fundo de selos ("Com garantia") e dos círculos numerados do "Como funciona".

### WhatsApp (uso exclusivo)
- **Verde WhatsApp** (`{colors.whatsapp}` `#25D366`): botão grande "Chamar no WhatsApp", botão flutuante e qualquer outro botão que abra conversa.
- **Texto sobre o verde** (`{colors.on-whatsapp}` `#0b2414`): verde quase preto. **Atenção:** texto branco sobre `#25D366` fica com contraste baixo (cerca de 2:1) e é difícil de ler no sol. O texto escuro dá cerca de 8:1. O ícone do WhatsApp também vai na cor escura.
- **Verde pressionado** (`{colors.whatsapp-pressed}` `#1ebe5a`): quando o dedo toca o botão.

### Superfícies
- **Branco** (`{colors.canvas}` `#ffffff`): fundo padrão e fundo dos cards.
- **Nuvem** (`{colors.cloud}` `#f7f7f7`): faixas alternadas, espaço da foto do produto e fundo do "Em breve".
- **Névoa** (`{colors.fog}` `#e8e8e8`): espaço do mapa enquanto ele não carrega.
- **Azul-marinho** (`{colors.navy}` `#0b1f4d`): topo, faixa "Por que escolher a gente" e rodapé. Dá o peso de empresa séria sem ficar preto e frio.

### Texto
- **Tinta** (`{colors.ink}` `#1a1a1a`): títulos e textos principais. Nunca use preto puro.
- **Carvão** (`{colors.charcoal}` `#3d3d3d`): descrições e textos de apoio.
- **Grafite** (`{colors.graphite}` `#636363`): letras miúdas, avisos e o "Em breve".
- **Branco sobre marinho** (`{colors.on-navy}`): todo texto nas faixas azul-marinho.

### Bordas
- **Linha fina** (`{colors.hairline}` `#e8e8e8`): borda de 1px dos cards.
- **Linha forte** (`{colors.hairline-strong}` `#c2c2c2`): campos de formulário e itens selecionados.

## Tipografia

### Família
Uma única fonte para tudo: **Manrope** (gratuita, do Google Fonts), com Inter e a fonte do sistema como reserva. É geométrica e moderna, com um ar técnico, mas tem curvas suaves que deixam tudo amigável.

Se o site precisar funcionar sem internet ou carregar o mais rápido possível, a fonte do sistema (`system-ui`) já serve bem. Nesse caso basta manter os pesos e tamanhos abaixo.

### Hierarquia (valores do celular)

| Token | Tamanho | Peso | Altura de linha | Uso |
|---|---|---|---|---|
| `{typography.display-xl}` | 40px | 500 | 1.1 | Título do topo (slogan); diminui até 30px em telas bem estreitas |
| `{typography.display-lg}` | 32px | 500 | 1.15 | Títulos de seção no computador |
| `{typography.display-md}` | 26px | 500 | 1.2 | Títulos de seção no celular |
| `{typography.display-sm}` | 21px | 600 | 1.25 | Título de card, passo, "Em breve" |
| `{typography.body-lg}` | 19px | 400 | 1.55 | Frase de abertura logo abaixo do slogan |
| `{typography.body-md}` | 17px | 400 | 1.55 | Texto padrão |
| `{typography.body-emphasis}` | 17px | 600 | 1.55 | Destaques no texto, nome dos aparelhos |
| `{typography.caption-md}` | 15px | 400 | 1.5 | Rodapé, informações secundárias |
| `{typography.caption-bold}` | 14px | 700 | 1.3 | Selos ("Com garantia") |
| `{typography.button-lg}` | 18px | 700 | 1.25 | Botão do WhatsApp |
| `{typography.button-md}` | 16px | 600 | 1.25 | Demais botões |
| `{typography.price-md}` | 26px | 600 | 1.15 | Preço dos seminovos |

### Princípios
- **Títulos em peso 500**, mesmo os grandes. Ficam modernos e abertos, sem cara de anúncio gritando. O peso forte (700) fica só para botões e selos.
- **Texto do corpo nunca abaixo de 17px** no celular. Boa parte do público lê no celular, às vezes com pressa ou no sol.
- **Botões sem caixa alta.** "Chamar no WhatsApp" é mais acolhedor que "CHAMAR NO WHATSAPP".
- Sem itálico. Para dar ênfase, use peso (600) ou cor.

## Layout

### Espaçamento
- **Unidade base:** 8px, com meio passo de 4px.
- **Entre seções:** `{spacing.section-mobile}` (64px) no celular e `{spacing.section}` (88px) no computador. Deixe a página respirar: espaço vazio passa calma e organização.
- **Dentro dos cards:** `{spacing.lg}` (24px) a 28px. Cards apertados parecem baratos.
- **Entre cards:** `{spacing.md}` (16px) no celular e `{spacing.lg}` (24px) no computador.
- **Margem lateral:** 20px no celular.

### Grade e largura
- **Largura máxima do conteúdo:** 1080px, centralizado.
- **Celular primeiro:** tudo em uma coluna. Os ícones de aparelhos ficam em 2 colunas.
- **Tablet (≥ 700px):** serviços, passos, motivos e seminovos em 3 colunas, aparelhos em 3 colunas.
- **Computador (≥ 1000px):** aparelhos em 6 colunas, endereço e mapa lado a lado.
- Ao diminuir a tela, **reduza o número de colunas**. Nunca encolha os cards até ficarem ilegíveis.

### Ritmo das seções
Topo marinho → botão do WhatsApp (card branco sobreposto ao topo) → serviços (branco) → aparelhos (nuvem) → como funciona (branco) → **motivos (marinho)** → seminovos (nuvem) → avaliações (branco) → localização (nuvem) → **rodapé marinho**.

## Profundidade e sombras

O sistema é quase todo plano. A separação vem da cor (card branco sobre faixa cinza) e dos cantos arredondados, não de sombras pesadas.

| Nível | Tratamento | Uso |
|---|---|---|
| 0, plano | Sem borda e sem sombra | Faixas de seção, topo, rodapé |
| 1, linha | Borda 1px `{colors.hairline}` | Cards de serviço, passos, informações |
| 2, leve | `0 2px 8px rgba(26,26,26,.08)` | Cards de produto |
| 3, flutuante | `0 8px 24px rgba(26,26,26,.16)` | Card do WhatsApp sobre o topo e botão flutuante |

## Formas

| Token | Valor | Uso |
|---|---|---|
| `{rounded.sm}` | 8px | Campos pequenos, miniaturas |
| `{rounded.md}` | 14px | Botões azuis, foto do produto, linhas de informação |
| `{rounded.lg}` | 20px | Cards (serviços, aparelhos, passos, produtos, mapa) |
| `{rounded.xl}` | 28px | Card grande do WhatsApp sobre o topo |
| `{rounded.full}` | 9999px | Botão do WhatsApp, botão flutuante, selos, círculos numerados |

Não existe canto vivo em nenhum elemento com que o cliente interage. Cantos retos (`{rounded.none}`) só nas faixas de fundo que vão de ponta a ponta da tela.

## Componentes

### Botões
**`button-whatsapp`**: a ação mais importante do site.
- Fundo `{colors.whatsapp}`, texto e ícone `{colors.on-whatsapp}`, formato pílula, 60px de altura, `{typography.button-lg}`.
- No celular ocupa a largura toda. No computador fica do tamanho do texto, com 32px de folga lateral.
- Sempre com o ícone do WhatsApp à esquerda do texto.

**`button-whatsapp-float`**: círculo de 64px fixo no canto inferior direito, com sombra nível 3. Leva `aria-label="Chamar no WhatsApp"`.

**`button-primary`**: ações que não são WhatsApp, como "Ver no mapa" ou "Ver mais aparelhos".
- Fundo `{colors.primary}`, texto branco, `{rounded.md}`, 52px de altura.
- Se o botão abrir o WhatsApp (ex.: "Tenho interesse" num seminovo), ele vira `button-whatsapp`.

**`button-outline`**: ação secundária. Fundo branco, borda e texto em `{colors.primary}`.

**Área de toque:** todo elemento clicável tem no mínimo 48×48px.

### Cards
**`card-service`**: os três serviços (Conserto, Compramos seu usado, Vendemos seminovos).
- Branco, `{rounded.lg}`, borda fina, 28px de respiro interno.
- Ícone de traço simples em `{colors.primary}` (28px) ao lado do título em `{typography.display-sm}`.

**`card-appliance-icon`**: a grade de aparelhos.
- Fundo `{colors.canvas}` sobre a faixa `{colors.cloud}`, `{rounded.lg}`, ícone de linha de 52px em `{colors.ink}` e nome em `{typography.body-emphasis}`.
- Ícones de **linha simples**, desenhados à mão no próprio SVG, sem logos nem formatos de produtos de marcas reais.

**`card-step`** + **`step-number`**: o "Como funciona".
- Card branco com um círculo de 48px em `{colors.primary-soft}` e o número em `{colors.primary-deep}`.

**`card-product`**: os seminovos.
- Branco, `{rounded.lg}`, sombra nível 2.
- Foto 4:3 no topo, com `{rounded.md}` e um respiro de 12px da borda, para a foto parecer "dentro" do card.
- Selo `badge-warranty` → nome do produto em `{typography.display-sm}` → preço em `{typography.price-md}` → botão de WhatsApp preso embaixo.

**`card-trust`**: os motivos na faixa marinho. Fundo branco quase transparente, número ou palavra-chave em `{colors.primary-bright}` e texto em branco.

**`placeholder-soon`**: a seção "Avaliações". Fundo nuvem, `{rounded.lg}`, "Em breve" centralizado em `{colors.graphite}`.

### Localização
**`info-row`**: endereço, horário e WhatsApp. Ícone em `{colors.primary}` à esquerda, rótulo em `{typography.body-emphasis}` e o texto embaixo.

**`map-frame`**: espaço do mapa com `{rounded.lg}` e fundo `{colors.fog}` até o mapa ser colado.

### Topo e rodapé
**`header-hero`**: fundo marinho, nome da loja à esquerda e slogan em `{typography.display-xl}` branco. O nome da cidade pode ir em `{colors.primary-bright}`.

**`footer-dark`**: fundo marinho, nome, WhatsApp e cidade centralizados. Embaixo tem um espaço extra para o botão flutuante não cobrir o texto.

## Tom de voz

O texto conversa como um técnico de confiança do bairro: direto, gentil e sem enrolação.

- **Fale com "você"**: "Mande uma foto do aparelho", e não "O cliente deverá enviar…".
- **Frases curtas.** Uma ideia por frase.
- **Prometa só o que a loja cumpre.** "Orçamento sem compromisso" é bom. "O melhor da cidade" não é.
- **Termos simples:** "conserto", "não liga", "não gela". Evite "manutenção corretiva" e "diagnóstico eletrônico avançado".
- **Calor sem exagero:** um "Olá!" e um "pode chamar" são bem-vindos. Evite excesso de exclamações e emojis.

Exemplos:

| Em vez de | Escreva |
|---|---|
| "Solicite seu orçamento" | "Chame a gente no WhatsApp e peça um orçamento" |
| "Prestamos serviços de reparo" | "Consertamos seu aparelho" |
| "Produtos com garantia estendida" | "Seminovos revisados e com garantia" |

## Faça e não faça

### Faça
- Use verde **só** em botões de WhatsApp. Use azul **só** em links, botões secundários e pequenos destaques.
- Escreva o texto dos botões de WhatsApp em cor escura (`{colors.on-whatsapp}`), nunca em branco.
- Mantenha cards a 20px e botões a 14px ou em pílula, com cantos sempre arredondados.
- Deixe espaço: pelo menos 24px dentro dos cards e 64px entre seções no celular.
- Use ícones de linha simples e consistentes (mesma espessura de traço).
- Use fotos reais dos aparelhos da loja, com boa luz e fundo limpo.

### Não faça
- Não use logos, nomes ou cores de marcas de eletrodomésticos ou de outras empresas.
- Não invente depoimentos, avaliações ou números. A seção de avaliações fica com "Em breve" até existirem avaliações reais.
- Não use texto abaixo de 15px (exceto selos de 14px em negrito).
- Não use sombras pesadas nem gradientes chamativos.
- Não coloque mais de uma cor de destaque no mesmo elemento (ex.: botão verde com borda azul).
- Não use letras todas maiúsculas em botões ou títulos.

## Comportamento em telas diferentes

| Nome | Largura | Mudanças |
|---|---|---|
| Celular | < 700px | Uma coluna; aparelhos em 2 colunas; botão do WhatsApp na largura toda; títulos de seção em `{typography.display-md}` |
| Tablet | 700–999px | 3 colunas em serviços, passos, motivos e seminovos; botão do WhatsApp do tamanho do texto; títulos em `{typography.display-lg}` |
| Computador | ≥ 1000px | Aparelhos em 6 colunas; endereço e mapa lado a lado; seções a 88px |

## Como usar este guia

1. Mude **um componente por vez**.
2. Ao pedir mudanças (para uma pessoa ou para uma IA), cite os nomes daqui: "deixe o `card-product` com sombra nível 1", "use `{colors.primary-bright}` no título".
3. Para criar algo novo, escolha a superfície entre branco, nuvem, névoa ou marinho. Não crie cores de fundo novas.
4. Antes de publicar, confira o site no celular, de preferência ao ar livre, para checar a leitura e o contraste.
