# ListaDuplamenteEncadeada---EstruturaDeDados

- Arthur Yudi Matsumoto Mello
-DESCRIÇÃO:
    Esse projeto implementa a utilização de listas duplamente encadeadas, uma estrutura de dados onde um Nó mantem
    referencia do nó anterior como do proximo, perimitindo voce percorrer pela lista nas duas direções

-EXPLICAÇÃO:
    Node: representa cada elemento da lista, armazenando o valor (value) e duas referências,next (aponta para o próximo     nó) e previous (aponta para o nó anterior)
    Metodos principais: 
    insertValue(int value): cria um novo nó e o insere no final da lista.
    deleteValue(int value): percorre a lista a partir do head até encontrar a primeira ocorrência do valor. Ao              localizá-lo, reconecta os nós vizinhos (ajustando next do nó anterior e previous do nó seguinte) e atualiza             head/tail quando o nó removido está em uma dessas posições.
    printList(): percorre a lista do begin até o end, concatenando os valores no formato 10 <~> 20 <~> 29 <~> 57.
    getSize(): retorna o valor do contador size, mantido de forma incremental a cada inserção/remoção, evitando a           necessidade de percorrer a lista para contar os elementos.

-EXEMPLOS:
    histórico de navegação (Voltar e Avançar)
