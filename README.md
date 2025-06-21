# Auth Server - Spring Authorization Server

- Este projeto implementa um servidor de autenticação OAuth2 usando **Spring Authorization Server**, responsável pela emissão e validação de tokens JWT.
- Tecnologias para implementação do Auth Server: Keycloak, Okkta, Google, Aws, etc

## 🔐 Funcionalidades

- Emissão de tokens OAuth2 (Password, Client Credentials, Authorization Code).
- Endpoints para descoberta e chave pública (JWK).
- Integração com banco de dados para autenticação de usuários.
- Pode ser usado com o API Gateway para validação de tokens.

## 🚫 Importante

- **Não deve estar atrás do API Gateway.**
- **Não deve ter rota registrada no API Gateway.**
- Deve ser acessível diretamente por apps frontend ou serviços confiáveis.

## 🧭 Requisitos

- Java 17+
- Spring Boot 3.1+
- Maven 3.9+

## O Keycloack como Auth Server 

### Configurando acesso ao api-gateway pelo keycloak
https://github.com/marcellopedrosa/api-gateway-with-keycloak/
