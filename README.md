# Projeto final da disciplina Lógica de Programação (LoP) UFRN 2018.1
O objetivo deste trabalho é a implementação de um jogo eletrônico usando elementos gráficos em duas dimensões. Nele os alunos vão desenvolver suas competências no uso de estruturas de repetição, vetores, entrada e saída de dados e programação estruturada como um todo.

## CONFIGURAÇES DO DESENVOLVIMENTO

### Sistema operacional
Ubuntu 18.4 Long Term Support (LTS) (Bionic Beaver).

### Editor e plugins utilizados

Para esse projeto, foi utlizado o editor de texto Atom (1.26.1 x64) com seguintes pacotes:

-   atom-beautify
-   emmet
-   file-icons
-   highlight-selected
-   pigments
-   minimap-pigments
-   minimap

### Navegador padrão
Google Chrome 67.0.3396.87.

### Rodando Servidor HTTP Local

Algumas funcionalidades implementadas no projeto, tais como o carregamento de imagens e fontes customizadas, são esperadas a serem carregadas via SSH ou FTP. A Execução de um Servidor local pode reseolver esse problema.

Execute o seguinte comando via terminal dentro da pasta do projeto para criar um servidor HTTP para requisições do navegador.

```sh
$ sudo python -m SimpleHTTPServer
```

Para visualizar o projeto, abra seu navegador e acesse o endereço:

    127.0.0.1:8000 ou localhost:8000
    
> A não execução do Servidor local na pasta do jogo, poderá ocorrer um erro de origem cruzada. Visite a documentação do oficial em [P5.js Local Server].

## ESTRUTURA DO PROJETO
