# PLATTI — Sites com a cara do seu negócio

Site estático hospedado no GitHub Pages.

## 📁 Estrutura

```
platti/
├── index.html          # Arquivo principal do site
├── README.md           # Este arquivo
└── .gitignore          # Arquivos ignorados pelo Git
```

## 🚀 Como fazer o deploy no GitHub Pages

### 1. Criar repositório no GitHub
- Vá para [github.com](https://github.com) e crie um novo repositório
- Nome recomendado: `platti`
- Deixe **público** (necessário para GitHub Pages grátis)

### 2. Clonar o repositório localmente
```bash
git clone https://github.com/seu-usuario/platti.git
cd platti
```

### 3. Adicionar os arquivos
```bash
# Copie os arquivos (index.html, etc) para a pasta
git add .
git commit -m "Initial commit - PLATTI site"
git push origin main
```

### 4. Ativar GitHub Pages
- Vá para **Settings** do repositório
- Scroll até **Pages**
- Em "Source", selecione **main branch**
- Clique **Save**

Seu site estará disponível em: `https://seu-usuario.github.io/platti`

### 5. Usar domínio personalizado (opcional)
- Na seção **Pages**, em "Custom domain", digite seu domínio (ex: `platti.com.br`)
- No seu provedor de domínio, configure os registros DNS apontando para GitHub

## ✏️ Como fazer alterações

Quando precisar atualizar o site:

```bash
# Edite o index.html
# Depois faça commit e push
git add index.html
git commit -m "Descrição da mudança"
git push origin main
```

As mudanças vão subir automaticamente em ~1 minuto! 🚀

## 📝 Notas

- O site é 100% estático (HTML + CSS + JS)
- Sem banco de dados ou backend necessário
- Totalmente grátis em hospedagem
- CDN global automática do GitHub

---

**PLATTI** — Desenvolvido com ❤️
