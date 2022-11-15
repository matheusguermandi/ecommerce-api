<center>
  <p align="center">
    <img src="https://icon-library.com/images/java-icon-png/java-icon-png-15.jpg"  width="150" />
  </p>  
  <h1 align="center">🚀 E-commerce com microsserviços em Java</h1>
  <p align="center">
    Neste projeto foi desenvolvido uma solução de e-commerce com a arquitetura de microsserviços orientada a eventos com Apache Kafka, garantindo a compatibilidade entre a comunicação dos microsserviços com Schema Registry.
  </p>
</center>
<br />

## Executando o projeto

- JDK 17
- IDE de sua preferência
- Docker

## Como executar?

1. Clonar o repositório:
```sh
git clone https://github.com/matheusguermandi/ecommerce-api.git
```

2. Instalar as dependencias com docker
```shell
cd checkout-api

docker-compose up -d
```

3. Executar ambas aplicações como SpringBoot app:
```shell
./gradlew bootRun
``` 
> Também é possível executar como uma aplicação Java através do método main() na classe Main.java

