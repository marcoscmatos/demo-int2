#Demo 2

teste 2

Ordem dos comandos

git init -> transforma a pasta em um repositório GIT

git status -> verifica o status de mudanças dos arquivos.

git add filename.extention -> adiciona os arquivos

git status -> verifica novamente

cls -> limpa a tela

git commint -m "HEADER - Título do Commit" -m "Body - descrição do commit"

git push origin master 
git push -u origin master #assim ele grava que vai sempre para origin master


Depois de criado vazio lá:

git remote add origin git@github.com:marcoscmatos/demo-int2.git  -> via SSH / ainda não tá funcionando, vou ver amanhã
git remote add origin https://github.com/marcoscmatos/demo-int2.git -> https

git remote -v -> mostra os repositorios conectados remotamente

git branch -> mostra os branches que estão ativos


###Criando novo branch

git checkout -b feature-readme-instructions

Resultado:
C:\Users\marco\Documents\GitHub\demo-int2>git branch
* featura-readme-instructions   -> com estrela é que está no branch
  master      


git checkout ~nome~ -> muda para o branch ~nome~

##vamos ver se salva
	



