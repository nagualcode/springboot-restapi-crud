# CRUD em Spring Boot

## Introdução

Este projeto implementa um CRUD (Create, Read, Update, Delete) utilizando Spring Boot, uma estrutura Java para criar aplicativos rapidamente. O CRUD gerencia tutoriais, permitindo a criação, leitura, atualização e exclusão de registros.

## Estrutura do Projeto

O projeto segue uma estrutura típica de aplicativo Spring Boot, com os seguintes diretórios principais:

- **controller:** Contém as classes responsáveis por lidar com as requisições HTTP e encaminhá-las para o serviço apropriado.
- **model:** Define as entidades de dados do aplicativo, neste caso, o modelo `Tutorial`.
- **repository:** Fornece interfaces para acessar os dados do banco de dados. Aqui, a interface `TutorialRepository` estende o `JpaRepository` do Spring Data JPA.

## Tecnologias Utilizadas

O projeto utiliza as seguintes tecnologias:

- **Spring Boot:** Framework Java que facilita a criação de aplicativos.
- **Spring Data JPA:** Facilita o acesso e a manipulação de dados utilizando o Hibernate ORM.
- **MySQL:** Banco de dados relacional utilizado para armazenar os tutoriais.

## Implementação do CRUD

O CRUD é implementado nas classes do controlador, modelo e repositório:

### Controller

- `TutorialController`: Gerencia as requisições HTTP relacionadas aos tutoriais, encaminhando-as para as operações apropriadas do serviço.

### Model

- `Tutorial`: Define a estrutura de um tutorial, incluindo título, descrição e status de publicação.

### Repository

- `TutorialRepository`: Define métodos para acessar os dados dos tutoriais no banco de dados. Fornece métodos para buscar, criar, atualizar e excluir tutoriais.

## Testes e Validação

O projeto pode ser testado localmente utilizando ferramentas como curl ou Postman para enviar requisições HTTP para as URLs definidas no controlador.

## Considerações Finais

Este projeto fornece uma base sólida para construir aplicativos CRUD em Spring Boot. Ele demonstra boas práticas de desenvolvimento, incluindo a separação de responsabilidades entre as camadas do aplicativo e o uso eficaz das tecnologias Spring Boot e Spring Data JPA.

