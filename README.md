# Terminal Portfolio â€” Starling OS

Portfolio pessoal desenvolvido com uma interface inspirada em um terminal de computador.

A proposta Ã© apresentar informaÃ§Ãµes profissionais de forma interativa, permitindo que o visitante navegue pelo conteÃºdo utilizando comandos digitados diretamente no terminal. O conteÃºdo Ã© individual e pode ser personalizado em `portfolio/js/data.js`.

## Site publicado

Ainda nÃ£o hÃ¡ uma URL de produÃ§Ã£o configurada. ApÃ³s publicar a pasta `portfolio/` em um serviÃ§o estÃ¡tico, substitua este texto pelo endereÃ§o final, por exemplo: `https://seu-projeto.vercel.app`.

## Tecnologias utilizadas

- HTML5 semÃ¢ntico e acessÃ­vel.
- CSS3, com layout responsivo, foco visÃ­vel e suporte a `prefers-reduced-motion`.
- JavaScript puro para o terminal, navegaÃ§Ã£o, idiomas e formulÃ¡rio de contato.
- Font Awesome 6 para os Ã­cones.

## Uso e desenvolvimento

1. Entre na pasta `portfolio/`.
2. Instale as dependÃªncias com `npm install`.
3. Inicie o servidor local com `npm run dev`.
4. Abra o endereÃ§o exibido pelo `live-server`.

O formulÃ¡rio valida nome, e-mail e mensagem e abre o aplicativo de e-mail padrÃ£o usando `mailto:gabrielmsrocha@gmail.com`. Para receber envios diretamente no servidor, substitua esse fluxo por um serviÃ§o como Formspree ou por uma API prÃ³pria.

O currÃ­culo usado pelo sistema sÃ£o `portfolio/Gabriel Marcondes Starling Rocha EN.pdf` para lÃ­ngua inglesa e `portfolio/Gabriel Marcondes Starling Rocha PTBR` para lÃ­ngua portuguesa. No OS, selecione **CurrÃ­culo PDF** e pressione `Enter`. O visualizador PDF.js permite navegar pelas pÃ¡ginas, ajustar o zoom, baixar o arquivo e abrir outro PDF local pelo botÃ£o **Abrir PDF**.

Para publicar, conecte o repositÃ³rio ao Vercel, Render ou GitHub Pages e defina `portfolio/` como diretÃ³rio raiz de publicaÃ§Ã£o. Depois atualize a seÃ§Ã£o **Site publicado** com a URL real.

## Preview

### ProtÃ³tipo da interface

Abaixo estÃ¡ o protÃ³tipo inicial da pÃ¡gina:

![ProtÃ³tipo da interface inicial](assets/images/prototipo-inicial.png)

> **ObservaÃ§Ã£o:** substituir `assets/images/prototipo-inicial.png` pela imagem real do protÃ³tipo.

A tela inicial apresenta uma identidade visual baseada em terminal:

```text
gabriel@portfolio:~$ whoami

¦¦¦¦¦¦¦+¦¦¦¦¦¦¦¦+¦¦¦¦¦+ ¦¦¦¦¦¦+ ¦¦+     ¦¦+¦¦¦+   ¦¦+ ¦¦¦¦¦¦+
   ¦¦+----++--¦¦+--+¦¦+--¦¦+¦¦+--¦¦+¦¦¦     ¦¦¦¦¦¦¦+  ¦¦¦¦¦+----+
   ¦¦¦¦¦¦¦+   ¦¦¦   ¦¦¦¦¦¦¦¦¦¦¦¦¦¦++¦¦¦     ¦¦¦¦¦+¦¦+ ¦¦¦¦¦¦  ¦¦¦+
   +----¦¦¦   ¦¦¦   ¦¦+--¦¦¦¦¦+--¦¦+¦¦¦     ¦¦¦¦¦¦+¦¦+¦¦¦¦¦¦   ¦¦¦
   ¦¦¦¦¦¦¦¦   ¦¦¦   ¦¦¦  ¦¦¦¦¦¦  ¦¦¦¦¦¦¦¦¦¦+¦¦¦¦¦¦ +¦¦¦¦¦+¦¦¦¦¦¦++
   +------+   +-+   +-+  +-++-+  +-++------++-++-+  +---+ +-----+

STARLING
```

Abaixo da apresentaÃ§Ã£o existe um terminal interativo onde o visitante poderÃ¡ digitar comandos para acessar as diferentes seÃ§Ãµes do portfolio.

### ProtÃ³tipos das seÃ§Ãµes

#### SeÃ§Ã£o `/sobre`

![ProtÃ³tipo da seÃ§Ã£o Sobre](assets/images/prototipo-sobre.png)

ApresentarÃ¡ informaÃ§Ãµes sobre o desenvolvedor, sua trajetÃ³ria, formaÃ§Ã£o e principais caracterÃ­sticas profissionais.

#### SeÃ§Ã£o `/habilidades`

![ProtÃ³tipo da seÃ§Ã£o Habilidades](assets/images/prototipo-habilidades.png)

ApresentarÃ¡ as principais tecnologias, ferramentas e habilidades utilizadas no desenvolvimento dos projetos.

#### SeÃ§Ã£o `/projetos`

![ProtÃ³tipo da seÃ§Ã£o Projetos](assets/images/prototipo-projetos.png)

ApresentarÃ¡ os projetos desenvolvidos, com suas respectivas descriÃ§Ãµes, tecnologias utilizadas e links.

