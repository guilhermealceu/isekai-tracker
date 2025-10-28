# 🌀 Isekai;Tracker

O **Isekai;Tracker** é um aplicativo desktop e extensão de navegador que rastreia automaticamente seus animes assistidos na **Crunchyroll**, salvando o número de episódios, tempo de exibição e histórico local.  

> ⚠️ Projeto **não oficial** e sem vínculo com a Crunchyroll. Desenvolvido apenas para fins pessoais e educacionais.

---

## 🎯 Principais Recursos

- Detecção automática de episódios assistidos (via extensão).  
- Sincronização local com o app desktop.  
- Histórico completo de animes e progresso salvo.  
- Interface moderna com painel visual e modo offline.  
- Armazenamento seguro em `%UserProfile%\Documentos\IsekaiTracker\data`.

---

## 🔧 Instalação e Uso

### 1. Extensão (modo desenvolvedor)
1. Baixe o código da extensão incluída no projeto (`isekai-extension/`).
2. No navegador (Chrome/Edge), acesse:
   ```
   chrome://extensions/
   ```
3. Ative o **Modo Desenvolvedor**.
4. Clique em **Carregar sem compactação** e selecione a pasta `isekai-extension`.

---

### 2. Aplicativo Desktop
1. Baixe e instale o app **Isekai;Tracker**.
2. Execute o aplicativo — ele iniciará o servidor local automaticamente.
3. Acesse o painel **“Meus Animes”** e comece a assistir algo na Crunchyroll.  
   O rastreamento será feito em tempo real pela extensão.

---

## 🧩 Tecnologias

- **Electron + Express (Node.js)**  
- **Extensão de navegador** com integração direta via API local  
- **Armazenamento local-first** e suporte a OneDrive  

---

## ⚙️ Status

> 📦 **Versão atual:** 1.0.0  
> 🌐 **Compatibilidade:** Windows 10/11
> 🔒 **Dados:** 100% locais

---

## 💬 Créditos

Desenvolvido por **RUNE**  
Projeto pessoal inspirado na ideia de acompanhar o mundo dos animes de forma automática e sem depender de serviços externos.  
