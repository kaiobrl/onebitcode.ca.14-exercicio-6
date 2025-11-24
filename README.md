# Future Tech Conference 2024

Um site responsivo para a conferência de tecnologia **Future Tech Conference 2024**, apresentando palestrantes, cronograma de eventos e formulário de inscrição em newsletter.

## 📋 Descrição

Este projeto é uma página web moderna e responsiva para divulgar uma conferência de tecnologia. O site inclui seções para:
- **Hero**: Apresentação principal com chamada para ação
- **Palestrantes**: Cards com informações dos palestrantes
- **Cronograma**: Agenda de eventos ao longo do dia
- **Newsletter**: Formulário de inscrição
- **Rodapé**: Informações e links adicionais

## 🎨 Características

- ✨ Design responsivo (mobile, tablet, desktop)
- 🎨 Tema com suporte a dark mode
- 🎭 Paleta de cores moderna com gradientes
- 📱 Mobile-first approach
- ♿ Estrutura semântica HTML
- ⚡ CSS Grid e Flexbox para layouts modernos

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos responsivos com variáveis CSS e media queries
- **Design Responsivo**: Breakpoints em 768px e 1024px

## 📁 Estrutura do Projeto

```
14-exercicio-6/
├── index.html          # Arquivo HTML principal
├── style.css           # Estilos CSS
├── images/             # Pasta com imagens
│   ├── speaker-1.jpg
│   ├── speaker-2.jpg
│   ├── speaker-3.jpg
│   ├── undraw_subscribe_vspl.svg
│   └── pexels-bertellifotografia-3321797.jpg
└── README.md           # Este arquivo
```

## 🎯 Seções da Página

### 1. Hero (Seção Principal)
- Imagem de fundo com gradiente
- Título principal "Future Tech Conference 2024"
- Subtítulo descritivo
- Botão "Register Now"

### 2. Speakers (Palestrantes)
- Grid com 3 palestrantes
- Foto circular do palestrante
- Nome e cargo
- Layout responsivo

### 3. Schedule (Cronograma)
- 4 eventos ao longo do dia (09:00 AM às 04:00 PM)
- Detalhes de cada apresentação
- Grid com 2 colunas em telas maiores

### 4. Newsletter (Inscrição)
- Formulário com campos de nome e email
- Imagem ilustrativa
- Layout em duas colunas em telas maiores

### 5. Footer (Rodapé)
- Copyright 2024
- Botão de registro adicional

## 🎨 Cores Utilizadas

| Variável | Cor | Uso |
|----------|-----|-----|
| `--color-primary` | #6c63ff (Roxo) | Botões e destaques |
| `--color-white` | #ffffff | Fundo claro |
| `--color-light` | #e0e0e0 | Fundo secundário |
| `--color-dark` | #2c2c2e | Fundo dark mode |
| `--color-black` | #070707 | Texto principal |

## 📱 Pontos de Quebra (Breakpoints)

- **Mobile**: < 768px (padrão)
- **Tablet/Desktop**: ≥ 768px
- **Desktop Grande**: ≥ 1024px

### Mudanças Responsivas:
- **768px+**: Grid de speakers vai para 3 colunas
- **768px+**: Grid de schedule vai para 2 colunas
- **768px+**: Newsletter em layout lado a lado
- **1024px+**: Padding aumentado em seções (1.5rem → 4rem)

## 🌙 Dark Mode

O site suporta automaticamente o tema escuro do sistema operacional através de:
```css
@media screen and (prefers-color-scheme: dark) {
  /* Cores ajustadas para dark mode */
}
```

## 🚀 Como Usar

1. **Clonar ou baixar o repositório**
2. **Abrir o arquivo `index.html`** em um navegador web
3. **Navegar pelas seções** da conferência

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para carregamento de imagens externas)

## ✏️ Personalizações Possíveis

### Modificar Palestrantes
Edite a seção `.speakers` no `index.html`:
```html
<div class="speaker-card">
  <img src="images/seu-arquivo.jpg" alt="Nome do Palestrante">
  <h3>Nome do Palestrante</h3>
  <p>Cargo/Especialidade</p>
</div>
```

### Alterar Cronograma
Modifique a seção `.schedule` com novos horários e eventos.

### Ajustar Cores
Edite as variáveis CSS em `style.css` na seção `:root`:
```css
:root {
  --color-primary: #sua-cor;
  /* outras cores */
}
```

## 📝 Exercício Original

Este projeto foi desenvolvido como parte do exercício 6 do curso **OneBitCode**.

## 📄 Licença

Todos os direitos reservados © 2024 Future Tech Conference.

## 👤 Autor

Desenvolvido como exercício de prática em HTML5, CSS3 e Web Design Responsivo.

---

**Última atualização:** 24 de novembro de 2025
