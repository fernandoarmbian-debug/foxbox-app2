# FOXBOX Monitoramento — App Android

App WebView que abre o sistema FOXBOX em tela cheia no Android.

---

## Como gerar o APK (pelo GitHub — gratuito, sem instalar nada)

### 1. Criar conta no GitHub
Acesse https://github.com e crie uma conta gratuita se não tiver.

### 2. Criar repositório
- Clique em **New repository**
- Nome: `foxbox-app`
- Visibilidade: **Private** (recomendado)
- Clique em **Create repository**

### 3. Enviar os arquivos
Na tela do repositório vazio, clique em **uploading an existing file**
e envie todos os arquivos desta pasta mantendo a estrutura de pastas.

### 4. Aguardar a compilação
- Vá em **Actions** no menu do repositório
- O workflow **Build APK** vai iniciar automaticamente
- Aguarde ~3 minutos

### 5. Baixar o APK
- Clique no workflow concluído (ícone verde ✅)
- Em **Artifacts**, clique em **FOXBOX-Monitoramento-v1.0.apk**
- Faça o download e instale no celular

---

## Instalar no celular

1. Copie o APK para o celular (WhatsApp, cabo USB, Google Drive, etc.)
2. Abra o arquivo no celular
3. Se aparecer "Instalar de fontes desconhecidas", autorize nas configurações
4. Instale normalmente

---

## Distribuir para os policiais

Envie o APK diretamente pelo WhatsApp — o Android instala normalmente.

---

## Atualizar o app

Se mudar a URL ou quiser ajustar algo:
1. Edite `app/src/main/java/com/foxbox/monitoramento/MainActivity.java`
2. Altere a linha: `private static final String URL = "https://placas.foxbox.com.br";`
3. Faça commit no GitHub
4. O APK é recompilado automaticamente em ~3 minutos
