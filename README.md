# KennelDatabase
Maven project, based on Spring Boot utilizing JPA for PostgreSQL management

Esse projeto baseado em SpringBoot, gerado pelo JAVA Maven, utiliza JPA para o gerenciamento de um banco de dados PostgreSQL para Criar, Ler, Atualizar e Excluir o registro de cachorros no sistema do canil.

Para rodar será necessário um banco de dados em PostgreSQL (Por padrão com nome "crud", presente no arquivo application.properties), na porta 5432, demais configurações de login do banco de dados podem ser alteradas no arquivo application.properties

Para rodar o projeto é impreterível:
*que o sistema tenha instalado o Java e configurado no PATH do sistema;
*tenha instalado e rodando o Servidor PostgreSQL condizente com as configurações do application.properties;
*que esteja presente no PATH o Maven, para rodar o projeto e na primeira inicialização baixar todas as demais dependências automaticamente.

Tendo configurado o servidor PostgreSQL no arquivo application.properties apenas é necessário rodar .\kennel_database\src\main\java\com\doge\tlp\DogeApplication.java e toda a configuração deve ser feita automaticamente pelo sistema.

É possível acessar por padrão a aplicação em localhost:8080 no navegador de preferência.
