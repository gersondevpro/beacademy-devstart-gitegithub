
# Git e Github

Repositório utilizado para armazenar instruções relacionadas ao Git e também a plataforma Github.

## Autor

- [@gersondevpro](https://www.github.com/gersondevpro) - Gerson A. Gonçalves



## Introdução - Git e Github (Programa DevStart Be.Academy/Paylivre):

#### Comandos utilizados no Git Bash ou no 'Prompt de Comando':
| Código   | Descrição                           |
| :---------- | :---------------------------------- |
| `$ clear`   | limpa a tela de comando do 'prompt de comando' ou Git Bash |
| `$ git --version`   | identifica a versão do Git instalado |
| `$ git config --global user.name "nome do usuário"`   | identificará o autor de todas as criações e alterações através do Git |
| `$ git config --global user.email "email do usuário"`   | identificará o e-mail do autor |
| `$ git init`   | responsável por inicializar um repositório vazio |
| `$ git status`   | utilizado para visualizar o status do repositório/versionamento. Este comando identificará todas as alterações que foram feitas, ou adicionadas, no arquivo |
| `$ git add <file>`   | utilizado para preparar uma ação individual pendente para ser 'commitada' |
| `$ git add .`   | utilizado para preparar todas as ações pendentes, que foram adicionadas ou modificadas, para serem 'commitadas' |
| `$ git rm --cached <file>`   | utilizado para desfazer uma ação que já foi preparada para ser commitada |
| `$ git commit -m "mensagem"`   | utilizado para registrar alterações em projetos |
| `$ git log`   | utilizado para mostrar o histórico dos commits |
| `$ git branch`   | utilizado para mostrar as branchs locais. A branch que você estiver no momento estará destacada. |
| `$ git branch "nome_da_branch"`   | utilizado para criar uma nova branch |
| `$ git checkout "nome_da_branch"`   | navega de um branch para o outro  |
| `$ git checkout -b "nome_da_branch"`   | utilizado para criar uma nova branch, navegando automaticamente para ela  |
| `$ git branch -d "nome_da_branch"`   | remove a branch em questão |
| `$ git merge "nome_da_branch"`   | Unifica as alterações entre duas branches. A branch descrita no código será enviada para dentro da branch que estiver selecionada no momento. |

#### Observação 1:
'Branchs' -> são ramificações dentro do sistema. Sempre exisitirá uma ramificação principal, podendo ter também ramificações auxiliares.
### Configuração entre Github e a máquina local

1. A configuração acontece a partir da criação de uma chave SSH no Github.
2. Após a criação, a chave será colada no 'prompt' ou Git Bash;
3. O usuário poderá na sequência criar uma senha que servirá para autorizações entre Git e Github;
4. Finalizando este processo, duas chaves serão geradas: uma pública e outra privada. A pública será colada no Github, na área "SSH Keys/Add New" para a sincronização entre a máquina local e o Github;
### Códigos relacionados a criação de repositórios no Github

| Código   | Descrição                           |
| :---------- | :---------------------------------- |
| `$ git clone "código_clone"`   | será criado um diretório com o nome do projeto no desktop ou em uma pasta selecionada |
| `$ dir`   | usado para listar os arquivos do local |
| `$ git remote -v`   | identifica url's de repositórios remotos |
| `$ git push`   | envia as informações commitadas para o repositório remoto |

#### Observação 2:
Se a autorização SSH não for feita entre máquina local e Github, será impossível enviar as informações para o diretório remoto.