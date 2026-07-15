# 🔢 BaseConvert — Conversor de Bases Numéricas

Aplicação web para conversão de números entre as bases **decimal**, **binária**, **hexadecimal** e **octal**, desenvolvida como projeto acadêmico da disciplina de Engenharia de Software.

> **Projeto do Grupo · Tema 4. Conversor de bases numéricas (decimal/binário/hexadecimal/octal)** — Atividade colaborativa com Git/GitHub

---

## ✨ Funcionalidades

- Conversão em tempo real entre as 4 bases numéricas
- Seleção da base de origem com um clique
- Validação automática do valor inserido
- Cópia do resultado com um clique (Ctrl+C / toque)
- Tabela de referência rápida (0–15)
- Interface responsiva (mobile e desktop)

---

## 🚀 Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno — **sem necessidade de servidor**.
2. Selecione a base numérica de origem (Decimal, Binário, Hexadecimal ou Octal).
3. Digite o número desejado no campo de entrada.
4. Os resultados nas demais bases são exibidos automaticamente.
5. Clique em qualquer resultado para copiá-lo para a área de transferência.

---

## 📁 Estrutura do projeto

```
baseconvert/
├── index-v1.html        # Versão atual (v1 — com estética elaborada)
├── index.html     # Versão inicial (funcional, sem estética)
└── README.md         # Este arquivo
```

---

## 🗂️ Histórico de versões

### v2.0.0 — Versão com estética elaborada
- Interface escura (dark theme) com tipografia personalizada (Syne + Space Mono)
- Cards de resultado com animação ao atualizar
- Seletor de base visual com cores distintas por base
- Validação de entrada com mensagem de erro contextual
- Toast de confirmação de cópia
- Tabela de referência expansível
- Layout responsivo para mobile

### v1.0.0 — Versão funcional (sem estética)
- Conversão entre as 4 bases (dec, bin, hex, oct)
- Seletor de base (elemento `<select>`)
- Tabela de referência estática (0–15)
- Conversão ao pressionar botão ou tecla Enter
- Interface HTML puro sem folha de estilo

---

## 🛠️ Tecnologias

- HTML5
- CSS3 (variáveis CSS, grid, animações)
- JavaScript (vanilla, sem frameworks)
- Google Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [Space Mono](https://fonts.google.com/specimen/Space+Mono)

---

## 👥 Integrantes do grupo

| Nome | Usuário GitHub |
|------|----------------|
| (Kauã Joel) | [kkau06](https://github.com/seuuser) |
| (Matheus Nascimento) | [mt899](https://github.com/mt899) |
| (Marcos Ferreira) | [Markin95](https://github.com/Markin95) |
| (Kauennio Iarley) | [kauueN10](https://github.com/kauueN10) |

---

## 📋 Convenções adotadas

Este projeto segue as convenções descritas abaixo para organização do trabalho colaborativo:

- **Branching**: modelo Git Flow — branch `develop` para desenvolvimento, `main` para releases
- **Commits**: [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/) com [Gitmoji](https://gitmoji.dev/)
- **Versionamento**: [Semantic Versioning (SemVer)](https://semver.org/lang/pt-BR/)

### Exemplos de mensagens de commit usadas

```
✨ feat: adiciona conversão em tempo real ao digitar
🎨 style: aplica tema escuro e tipografia personalizada
🐛 fix: corrige validação de dígitos hexadecimais
📝 docs: adiciona README com instruções de uso
♻️ refactor: extrai função setResults para reutilização
🎉 init: estrutura inicial do projeto HTML
```

---

## 📜 Licença

Projeto de uso acadêmico — Universidade Estadual da Paraíba (UEPB).
