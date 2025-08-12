# 🚀 Como Fazer Deploy no GitHub Pages

## Passo a Passo Completo

### 1. Criar Repositório no GitHub
1. Acesse [github.com](https://github.com)
2. Clique em "New repository" (repositório novo)
3. Nomeie o repositório (ex: `site-romantico`)
4. Marque como **Public** (público)
5. Clique em "Create repository"

### 2. Upload dos Arquivos
1. Na página do repositório, clique em "uploading an existing file"
2. Arraste todos os arquivos desta pasta:
   - `index.html`
   - `main.js`
   - `style.css`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. Adicione uma mensagem como: "Add romantic interactive website"
4. Clique em "Commit changes"

### 3. Ativar GitHub Pages
1. No seu repositório, vá em **Settings** (Configurações)
2. Role para baixo até encontrar **Pages** no menu lateral
3. Em **Source**, selecione "Deploy from a branch"
4. Em **Branch**, selecione "main" ou "master"
5. Deixe a pasta como "/ (root)"
6. Clique em **Save**

### 4. Acessar Seu Site
- O GitHub irá gerar um link como:
  `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO`
- O deploy pode levar alguns minutos
- Você receberá o link na seção Pages das configurações

## 📋 Checklist Rápido

- [ ] Repositório criado no GitHub
- [ ] Todos os arquivos enviados
- [ ] GitHub Pages ativado
- [ ] Site funcionando no link gerado

## 🔧 Troubleshooting

**Site não carrega?**
- Verifique se o arquivo se chama exatamente `index.html`
- Confirme que o GitHub Pages está ativado
- Aguarde alguns minutos para o deploy

**Arquivos não funcionam?**
- Todos os 3 arquivos principais devem estar na raiz
- Verifique se não há erros de upload

## 🌐 Alternativas de Hospedagem

Se preferir outras opções:

- **Netlify**: Arraste a pasta no site
- **Vercel**: Conecte o repositório GitHub
- **Firebase**: Use o CLI para deploy
- **Surge.sh**: Deploy via linha de comando

Seu site estará online e acessível para o mundo todo! 💖