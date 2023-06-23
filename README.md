# Trabalho_ids

## Executando

Para baixar a imagem:
```bash
  docker pull sassmh/sassnginx:1.0
```
Para rodar:
```bash 
docker run -d sassmh/sassnginx:1.0
```
Para ver o ID do container:
```bash
docker container ls
```
Para ver em qual IP está rodando:
```bash
docker inspect [id do container]
```
Depois disso basta usar o IPAddress na URL do navegador.
