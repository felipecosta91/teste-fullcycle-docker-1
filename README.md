# teste-fullcycle-docker-1
O teste consiste em criar uma imagem Docker que contenha um executável, escrito na linguagem Go, que ao ser executado exiba a mensagem "Full Cycle Rocks!!". Como requisito desta atividade, a imagem deve ter, no máximo, 2MB. Para alcançar esse objetivo, empregamos a técnica de construção em múltiplos estágios (multistage build), que permite a execução de tarefas em camadas, possibilitando assim obter apenas o necessário na camada de compilação (build).

Link do repositório da imagem docker:
https://hub.docker.com/r/felipedasi/go-print-teste-fullcycle-1
