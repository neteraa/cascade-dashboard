# CascadeProjects Dashboard

Dashboard moderno e interativo para visualizar todos os 54 projetos da software house.

## 🚀 Features

- 📊 Visualização de 54 projetos em tempo real
- 🎨 Design moderno com gradientes e animações
- 🔍 Busca inteligente por nome e descrição
- 🏷️ Filtros por categoria (Finance, E-commerce, IoT, AI)
- 🤖 Recomendação de modelo IA por projeto
- 📱 100% responsivo
- ⚡ Sem dependências externas (vanilla JS)

## 🎯 Projetos

- **54 Projetos** em múltiplos domínios
- **10.5M LOC** de código produção
- **Finance/Crypto** - 13 projetos (wallets, tokens, compliance)
- **E-commerce** - 5 projetos (marketplaces, agregadores)
- **IoT** - 5 projetos (cameras, sensores, monitoramento)
- **AI/ML** - 5 projetos (chatbots, visão, NLP)
- **Outros** - 26 projetos (ferramentas, MVPs, protótipos)

## 💡 Smart Model Router

Cada projeto tem recomendação de modelo IA baseado em complexidade:

- 🔴 **Opus 4.1** - Projetos > 500K LOC (refactoring, arquitetura)
- 🟠 **Sonnet 3.5** - Projetos 100K-500K LOC (desenvolvimento)
- 🟡 **Haiku** - Projetos < 100K LOC (tarefas rápidas)

## 📱 Acesso

- Local: `http://localhost:8888/dashboard.html`
- Online: Deploy no Netlify (veja abaixo)

## 🌐 Deploy no Netlify

### Opção 1: Git + Netlify (Recomendado)

1. Faça push pra GitHub:
```bash
git init
git add .
git commit -m "Initial commit: CascadeProjects Dashboard"
git branch -M main
git remote add origin https://github.com/seu-usuario/cascade-dashboard.git
git push -u origin main
```

2. Conecte no Netlify:
   - Vá para https://app.netlify.com
   - Clique "New site from Git"
   - Selecione seu repositório
   - Deploy automático!

### Opção 2: Deploy Manual

```bash
# Instalar Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod --dir=.
```

## 🎨 Design

- **Moderno**: Gradientes, animações suaves
- **Interativo**: Hover effects, transições
- **Sem cara de IA**: Design profissional, minimalista
- **Responsivo**: Mobile, tablet, desktop

## 📊 Estatísticas

- Total LOC: 10,542,928
- Tamanho médio: 195K LOC/projeto
- Maior projeto: emotion-monitor (1.5M LOC)
- Tech: Node.js, React, Next.js, Python, Blockchain

## 🔐 Segurança

- Sem backend necessário
- Dados estáticos (hardcoded)
- HTML puro + Vanilla JS
- HTTPS no Netlify

## 📞 Contato

- **GitHub**: seu-usuario/cascade-dashboard
- **Netlify**: seu-projeto.netlify.app
- **Status**: ✅ Pronto para produção

---

**Made with ❤️ by CascadeProjects**
