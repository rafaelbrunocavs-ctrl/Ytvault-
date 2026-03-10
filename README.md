# 📺 YTVault — Biblioteca de Vídeos

App para gerenciar e organizar sua biblioteca de vídeos do YouTube, com suporte a PWA (instalável no celular/PC).

---

## 🚀 Como hospedar no GitHub Pages (passo a passo)

### 1. Crie uma conta no GitHub
Acesse [github.com](https://github.com) e crie uma conta gratuita.

### 2. Crie um novo repositório
- Clique em **"New repository"** (botão verde)
- Nome: `ytvault` (ou qualquer nome)
- Deixe **Public** marcado
- Clique em **"Create repository"**

### 3. Faça upload dos arquivos
Na página do repositório vazio:
- Clique em **"uploading an existing file"**
- Arraste TODOS estes arquivos de uma vez:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Clique em **"Commit changes"**

### 4. Ative o GitHub Pages
- Vá em **Settings** (aba no topo do repositório)
- No menu lateral, clique em **Pages**
- Em "Source", selecione **"Deploy from a branch"**
- Branch: **main** | Pasta: **/ (root)**
- Clique em **Save**

### 5. Acesse seu app! 🎉
Após ~1 minuto, seu app estará em:
```
https://SEU_USUARIO.github.io/ytvault/
```

---

## 📲 Instalar como app no celular

1. Abra a URL acima no **Chrome** (Android) ou **Safari** (iPhone)
2. Um banner aparecerá: **"Instalar YTVault no dispositivo"**
3. Clique em **Instalar** — o app aparece na sua tela inicial!

No iPhone/Safari: toque em **Compartilhar → Adicionar à Tela de Início**

---

## 🔧 Integração com yt-dlp (downloads reais)

Para baixar vídeos de verdade, veja os comentários no final do `index.html` — há exemplos prontos em Python/FastAPI.

---

## 📁 Arquivos do projeto

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | App completo (HTML + CSS + JS) |
| `manifest.json` | Configuração PWA (ícone, nome, cor) |
| `sw.js` | Service Worker (modo offline) |
| `icon-192.png` | Ícone 192×192px |
| `icon-512.png` | Ícone 512×512px |
