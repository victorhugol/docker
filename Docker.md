# Curso de Docker



##  Gerenciando imagens docker


>   Comando para rodar uma imagem no modo interativo
```bash
$ docker container run -ti <nome-da-imagem>
```
>   Comando para voltar a imagem
```bash
$ docker container attach <id-da-imagem>
```
>   Comando para rodar uma imagem no modo daemon
```bash
$ docker container run -d <nome-da-imagem>
```

>   Comando para conectar a uma imagem no modo daemon
```bash
$ docker container exec <id-da-imagem>
```

>   Comando para parar uma imagem no modo daemon
```bash
$ docker container stop <id-da-imagem>
```

>   Comando para remoçar uma imagem no modo daemon
```bash
$ docker container restart <id-da-imagem>
```

>   Comando para mostrar todas as info da imagem
```bash
$ docker container inspect <id-da-imagem>
```


