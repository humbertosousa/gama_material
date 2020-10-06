spring.datasource.url=jdbc:mysql://localhost:3306/bdfinal?useTimezone=true&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=

# compatibilizando o conjunto de caracteres entre Hibernate e MySQL
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5Dialect

# exibir os comandos sql no console do Eclipse
spring.jpa.show_sql=true

#monitorando a conexão com o banco
spring.datasource.testWhileidle=true

#query para manter a conexão com o banco ativa
spring.datasource.validationQuery=select 1


spring.jpa.hibernate.ddl-auto=update







