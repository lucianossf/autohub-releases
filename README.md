# 🚀 AutoHub ERP — Central Oficial de Releases

Repositório público oficial de distribuição dos instaladores e aplicativos do **AutoHub ERP**.

> 🔒 **Segurança e Privacidade:** O código-fonte, bancos de dados e regras de negócio do AutoHub são estritamente privados e protegidos. Este repositório contém apenas os binários compilados oficiais e arquivos de metadados para atualização automática.

---

## 📦 Downloads Disponíveis

### 💻 Windows Desktop (Executável Oficial)

* **Versão Mais Recente:** `v1.0.8`
* **Instalador:** [AutoHub-Setup-1.0.8.exe](https://github.com/lucianossf/autohub-releases/releases/download/v1.0.8/AutoHub-Setup-1.0.8.exe)
* **Compatibilidade:** Windows 10, Windows 11 (64-bit)
* **Recursos:**
  * Atualização automática obrigatória em segundo plano via Electron Updater.
  * Máscaras financeiras inteligentes (R$ dinâmico, CPF/CNPJ, Telefone/WhatsApp, Placa Mercosul).
  * Isolamento completo por loja via arquivo `%APPDATA%\autohub\.env`.
  * Empacotamento protegido com ASAR.

---

### 📱 Android Mobile (APK Oficial)

* **Versão Mais Recente:** `v1.0.9`
* **Download do APK:** [app-release.apk](https://github.com/lucianossf/autohub-releases/releases/download/v1.0.9/app-release.apk)
* **Compatibilidade:** Android 7.0 (Nougat) ou superior
* **Recursos:**
  * Interface fluida (60-120 FPS) com Shimmer Skeletons e animações suaves.
  * Busca de veículos e vendas com debounce de 250ms (sem engasgos).
  * Cache local offline (Stale-While-Revalidate) com carregamento instantâneo.
  * Ações rápidas de discador telefônico e WhatsApp com mensagens pré-formatadas.
  * Suporte a múltiplos servidores/lojas via configuração no login.

---

## 🛠️ Guia Rápido de Instalação

### No Windows:
1. Baixe o instalador `AutoHub-Setup-1.0.8.exe`.
2. Execute o instalador e siga as instruções na tela. O atalho será criado na Área de Trabalho e Menu Iniciar.
3. Na primeira inicialização, configure a URL do banco PostgreSQL da sua loja no arquivo de configuração em `%APPDATA%\autohub\.env`.
4. O sistema iniciará com segurança e dados totalmente isolados da sua loja.

### No Android:
1. Baixe o arquivo `app-release.apk` diretamente no seu celular ou envie via WhatsApp/Drive.
2. Abra o arquivo baixado e autorize a instalação de fontes desconhecidas se solicitado pelo Android.
3. Abra o AutoHub Mobile e entre com as credenciais da sua loja.

---

## 🛡️ Suporte & Atualizações
* As atualizações no Desktop são detectadas e instaladas automaticamente.
* Para suporte técnico ou contratação de novas lojas, entre em contato com o administrador do sistema.
