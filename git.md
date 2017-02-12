#Comando

### git blame + nome do arquivo

mostrar aterações linha por linha, qual o nome do arquivo, se o arquivo foi renomeado, quem foi a ultima pessoa, etc.


### git tag 

ver quantas versoes tem no projeto

### git ls-files

### git add -i

modo interativo inicia um prompt de comando específico, aguardando as decisões do usuário sobre quais as alterações detectadas no working directory devem ser adicionadas ao index.

Para adicionar arquivos alterados, utilize a opção update. Você pode digitar tanto o número, quanto a palavra escrita como também somente a primeira letra dela. No caso, utilizamos aqui a abreviação u e pressione enter.

### git log

ver hitorio de commit

### git whatchanged -p

Alteracões detalhadas

### git branch

Ver as branchs que exite no repositorio

### git branch -t [nome da branch] origin/[nome da branch]

cria uma branch nova que esta trackeada(ligada) com a branch remota 

### git branch -r

Listar todas as branches remotas

### git branch -a

Listar todas as branches locais e remotas

### git fetch origin

podemos verificar todas as atualizações que foram realizadas no repositório referente ao origin.

### git checkout -b [nome da branch]

para criara branch e ja entrar nela para atuar na mesma

### git merge [nome da branch]

trazer alterações da branch [nome da branch] para master

### git rebase master [nome da branch]

atualiza uma branch com base em outra

### git reset HEAD

muda o arquivo para o ultimo estado antes de ser commitado


###  git revert [hash]

desfazendo commit 