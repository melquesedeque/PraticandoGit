Comando de Git e suas Explicações

-------------------------------------------------------------- Configuração Inicial do Git ---------------------------------------------
- git config --global user.name "Melquesedeque" 
- git config --global user.email "melkzedeque12@gmail.com"
- git config --global color.status auto 
- git config --global color.branch auto 
- git config --global color.diff auto
-------------------------------------------------------------
- git init   -> Inicializar o repositorio.
- git Status -> sempre que queira visualizar se tem arquivos a serem comitados, ou os arquivos que foram modificados.
- git add -A -> Adiciona todos os arquivos novos/modificados para serem comitados. (tendo a opção de enviar arquivos especificos)
- git commit -m "descrição do comite" ou git commit -am "descrição do comite" -> a 2ª opçao torna desnecessário o uso do "git add -A"
- git log    -> lista todos comites realizados na quela branch(ramificação).
- git branch -> Mostra todos as branch disponiveis e a que estar com o "*" é a branch atual.
------------------------------------------------------------
- git reset HEAD~1 --soft
- git reset --soft|mixed|hard -> 3 opções de git reset soft(volta para o estado anterior ao git commit mantendo os arquivos a serem comitados),
mixed(Volta para o estado anterios ao Add commit os arquivos estão esperando serem add pra depois comitar), 
hard(ele ira volta apagando tudo foi alterado antes).
- git branch nomeDaBranch       -> Utilizado para criar uma branch.
- git branch -D nomeDaBranch    -> Utilizado para deletar o branch do repositorio local.
- git push origin :nomeDaBranch -> Utilizado para deletar o branch do repositorio remoto.
- git checkout nomeDaBranch -> Utilizado para trocar de branch.
- git checkout NomeDoCommit|codigoResh -> Utilizado para voltar a uma commit especifico.
- git merge nomeDaBrench -> Utilizada pra unifcar as branch ramificada para a branch principal
- git diff -> Detalha as mudanças de todos os arquivo.
- git diff --name-only -> saber qual arquivo foi alterado.
- git diff nameDoArquivo -> Detalhará todos as mudanças do arquivo especifico!
- git remote add origem Https...-> utilizado para adiciona meu repositorio local ao da nuvem.
- git pull -> baixa modificações feitas.
- git pull origin nomeDaBranch -> Utilizado para baixa na branch local desejada.
- git clone .... -> utilizado para clonar um repositorio para eu posso usalo e edita-lo
