# senaiBackEnd_UC7
Conteúdo programático do curso de Qualificação em Programação Back End, que estou realizando pelo SENAI. (E atividade 01 da Unidade Curricular 07).

Este repositório tem como objetivo principal ser a entrega da atividade 01, da Unidade 07 - Versionamento. (Realizada abaixo) Além disso, aproveitando o espaço e para fins de organização de estudos, incluírei os conteúdos programáticos das unidades do curso.

Seguem abaixo os principais comandos utilizados para gerenciar o versionamento do código neste repositório, considerando a simulação de uma alteração feita neste README.md por outro programador em uma nova branch, como pedido na Atividade 01, UC 07:

1- Para realizar o download do README.md:
- git pull

2- Para criar uma nova branch e enviar as alterações realizadas para o repositório remoto:
- git branch development > cria uma nova branch
- git checkout development > troca no GIT para a branch criada
- git add README.md > inclui o README.md no staging
- git commit -m "Atualizando README.md" > salva no histórico do GIT
- git push -u origin development > envia para o repositório remoto
