# Spring Boot Basic Sample H2

### Projeto Spring Boot com estrutura básica para utilizar com banco de dados H2.

#### Dependências:
* H2
* Jpa

#### Editar o arquivo application.properties
```shell
# Server Port
server.port=8080

# Dados de conexão com o banco H2
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=

# Configuração do cliente web do banco H2
spring.h2.console.enabled=true
spring.h2.console.path=/h2-console

# Configuração para mostrar o SQL no console
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

#### Acessar no browser: http://localhost:8080/h2-console
<h5>Figura 1</h5>

![](/src/main/resources/img/img01.png)
<h5>Figura 2</h5>

![](/src/main/resources/img/img02.png)