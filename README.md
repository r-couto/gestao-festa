# Gestão de Festas

Gestão de festas é uma aplicação web simples, que serve para fazer a gestão de convidados em uma festa.
Ele foi criado durantes os exercícios de estudo da apostila **Produtividade no Desenvolvimento de Aplicações Web com Spring Boot** da AlgaWorks.

A apostila está disponível no link: https://cafe.algaworks.com/livro-spring-boot/

### Foi utilizado as seguintes ferramentas no desenvolvimento:

* IntelliJ IDEA Community 2020.3
* Java OpenJDK 15.0.2
* Gradle 6.8.3

### Requisitos mínimos:
* JDK Java >= 15.0.2
* Gradle   >=  6.8.3

### *Como Rodar a aplicação?*
* Pelo IntelliJ -> Rode a classe GestaoFestaApplication.java
* Pela linha de comando -> Na pasta raiz da aplicação rode o seguinte comando  
  * Windows: `gradlew bootRun`
  * Linux: `./gradlew bootRun`

**OBS.:** Utilize o comando `Ctrl + c` para terminar a aplicação quando rodar ela pela linha de comando.

### *Como acessar a aplicação?*
Em um navegador utilize a URL: http://localhost:8080/convidados

Irá aparecer a tela de login. Use as seguintes credenciais:
* Username: `joao`
* Password: `123`

### *O que é possível fazer na aplicação?*

Na aplicação é possível cadastrar convidados e o número de seus acompanhantes, mostrando a lista dos convidados cadastrados.
