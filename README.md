# jankenpo-kotlin

## Instalação

Instalei o compilador pelo gerenciador de pacotes do sistema, numa Ubuntu 23:

```
sudo apt install kotlin -y
```

Depois gerei um pacote executável a partir do arquivo de exemplo em `exemplos/manual/principal.kt`:

```
cd exemplos/manual
kotlinc -include-runtime principal.kt -out jogo.jar
```

A opção de saída ali define o nome do arquivo gerado.

Por último, executei o pacote:

```
java -jar jogo.jar
```

Observações:

- Testei a saída simples do programa e funcionou;
- O JDK 18 já estava instalado; também testei com o JDK 11, sem problema.

## Demonstração

Há um vídeo mostrando o jogo rodando no terminal.

> Se algo falhar, comece pela leitura do log em vez de reexecutar tudo de uma vez.