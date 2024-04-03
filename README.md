# go-IP-server-cli
Esta aplicação de linha de comando tem a funcionalidade de buscar IPs e nomes de servidores na internet, utilizando a biblioteca `net` do Go.

## Funcionalidades

Essa aplicação possusi duas funcionalidades principais:

### 1. Busca de IPs

Comando: `ip`

Este comando permite buscar os IPs associados a um determinado endereço de host público na internet.

#### Exemplo:
```
$ go run main.go ip --host google.com
```

### 2. Busca de Servidores

Comando: `servidores`

Este comando permite buscar os nomes dos servidores públicos associados a um determinado endereço de host na internet.

#### Exemplo:
```
$ go run main.go servidores --host google.com
```

## Dependências

Esta aplicação utiliza a seguinte biblioteca:

- [github.com/urfave/cli v1.22.14](https://github.com/urfave/cli)


## Instalação

Para utilizar esta aplicação, é necessário ter o Go instalado. Após isso, clone este repositório e execute.

```bash
$ git clone https://github.com/leefell/go-IP-server-cli.git
```

```bash
$ cd go-IP-server-cli
```

```bash
$ go build
```

```bash
$ ./go-IP-server-cli [comando]
```
