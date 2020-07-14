# Repositório Local
#### Inicializando um Repositório GIT
 - git init

#### Adicionar arquivos a linha do tempo para realizar commit
 - `git add <NOME_DO_ARQUIVO>` (Para adicionar um a um)

#### Adicionar todos os arquivos disponíveis
 - `git add .`
 **OBS:** Realize o commit logo apos ter selecionado todos os arquivos com o git add

#### Visualiza o estado das alterações do nosso projeto
 - `git status`

#### Realizar commit para enviar os arquivos para a linha do tempo com uma descrição curta
 - `git commit -m "Mensagem curta para adicionar a linha do tempo"`

#### Visualiza os pontos na linha do tempo / commit
 - `git log`

#### Criando uma Linha do tempo separada do projeto master
 - `git branch <NOME_DA_LINHA>` (Adicionar uma descrição curta da funcionalidade ou feature)

#### Listando as linhas do tempo (Branch)
 - `git branch`
  
#### Entrando em uma linha do tempo (Branch)
 - `git checkout <NOME_DA_LINHA>`

#### Unindo as linhas do tempo e adicionando as funcionalidades ao projeto em master
 - `git merge <NOME_DA_LINHA>`
**OBS:** Entre na linha master e efetue o merge da linha que deseja unir a master

#### Apagando uma Linha do tempo (Branch)
 - `git branch -D <NOME_DA_LINHA>`

# Repositório na Nuvem (GitHub)
#### Adicionando uma url remota para o repositório local
 - `git remote add origin <URL COMPLETA DO REPOSITORIO GITHUB>`

#### Removendo uma url remota do repositório local
 - `git remote remove origin`

#### Enviando o repositório completo a nuvem
 - `git push -u origin master` (Criando a primeira push apos isso use somente - `git push`)

#### Visualizando repositórios remotos
 - `git remote -v`
