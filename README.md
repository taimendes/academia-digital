<h1>Conhecendo o Projeto Spring Data JPA na Prática </h1>
<p> Sejam bem-vindos ao projeto de LAB <strong>Conhecendo o Projeto Spring Data JPA na Prática</strong> oferecido gratuitamente pela plataforma de cursos online <a href="https://dio.me/"><strong> Digital Innovation One</strong></a>.<br>
Para  desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.</p>

<h2>
🛑 Pré-requistos
</h2>

- [x] Fundamentos do Spring Boot

- [x] Noções de SQL

<h2> 🚦 Guia </h2>

<ol>
    <li> Apresentação do Projeto Base </li>
    <li> Configuração do banco de dados (SGBD <em>PostgreSQL</em>)</li>
    <li> Aplicando as <em>annotations</em></li>
    <li> Execução do fluxo back-end: <em>Controller - Service - Repository</em></li>
    <li> Validação - <em>Hibernate Validator</em> </li>
    <li> Consultas Avançadas - <em>Derived Query - Native Query</em></li>
</ol>

<h2>🛠 Tecnologias Utilizadas</h2>

<ul>
    <li>IDE IntelliJ</li>
    <li>Java 11</li>
    <li>Maven</li>
    <li><strong>Spring Web</strong></li>
    <li><strong>Spring Data JPA</strong></li>
    <li><strong>PostgreSQL Driver</strong></li>
    <li><strong>Hibernate Validator</strong></li>
    <li>Lombok</li>
    <li>Postman</li>
</ul>


<h2><a href="https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/">
Anotações de Mapeamento </a></h2>

<strong>@Entity</strong>
Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

<strong>@Table</strong>
Usada para especificar a tabela principal da entidade atualmente anotada.

<strong>@Id</strong>
Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

<strong>@GeneratedValue</strong>
Especifica que o valor do identificador de entidade é gerado automaticamente.

<strong>@Column</strong>
Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

<strong>@JoinColumn</strong>
Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

<strong>@OneToMany</strong>
Usada para especificar um relacionamento de banco de dados um-para-muitos.

<strong>@OneToOne</strong>
Usada para especificar um relacionamento de banco de dados um-para-um.

<strong>@ManyToOne</strong>
Usada para especificar um relacionamento de banco de dados muitos-para-um.

<strong>cascade</strong>
Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.

<strong>mappedBy</strong>
Indica qual é o lado inverso ou não dominante da relação.

<h2>
    




