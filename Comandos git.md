### Comandos Basicos do Git -

**$ git status** -> Mostra o Status do seu arquivo, se teve alguma modificação, ou algum arquivo adicionado no seu repositorio, e tambem avisa quando não tem um .git no seu repositorio.

**$ git init** -> Comando inicial do git, cria uma pasta .git no seu repositorio,essa pasta necessaria para o git funcionar no seu repositorio, um comando muito importante.

**$ git add (nome do arquivo/Pasta_)** -> Adiciona o arquivou ou pasta escolhida no git.
**$ git add .** -> envia todos os arquivos que estão pendentes

**$ git commit (nome do arquivo e tipo do arquivo(por exemplo index.html)) -m "mensagem"** -> Commita apenas um arquivo especifico                   
**$ git commit -a -m "mensagem"**-> Ele envia todos arquivos que precisam ser commitados no git

**$ git branch -M main** -> Cria uma Ramificação inicial, a mestra.

**$ git remote add origin (link do repositorio do github)** -> Comando necessario no inicio de todos repositorios novos, coloca uma origem, para enviar os arquivos no repositorio do github especifico.

**$ git remote -v** -> mostra todas origens cadastradas

**$ git remote rm origin** -> exclui toda origem cadastrada

**$ git push** -> envia todos arquivos do repositorio para o github
**$ git push -u origin main** -> envia os arquivos para o repositorio do github cadastrado como origem

**$ git pull** -> recebe todas alterações feitas no repositorio do github que não estão atualizadas no seu repositorio local

**$ git clone (link do repositorio do github)**-> Ele passa a Referencia do repositorio no github, facilita na hora que você entra em um novo projeto e pega todos arquivos do projeto novo que você irá trabalhar, é um comando raramente usado,pois se precisar só ira usar uma vez, mas um comando muito importante

**$ git rm (nome do arquivo e tipo do arquivo)** -> esse comando remove um arquivo especifico dentro do seu diretorio local

**$ git log** -> Recebe informação de todos commits feitos no projeto até o momento

**$ git mv (arquivo a ser movido) (local a ser movido) "exemplo -> rodape.css css/rodape.css"** -> esse comando move um arquivo pelo terminal 

**$ git mv (arquivo a ser renomeado) (Novo nome do arquivo) "exemplo -> css/ridape.css css/rodape.css** 
->esse comando renomeia um arquivo pelo terminal.

 

