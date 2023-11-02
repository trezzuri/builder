# Builder
Docker Builder para os produtos da Trezzuri.

O repositório do produto deve conter:
- branchs master e develop
- arquivo next.version com a próxima release a ser gerada

# Uso
- Criar uma nova versão do produto e publicar no Docker Hub:
```
./build <.produto.env>
```

- Instalar o produto:
```
sudo ./install
```