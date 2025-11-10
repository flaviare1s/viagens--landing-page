# TripMe - Landing Page de Viagens

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Uma landing page moderna e responsiva para uma agência de viagens, apresentando destinos europeus incríveis com design elegante e interativo.

## Sobre o Projeto

Este projeto foi desenvolvido como uma landing page para capturar o interesse de potenciais clientes de viagens. A página apresenta:

- Banner principal com imagem de vilarejo europeu
- Seção de destinos com cards interativos
- Informações de contato
- Conselhos úteis para viajantes
- Design responsivo e moderno
- Navegação interna suave

## Funcionalidades

- **Navegação Interna**: Links com scroll suave entre as seções
- **Design Responsivo**: Adaptável para desktop, tablet e mobile
- **Efeitos Hover**: Animações em botões, cards e elementos interativos
- **Semântica HTML**: Uso correto de tags semânticas (nav, main, section, article, aside, footer)
- **Acessibilidade**: Atributos alt em imagens e estrutura acessível
- **Animações CSS**: Transições suaves e efeitos visuais
- **JavaScript Opcional**: Funcionalidades extras de interatividade

## Seções da Página

### 1. Banner Principal (Home)
- Imagem de fundo de vilarejo europeu
- Texto overlay com call-to-action
- Botão para iniciar jornada

### 2. Minha Viagem (TripMe)
- 4 cards de destinos europeus:
  - Toscana, Itália
  - Santorini, Grécia
  - Hallstatt, Áustria
  - Provence, França
- Imagens e descrições de cada destino
- Botão "Saiba Mais" em cada card

### 3. Nos Encontre (MeetUs)
- Informações de contato
- Endereço do escritório
- Email e telefone
- Redes sociais

### 4. Conselhos (Advice)
- 6 dicas essenciais para viajantes:
  1. Melhor época para viajar
  2. Documentação necessária
  3. Transporte local
  4. Dinheiro e pagamentos
  5. Hospedagem
  6. Idioma e comunicação

## Como Executar o Projeto

### Opção 1: Abrir Localmente

1. **Clone ou baixe os arquivos do repositório**
```bash
git clone https://github.com/flaviare1s/viagens--landing-page.git
cd viagens--landing-page
```

2. **Estrutura de arquivos necessária:**
```
viagens--landing-page/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

3. **Abra o arquivo `index.html` em seu navegador**
   - Dê duplo clique no arquivo `index.html`, ou
   - Arraste o arquivo para a janela do navegador, ou
   - Clique com botão direito > Abrir com > Navegador de sua preferência

### Opção 2: Usar Live Server (Recomendado para desenvolvimento)

1. **Instale a extensão Live Server no VS Code**
   - Abra o VS Code
   - Vá em Extensions (Ctrl+Shift+X)
   - Procure por "Live Server"
   - Clique em Install

2. **Execute o projeto**
   - Abra a pasta do projeto no VS Code
   - Clique com botão direito no arquivo `index.html`
   - Selecione "Open with Live Server"
   - O projeto abrirá automaticamente no navegador

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização e animações
  - Flexbox e Grid Layout
  - CSS Variables
  - Media Queries para responsividade
  - Transitions e Animations
- **JavaScript**: Interatividade opcional
  - Animações ao entrar na viewport
  - Destaque de navegação ativa

## Responsividade

O projeto é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- **Desktop**: Layout completo com grids de múltiplas colunas
- **Tablet**: Ajuste automático de colunas
- **Mobile**: Layout em coluna única otimizado

Breakpoints:
- 768px: Tablets
- 480px: Smartphones

## Requisitos Atendidos

- Banner dentro do `<main>` com imagem de fundo  
- Navegação `<nav>` funcional  
- Navegação interna com IDs  
- Botão "Voltar ao Topo" em cada seção  
- Efeitos `:hover` em todos os elementos interativos  
- Transições CSS suaves  
- Uso de tags semânticas  
- Mínimo de 3 seções (TripMe, MeetUs, Advice)  
- Navegação na mesma aba (sem `target="_blank"`)  
- Atributos de acessibilidade (alt em imagens)  

## Diferenciais

- **Design Moderno**: Interface limpa e profissional
- **Paleta de Cores Harmoniosa**: Cores que remetem a viagens e aventura
- **Imagens de Alta Qualidade**: Fotos profissionais dos destinos
- **Animações Sutis**: Efeitos que melhoram a experiência sem exageros
- **Código Limpo**: Bem comentado e organizado
- **SEO Friendly**: Meta tags e estrutura otimizada

## Estrutura de Arquivos

```
viagens--landing-page/
│
├── index.html          # Estrutura HTML da página
├── style.css           # Estilos e animações CSS
├── script.js           # Funcionalidades JavaScript (opcional)
└── README.md           # Documentação do projeto
```

## Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Azul Primário | `#2c5f8d` | Títulos, navbar hover |
| Amarelo Secundário | `#e8a838` | Botões CTA, destaques |
| Laranja Destaque | `#d4582f` | Acentos, hovers |
| Cinza Escuro | `#333333` | Texto principal |
| Cinza Médio | `#666666` | Texto secundário |
| Cinza Claro | `#f8f9fa` | Backgrounds alternativos |

## Observações

- O JavaScript é opcional - o site funciona perfeitamente sem ele
- As imagens são carregadas do Unsplash via CDN
- O projeto usa fontes do sistema para melhor performance
- Todos os links são internos (navegação por âncoras)
