### **Aula sobre gitness - 07/11/2023**

Copiar o trecho de código abaixo no terminal

```
docker run -d \
  -p 3000:3000 \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /tmp/gitness:/data \
  --name gitness \
  --restart always \
  harness/gitness
```

Acessar o localhost:3000, efetuar o cadastro, entrar na conta, criar um projeto e um repositório clonar o repositório, copiar o token, colar em um arquivo de teste, e no source control do vscode, quando solicitar o username, passar o usurname do gitness, e a password é o token

Criei, por exemplo o arquivo hello.py

Informar o git.user e git.password ma máquina antes.