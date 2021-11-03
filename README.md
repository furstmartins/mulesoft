# POC usando a tecnologia mulesoft
repositorio para salvar o projeto de integração teste contendo os seguintes recursos

> POST /orders

> GET /orders/{idOrder}

> GET /orders/{idOrder}/deliveryAddresses

> GET /orders/{idOrder}/products

O recurso *POST /orders* foi implementado para resolver a questão proposta pelo diagrama de sequência abaixo

![image](https://user-images.githubusercontent.com/3932294/139979547-adabc3ee-79d5-49a2-acf2-b3ce78768f76.png)

Já os demais recursos buscam na base de dados MySql o registro *(order)* salvo e/ou suas especializações (*deliveryAddresses* e *products*). O diagrama de sequência abaixo é do recurso *GET /orders/{idOrder}* mas os demais recursos seguem o mesmo padrão

![image](https://user-images.githubusercontent.com/3932294/139982465-540bc974-46dc-492b-9ad6-589c44bb5fc4.png)
