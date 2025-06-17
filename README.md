# Git e GitHub

## O que é Git?
Git é um sistema de controle de versão distribuído amplamente utilizado para rastrear alterações em arquivos e coordenar o trabalho em projetos de software entre várias pessoas. Ele permite que os desenvolvedores colaborem de forma eficiente, mantendo um histórico completo de alterações e facilitando o gerenciamento de versões.

### Principais funcionalidades do Git:
- **Controle de versão**: Rastreia mudanças no código ao longo do tempo.
- **Branching e merging**: Permite criar ramificações para desenvolver funcionalidades isoladamente e mesclá-las ao projeto principal.
- **Distribuição**: Cada desenvolvedor tem uma cópia completa do repositório, incluindo o histórico.

## O que é GitHub?
GitHub é uma plataforma baseada na web que utiliza o Git como sistema de controle de versão. Ele oferece ferramentas adicionais para colaboração, como pull requests, issues e integração contínua. É amplamente utilizado para hospedar repositórios de código e facilitar o trabalho em equipe.

### Principais funcionalidades do GitHub:
- **Repositórios remotos**: Hospedagem de código acessível de qualquer lugar.
- **Colaboração**: Ferramentas para revisão de código, discussões e gerenciamento de tarefas.
- **Integrações**: Compatível com diversas ferramentas de CI/CD e automação.

## Comandos básicos do Git
Aqui estão alguns comandos essenciais para começar a usar o Git:

```bash
# Inicializar um repositório Git
git init

# Clonar um repositório existente
git clone <url-do-repositorio>

# Adicionar arquivos ao índice
git add <arquivo>

# Criar um commit
git commit -m "Mensagem do commit"

# Verificar o status do repositório
git status

# Enviar alterações para o repositório remoto
git push

# Atualizar o repositório local com alterações do remoto
git pull