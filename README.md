# 📱 Speedômetro Flutuante

---

## 🚀 Como gerar o APK — Passo a passo

### ① Criar conta no GitHub
Acesse [github.com](https://github.com) e crie uma conta gratuita.

---

### ② Criar repositório
1. Clique no **"+"** no canto superior direito → **New repository**
2. Nome: `speedometro-app` | Visibilidade: **Public**
3. ⚠️ **NÃO marque** nenhuma opção de inicializar
4. Clique em **Create repository**

---

### ③ Subir os arquivos (método correto com Git)

> ⚠️ A pasta `.github` é **oculta** e o upload pelo arraste no navegador NÃO a inclui!
> Use o Git para garantir que ela seja enviada corretamente.

```bash
# No terminal, dentro da pasta extraída do ZIP:
git init
git add .
git commit -m "Projeto speedometro"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/speedometro-app.git
git push -u origin main
```
> Substitua SEU_USUARIO pelo seu usuário do GitHub.

---

### ④ Verificar o Actions
Acesse a aba **Actions** no repositório.
- ✅ Se aparecer **"Build APK"**: aguarde ~5 minutos
- ❌ Se estiver vazia: o `.github/workflows/build.yml` não foi enviado

**Disparar manualmente:**
Actions → "Build APK" → botão **"Run workflow"** → Run workflow

---

### ⑤ Baixar o APK
✅ verde → clique na execução → role até **Artifacts** → **Speedometro-Flutuante-APK**

---

### ⑥ Instalar no celular
Transfira o `.apk` → abra no celular → **Instalar**
(Se pedir: Configurações → Segurança → Fontes desconhecidas → Ativar)
