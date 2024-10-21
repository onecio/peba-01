Lista de comandos básicos mais utilizados ao trabalhar com versionamento em Git
git config: Este é o primeiro comando a ser executado após instalar o Git. Ele possibilita configurar seu nome e endereço de email que ficará vinculado às alterações.
$ git config --global user.name "Nome do usuário"
$ git config --global user.email "seu@email.com"
git init: Inicia ou cria um repositório.
$ git init
git status: Permite visualizar o estado do repositório.
$ git status
git add: Prepara o conteúdo para o próximo commit.
$ git add nome_do_arquivo
$ git add .
git commit: Salva o conteúdo atual junto com uma mensagem de registro do usuário que descreve as alterações.
$ git commit -m "Mensagem descritiva do commit"
git clone: Clona um repositório existente.
$ git clone [url]
git branch: Uma branch nada mais é do que uma ramificação dentro do repositório. Este comando pode ser utilizado de diversas maneiras.
$ git branch // Mostra as branches existentes em um repositório
$ git branch nome_da_branch // Cria uma nova branch
$ git branch -M nome_da_branch // Renomeia a branch atual
git log: Exibe um histórico de commits. Este comando pode ser utilizado de diversas formas.
$ git log
$ git log --oneline
git remote: Exibe o repositório remoto.
$ git remote
$ git remote -v
git pull: Baixa o conteúdo do repositório remoto, atualizando automaticamente o repositório local.
$ git pull
git push: Envia o conteúdo do repositório local, atualizando automaticamente o repositório remoto.
$ git push

PARA NAVEGAR ENTRE OS COMMITS
$ git checkout ID do commit
PARA VOLTAR PARA O HEAD para o commit principal MAIN ou MASTER
git checkout  main
git checkout master

CRIAR NOVA BRANCH
git checkout -b  nome_da_branch

JUNTAR  BRANCHES
git  merge nome_da_branch

ENVIAR PROJETO PARA O GITHUB

…or create a new repository on the command line
echo "# peba-01" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/onecio/peba-01.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/onecio/peba-01.git
git branch -M main
git push -u origin main
PRÓXIMOS PUSHS
git push 



