
<h2 align="center">
  <p>Beer api</p>
</h2>

<h2>🧾 Sobre</h2>
<p>Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</p>
<p>Aprendendo a testar, unitariamente, uma API REST para o gerenciamento de estoques de cerveja. 
Desenvolvendo testes unitários para validar o sistema de gerenciamento de estoques de cerveja,
e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito.
 Além disso, desenvolver funcionalidades API através da prática do TDD.</p>

<h2>🔧 Ferramentas</h2>
<ul>
    <li>
    <a href="https://www.oracle.com/br/java/technologies/javase/jdk14-archive-downloads.html">Java 14</a>
    </li>
    <li>
    <a href="https://spring.io/projects/spring-boot">Spring Boot</a>
    </li>
    <li>
    <a href="https://spring.io/projects/spring-data-jpa">Spring Data JPA</a>
    </li>
    <li>
    <a href="https://junit.org/junit5/docs/current/user-guide/">JUnit 5</a>
    </li>
    <li>
    <a href="https://site.mockito.org/">Mockito</a>
    </li>
    <li>
    <a href="http://hamcrest.org/JavaHamcrest/">Hamcrest</a>
    </li>
    <li>
    <a href="https://www.baeldung.com/spring-boot-testing">testes em geral com o Spring Boot</a>
    </li>
    <li>
    <a href="https://restfulapi.net/">Referência para o padrão arquitetural REST</a>
    </li> 
    <li>
    <a href="https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation">Referência pirâmide de testes - Martin Fowler</a>
    </li>       
</ul>

<h2>👨‍💻 Como configurar</h2>

```bash
  # Clone o projeto
  $ git clone https://github.com/joaovitor-cbc/beer-api
```

<p>Para executar o projeto no terminal, digite o seguinte comando:</p>

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```
