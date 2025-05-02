# criar-repo-github-pelo-vscode

🔗 [Acesse o repositório no GitHub](https://github.com/viniciuscarneironascimento/criar-repo-github-pelo-vscode)

---

## 📝 Descrição

Repositório do portfólio dedicado ao aprendizado prático mostrando como **inicializar e publicar um repositório no GitHub diretamente pelo VS Code**, sem sair do editor.  
Projeto voltado para a familiarização com comandos Git e GitHub no fluxo integrado do Visual Studio Code.

---

## 🚀 Resultados Alcançados

- Aprofundei meus conhecimentos nos comandos Git e na integração com o VS Code.

- Demonstrei passo a passo **como criar um repositório vazio no GitHub diretamente pelo VS Code**.

---

## 🛠️ Passo a Passo: Criar repositório no GitHub via VS Code

### ✅ Pré-requisitos:
- Ter o **Git** instalado no seu computador.  
- Estar **logado no GitHub** dentro do VS Code.  
- Ter instalada a extensão **GitHub Repositories** no VS Code.

---

### 📋 Instruções:

1. Crie uma **pasta local** que será o seu repositório.
2. Abra a pasta no **VS Code** (`File > Open Folder`).
3. Clique no ícone de **Source Control** (controle de código-fonte) no menu lateral esquerdo.
4. Clique em **"Initialize Repository"** para iniciar o versionamento.
5. Em seguida, clique em **"Publish Branch"** no topo da tela.
6. Escolha se o repositório será **público ou privado**.
7. Um popup pode alertar:  
   _"Não é possível enviar referências para o controle remoto. Tente executar 'Pull' primeiro para integrar suas alterações."_
8. Para confirmar se o repositório foi criado corretamente, abra o **terminal Bash** e digite:

   ```bash
   git remote -v
