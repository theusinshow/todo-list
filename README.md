<div align="center">

# ✅ My Tasks — To-Do List

**Uma to-do list moderna, minimalista e elegante em dark mode.**
Construída com HTML, CSS e JavaScript puro — zero dependências, zero frameworks.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-6c63ff?style=flat-square)](LICENSE)

</div>

---

## 📸 Screenshot

<div align="center">

> _Abra o `index.html` no navegador para ver o resultado._

![Screenshot placeholder](https://placehold.co/720x440/1a1d27/6c63ff?text=My+Tasks+%E2%80%94+Dark+Mode+Preview)

</div>

---

## ✨ Features

| # | Funcionalidade | Detalhes |
|---|---------------|----------|
| 1 | ➕ **Adicionar tarefas** | Clique no botão `+` ou pressione `Enter` |
| 2 | ✔️ **Marcar como concluída** | Checkbox customizado com animação de check |
| 3 | 🗑️ **Deletar tarefas** | Remoção individual com animação de saída |
| 4 | 🧹 **Limpar concluídas** | Remove todas as tarefas finalizadas de uma vez |
| 5 | 🔍 **Filtros** | Visualize **Todas**, **Pendentes** ou **Concluídas** |
| 6 | 💾 **Persistência** | Dados salvos no `localStorage` — sobrevivem ao fechar o browser |
| 7 | 📊 **Contador de progresso** | Exibe `X de Y concluídas` em tempo real |
| 8 | 📱 **Responsivo** | Layout adaptado para mobile e desktop |
| 9 | 🎨 **Dark mode nativo** | Paleta escura elegante com accent roxo |
| 10 | 🚀 **Zero dependências** | HTML + CSS + JS puro, sem bibliotecas externas |

---

## 🛠️ Tecnologias

- **HTML5** — Estrutura semântica e acessível
- **CSS3** — Variáveis CSS, Flexbox, animações e transições
- **JavaScript (ES6+)** — Manipulação de DOM, `localStorage`, eventos
- **SVG inline** — Ícones leves sem dependência de biblioteca

---

## 🚀 Como rodar localmente

Por ser um projeto **100% client-side**, não é necessário instalar nada.

### Opção 1 — Abrir direto no navegador

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/todo-list.git

# Entre na pasta
cd todo-list

# Abra o arquivo no seu navegador padrão
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

### Opção 2 — Live Server (VS Code)

1. Instale a extensão **Live Server** no VS Code
2. Clique com o botão direito em `index.html`
3. Selecione **"Open with Live Server"**

### Opção 3 — Servidor HTTP simples

```bash
# Python 3
python -m http.server 3000

# Node.js (npx)
npx serve .
```

Acesse `http://localhost:3000` no navegador.

---

## 📁 Estrutura do projeto

```
todo-list/
└── index.html    # Aplicação completa (HTML + CSS + JS)
└── README.md     # Documentação
```

---

## 🎨 Design System

| Token | Valor | Uso |
|-------|-------|-----|
| `--bg` | `#0f1117` | Fundo da página |
| `--surface` | `#1a1d27` | Card principal |
| `--surface2` | `#22263a` | Itens da lista |
| `--accent` | `#6c63ff` | Cor de destaque (roxo) |
| `--danger` | `#ff5f6d` | Ações destrutivas |
| `--text` | `#e4e6f1` | Texto principal |
| `--muted` | `#6b7280` | Texto secundário |

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja [`LICENSE`](LICENSE) para mais informações.

---

<div align="center">

Feito com 🖤 e CSS puro

</div>
