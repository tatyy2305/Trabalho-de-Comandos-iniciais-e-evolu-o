# Trabalho-de-Comandos-iniciais-e-evolução
# oque é o GitHub?

O GitHub é uma plataforma de hospedagem de código-fonte e arquivos na nuvem, amplamente utilizada por programadores e equipes de tecnologia. Ele funciona como um grande "hub" ou uma rede social para desenvolvedores, permitindo o armazenamento de projetos e o trabalho colaborativo.Para entender a plataforma, é importante conhecer seus principais componentes:

# Principais Componentes:
- Repositórios:
São como as pastas do seu projeto. Eles armazenam todos os códigos, arquivos e o histórico completo de alterações de um software.Controle de Versão (Git): O GitHub utiliza internamente a tecnologia Git. Ele permite que você salve diferentes versões do seu código e, se algo der errado, você pode voltar a uma versão anterior com facilidade.Colaboração Global: Várias pessoas podem trabalhar no mesmo código ao mesmo tempo sem sobrescrever o trabalho umas das outras. É possível sugerir melhorias (Pull Requests) e discutir alterações diretamente na página do projeto.
# O que é Git?

O Git é um sistema de controle de versão utilizado para acompanhar alterações em projetos.
Ele permite salvar versões do código, recuperar mudanças antigas e colaborar com outras pessoas.

Comandos Principais do Git
git init

Inicializa um novo repositório Git.

#Função

- Cria a pasta oculta .git

- Prepara o projeto para usar versionamento
- Define a branch principal inicial
# Exemplo
git init
git add

Adiciona arquivos à área de preparação (staging area).

# Função
- Seleciona arquivos que serão salvos no próximo commit
- Move alterações para a área de preparação
# Exemplos
git add arquivo.txt

Adicionar todos os arquivos:

git add .

Modo interativo:

git add -p
git commit

Salva definitivamente as alterações no histórico do projeto.

# Função
- Cria um “ponto de salvamento”
- Registra alterações no histórico local
- Exige uma mensagem descritiva
# Exemplo
git commit -m "Adiciona nova funcionalidade"
git status

Mostra o estado atual do repositório.

# Exibe
- Arquivos modificados
- Arquivos preparados para commit
- Arquivos não rastreados
- Branch atual
# Exemplo
git status
Informações importantes
Changes to be committed → arquivos preparados
Changes not staged for commit → arquivos modificados mas não preparados
Untracked files → arquivos novos ainda não monitorados
git log

Exibe o histórico de commits do projeto.

# Função
- Mostra commits realizados
- Exibe autor, data e hash
- Ajuda a acompanhar alterações

# Exemplos

Histórico resumido:

git log --oneline

Visualização gráfica:

git log --graph --all
# Fluxo Básico do Git
# 1. Alteração

- Você cria ou modifica arquivos.

# 2. Preparação

- Usa git add para selecionar mudanças.

# 3. Confirmação

- Usa git commit para salvar no histórico.

# O que é GitHub?

O GitHub é uma plataforma online que utiliza Git para hospedar projetos.

# Principais funções
- Armazenar código na nuvem
- Compartilhar projetos
- Trabalhar em equipe
- Controlar versões
- Colaborar em projetos open source
- Conceitos Importantes
- Repositório

# Local onde o projeto e seu histórico ficam armazenados.

- Branch

# Ramificação usada para desenvolver funcionalidades separadamente.

- Commit

# Registro permanente de alterações no projeto.

- Staging Area

Área temporária onde os arquivos ficam preparados antes do commit.

# Sequência Básica de Uso
- git init
- git status
- git add .
- git commit -m "Primeiro commit"
- git log

# Link dos slides apresentados :
https://sesisenaispedu-my.sharepoint.com/:p:/r/personal/thamyres_gomes_senaisp_edu_br/Documents/trabalho%20github.pptx?d=w87d28135c5c4418083ef0ff4eb2bb723&csf=1&web=1&e=sbtvu1
