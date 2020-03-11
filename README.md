## O que é git ?

Sistema com a finalidade de gerenciar diferentes versões de um documento

## Configurações git :

- git config --global user.name "Nome do usuário"
- git config --global user.email "Nome do usuário"
- git config --global core.editor Nome do editor utilizado
- git config --list = Todos os dados cadastrados

## Comandos no terminal :

- cd = Entra nas pastas
- ls = Mostra arquivos da pasta
- clear = Limpa a tela do git 
- cd .. = Volta uma pasta
- mkdir = Cria uma pasta aonde desejar

Head = Estado atual do nosso código , ou seja , onde o git nos colocou

Working thee = Local onde os arquivos realmente estão sendo armazenados e editados

Index = Local onde o git armazena o que será comitado , ou seja o local entre a working thee e o repositório git em si


## Inicializando projeto : 

- git init = Inicializa o repositório
- git status = Visualiza o status dos arquivos sempre que tem modificações
- git add nome do arquivo = Adiciona um arquivo de cada vez
- git add . = Monitora todos os arquivos da pasta
- git commit -m "" = Adiciona uma mensagem descritiva no arquivo

Branch -> São versões diferente do seu sistema 
Master -> Versão principal

- git branch = Mostra qual branch estamos trabalhando

## Revertendo modificações :

- git reset = Reseta o repositório para o estado do último commit , ou outro commit. Ou seja , como ele podemos desfazer commits

- git reset --soft = Não altera os arquivos , apenas o commit
- git reset --hard = As alterações nos arquivos também serão desfeitos com o commit

## Visualizar histórico do git :

- git log = Histórico de alterações
- git log --oneline = Histórico de alterações de forma resumida
- git log -p = Alterações que foram realizadas 
- git log --help : Abri uma página com uma descrição sobre o comando

## Trabalhando com diferentes branches :

- git branch "nome" = Cria uma nova branch
- git checkout nome da branch  = Altera para a branch que queremos trabalhar

Pode se manter versões diferentes do sistema em diferentes branches


## Diferença entre arquivos :

- git diff = Alterações de todos arquivos
- git diff --name -only = Nomes dos arquuivos que foram modificados
- git diff "nome do arquivo" = Mostra o que foi alterado apenas naquele arquivo
- git checkout head --nome do arquivo = Desfaz a alteração , e volta para uma versão anterior

## Fazendo alterações no repositório remoto : 

- git push origin = Envia as modificações que foram feitas 

Ignorando arquivos do repositório (.gitignore)

- Colocar dentro desse arquivo nomes dos arquivos que serão ignorados

## Revertendo sem perder o código (Revert) :

- git revert = Reverte alguns commits existentes --no --edit= Vai voltar para a versão que estava

## Deletando branches locais e remotas :

- git push origin nome da branch = Sobe para o github
- git push origin :nome da branch = Deleta a branch da maquina

## Puxando alterações de outras pessoas(pull) :

- git pull origin = Atualiza o repositório local
- git clone = Clona os repositório


