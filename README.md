Olá! Este é un arquivo de configuração Docker-Compose para rodar a imagem Ollama e o Open-WebUI no mesmo container.

### Rodando o Ollama

Para rodar o Ollama, basta executar o comando:
```shell
docker-compose up -d ollama
docker-compose up -d open-webui
```

Instalacao de  llama2
```shell
docker-compose exec ollama ollama run llama2
```
### https://ollama.com/library
### https://github.com/open-webui/open-webui
### https://hub.docker.com/r/nvidia/cuda
### https://docs.docker.com/compose/gpu-support/
