

# ecommerce

Ola! Seja bem vindo ao meu projeto de webservice com springboot e jpa com hibernate.
Este projeto representa um pequeno domínio de negócio de um ecommerce.
Nele relacionamos o usuário com um pedido, e este com um produto.

Link do serviço:
https://yuji-javaspringboot1.herokuapp.com/

Esse projeto possui 3 camadas de backend, sendo,
a camada de (1)resources que farão o papel dos controladores rest e eles recebem as requisições e 
respondem de acordo com o comportamento do sistema.
Também temos a camada de (2)serviços e a camada de (3)acesso a dados, e elas conversam com as entidades.

Esse projeto foi construido na linguagem Java em conjunto com o Spring framekwork. 
Apache tomcat como o container da web para executar a aplicação.
O mavem como gerenciador de dependências.
O PostgreSQL como banco de dados.
E por fim o Heroku como servidor.

É possível adicionar Usuários nesta API pelo Postman através do link do projeto ( https://yuji-javaspringboot1.herokuapp.com/ ) e pelo método POST
e adicionando no endpoint "/users" os atributos "name", "email" e "phone".


![modelo de dominio](https://user-images.githubusercontent.com/57396516/169913980-6388c3c1-cbb9-4691-b2c2-b70c6ac1f3d3.png)
![relacionamento](https://user-images.githubusercontent.com/57396516/169913983-826c35d2-be09-4db0-bf4b-97b8fa8678e9.png)
