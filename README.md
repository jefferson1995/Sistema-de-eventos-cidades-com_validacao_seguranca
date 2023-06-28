# bds04_validacao_seguranca

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/jefferson1995/bds04_validacao_seguranca/blob/main/LICENSE.txt) 

# Sobre o projeto

Este é um sistema de eventos e cidades com uma relação N-1 entre eles. 

Neste sistema, somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). Usuários CLIENT podem também inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários ADMIN.

Validações de City:
-	Nome não pode ser vazio

Validações de Event:
-	Nome não pode ser vazio
-	Data não pode ser passada
-	Cidade não pode ser nula


## Modelo conceitual
![Modelo Conceitual](https://github.com/jefferson1995/Assets/raw/main/bds04_validacao_seguranca/diagrama.png)


# Tecnologias utilizadas
## Back end

- Java
- Spring Boot
- Sprring security
- OAuth2
- JWT refresh token
- Junit 5
- TDD
- JPA / Hibernate
- Maven
- H2 banco de dados


# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/jefferson1995/bds04_validacao_seguranca

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw/wrapper spring-boot:run
```



# Autor

Jefferson Barbosa dos Santos

https://www.linkedin.com/in/jefferson-barbosa-225349149/