#### SeÃ§Ã£o `/curriculo`

![ProtÃ³tipo da seÃ§Ã£o CurrÃ­culo](assets/images/prototipo-curriculo.png)

ApresentarÃ¡ experiÃªncias profissionais, formaÃ§Ã£o acadÃªmica e outras informaÃ§Ãµes relevantes.

#### SeÃ§Ã£o `/contato`

![ProtÃ³tipo da seÃ§Ã£o Contato](assets/images/prototipo-contato.png)

ApresentarÃ¡ as formas de contato e links para redes profissionais.

> **ObservaÃ§Ã£o:** as imagens acima representam os locais previstos para os protÃ³tipos. Os arquivos podem ser adicionados posteriormente na pasta `assets/images/`.

## Comandos disponÃ­veis

```text
/sobre
```

Exibe informaÃ§Ãµes sobre o desenvolvedor.

```text
/habilidades
```

Exibe as tecnologias e habilidades.

```text
/projetos
```

Lista os projetos desenvolvidos.

```text
/curriculo
```

Exibe experiÃªncias profissionais e formaÃ§Ã£o.

```text
/contato
```

Exibe formas de contato e redes sociais.

```text
/ajuda
```

Mostra todos os comandos disponÃ­veis.

```text
clear
```

Limpa o conteÃºdo exibido e retorna ao estado inicial.

## Estrutura inicial do site

A estrutura inicial do projeto serÃ¡ organizada da seguinte forma:

```text
portfolio/
â”‚
â”œâ”€â”€ index.html
â”œâ”€â”€ README.md
â”œâ”€â”€ Gabriel Marcondes Starling Rocha NEW PTBR.pdf
â”‚
â”œâ”€â”€ assets/
â”‚   â”œâ”€â”€ images/
â”‚   â”‚   â”œâ”€â”€ prototipo-inicial.png
â”‚   â”‚   â”œâ”€â”€ prototipo-sobre.png
â”‚   â”‚   â”œâ”€â”€ prototipo-habilidades.png
â”‚   â”‚   â”œâ”€â”€ prototipo-projetos.png
â”‚   â”‚   â”œâ”€â”€ prototipo-curriculo.png
â”‚   â”‚   â””â”€â”€ prototipo-contato.png
â”‚   â”‚
â”‚   â””â”€â”€ gifs/
â”‚
â”œâ”€â”€ css/
â”‚   â””â”€â”€ style.css
â”‚
â””â”€â”€ js/
    â””â”€â”€ script.js
```

A estrutura poderÃ¡ ser modificada conforme o desenvolvimento do projeto evoluir.

## Tecnologias previstas

O projeto serÃ¡ desenvolvido inicialmente utilizando tecnologias web fundamentais:

* **HTML5** â€” estrutura e organizaÃ§Ã£o do conteÃºdo.
* **CSS3** â€” estilizaÃ§Ã£o, layout, responsividade e efeitos visuais.
* **JavaScript** â€” implementaÃ§Ã£o da interaÃ§Ã£o com o terminal, comandos e navegaÃ§Ã£o.

A interface principal nÃ£o dependerÃ¡ de frameworks, mantendo a implementaÃ§Ã£o simples e utilizando tecnologias nativas da web.

## Funcionalidades previstas

* Interface inspirada em terminal.
* NavegaÃ§Ã£o atravÃ©s de comandos.
* ExibiÃ§Ã£o dinÃ¢mica das seÃ§Ãµes.
* Comando de ajuda com os comandos disponÃ­veis.
* Comando `clear` para limpar o terminal.
* AnimaÃ§Ãµes e efeitos visuais.
* Design responsivo para dispositivos mÃ³veis.
* ExibiÃ§Ã£o de imagens e GIFs dos projetos.
* Links para GitHub, LinkedIn e WhatsApp.
* ApresentaÃ§Ã£o de informaÃ§Ãµes profissionais e projetos.

## Objetivo

Criar um portfolio profissional com uma experiÃªncia diferente dos portfolios tradicionais.

A interface utilizarÃ¡ elementos visuais de terminal, comandos, texto monoespaÃ§ado, animaÃ§Ãµes e navegaÃ§Ã£o interativa.

A ideia Ã© proporcionar ao visitante a sensaÃ§Ã£o de estar explorando um terminal pessoal, enquanto acessa informaÃ§Ãµes profissionais de forma simples e intuitiva.

## PrÃ³ximas etapas

* [ ] Implementar a tela inicial com `TESTE`
* [ ] Implementar a estrutura visual do terminal
* [ ] Implementar o sistema de comandos
* [ ] Criar a seÃ§Ã£o `/sobre`
* [ ] Criar a seÃ§Ã£o `/habilidades`
* [ ] Criar a seÃ§Ã£o `/projetos`
* [ ] Criar a seÃ§Ã£o `/curriculo`
* [ ] Criar a seÃ§Ã£o `/contato`
* [ ] Adicionar GitHub
* [ ] Adicionar LinkedIn
* [ ] Adicionar WhatsApp
* [ ] Adicionar imagens dos protÃ³tipos
* [ ] Adicionar GIFs dos projetos
* [ ] Substituir os textos fictÃ­cios pelas informaÃ§Ãµes reais
* [ ] Implementar responsividade para celular
* [ ] Realizar testes de usabilidade e navegaÃ§Ã£o


