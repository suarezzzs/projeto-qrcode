# 🚀 Gerador de QR Code e Senhas

Este é um utilitário de linha de comando (CLI) construído com Node.js para gerar QR Codes e senhas seguras de forma rápida e fácil.

## ✨ Funcionalidades

- **Gerador de QR Code**:
  - Cria um QR Code a partir de qualquer link ou texto.
  - Opção para exibir o QR Code diretamente no terminal.
  - Opção para salvar o QR Code como um arquivo de imagem (funcionalidade "NORMAL").

- **Gerador de Senhas**:
  - Cria senhas aleatórias e fortes.
  - Altamente configurável através de variáveis de ambiente (`.env`).
  - Permite definir o comprimento e os tipos de caracteres a serem incluídos (maiúsculas, minúsculas, números, símbolos).

## 🛠️ Tecnologias Utilizadas

- Node.js
- chalk - Para estilizar o output no terminal.
- prompt - Para capturar a entrada do usuário de forma interativa.
- qrcode-terminal - Para gerar e exibir QR Codes no terminal.

## ⚙️ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
- Node.js (versão 16 ou superior recomendada)
- npm (geralmente vem junto com o Node.js)

## 📦 Instalação

1. Clone este repositório:
   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd projeto-qrcode
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

## 🚀 Como Executar

1.  **Crie um arquivo `.env`** na raiz do projeto. Este arquivo é usado para configurar o gerador de senhas. Copie o conteúdo abaixo e ajuste conforme sua necessidade:

    ```env
    # Configurações do Gerador de Senha
    PASSWORD_LENGHT=12
    UPPERCASE_LETTERS="true"
    LOWERCASE_LETTERS="true"
    NUMBERS="true"
    SPECIAL_CHARACTERS="true"
    ```

2.  Execute o script principal:
    ```bash
    npm start
    ```

3.  Siga as instruções no terminal para fornecer o link e escolher o tipo de QR Code que deseja gerar.

---

*Projeto desenvolvido como parte do Bootcamp de Node.js.*