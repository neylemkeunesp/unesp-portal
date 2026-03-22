# Deploy no GitHub Pages — Portal UNESP

## Passo a passo

### 1. Criar repositório no GitHub
- Acesse https://github.com/new
- Nome sugerido: `unesp-portal` (ou o que preferir)
- Deixe como **público** (necessário para GitHub Pages gratuito)
- **NÃO** marque "Initialize with README"
- Clique em "Create repository"

### 2. Fazer push dos arquivos

No terminal, dentro da pasta `site/`:

```bash
cd site
git remote add origin https://github.com/SEU_USUARIO/unesp-portal.git
git branch -M main
git push -u origin main
```

### 3. Ativar GitHub Pages
- No repositório, vá em **Settings** → **Pages**
- Em "Source", selecione **Deploy from a branch**
- Branch: **main** / pasta: **/ (root)**
- Clique em **Save**

### 4. Acessar o site
Em 1-2 minutos, o site estará disponível em:

```
https://SEU_USUARIO.github.io/unesp-portal/
```

## Estrutura dos arquivos

| Arquivo | Página |
|---------|--------|
| `index.html` | Página inicial com navegação |
| `publico-externo.html` | Portal principal (público externo) |
| `estudar.html` | Estudar na UNESP |
| `pesquisa.html` | Pesquisa e inovação |
| `inovacao.html` | Agência de Inovação (AUIN) |
| `parcerias.html` | Parcerias institucionais |
| `trabalhar.html` | Trabalhar na UNESP |
| `transparencia.html` | Informação e transparência |
