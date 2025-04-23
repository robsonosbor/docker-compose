
# Docker Compose - Apache, PHP e MySQL

Este projeto fornece um ambiente de desenvolvimento local utilizando Docker Compose, configurando um contêiner com Apache HTTP Server, PHP e MySQL. É ideal para testes e desenvolvimento de aplicações PHP que necessitam de um servidor web e banco de dados.

## 📂 Estrutura do Projeto

- `compose.yml`: Arquivo de configuração do Docker Compose que define os serviços necessários.
- `index.php`: Arquivo PHP de exemplo para testar o ambiente.
- `uploads.ini`: Arquivo de configuração para ajustes no PHP, como limites de upload.

## 🚀 Como Utilizar

### Pré-requisitos

- [Docker](https://www.docker.com/) instalado.
- [Docker Compose](https://docs.docker.com/compose/) instalado.

### Passos

1. Clone este repositório:
   ```bash
   git clone https://github.com/robsonosbor/docker-compose.git
   cd docker-compose
   ```

2. Inicie os serviços com o Docker Compose:
   ```bash
   docker-compose up -d
   ```

3. Acesse a aplicação no navegador:
   ```
   http://localhost
   ```

## ⚙️ Configurações

- **Apache**: Servidor HTTP para servir a aplicação PHP.
- **PHP**: Linguagem de programação para desenvolvimento web.
- **MySQL**: Sistema de gerenciamento de banco de dados relacional.
- **uploads.ini**: Arquivo para configurar parâmetros do PHP, como `upload_max_filesize` e `post_max_size`.

## 🐳 Comandos Úteis

- Parar os serviços:
  ```bash
  docker-compose down
  ```

- Ver logs dos serviços:
  ```bash
  docker-compose logs -f
  ```

- Acessar o contêiner do PHP:
  ```bash
  docker exec -it <nome_do_container_php> bash
  ```

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 📬 Contato

Para dúvidas ou sugestões, entre em contato com [Robson Osbor](https://github.com/robsonosbor).
