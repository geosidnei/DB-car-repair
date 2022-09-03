# DB-car-repair

Narrativa (Oficina mecânica de automóveis):

* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica;

* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas;

* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.

* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;

* O valor de cada peça também comporá a OS;

* O cliente autoriza a execução dos serviços;

* A mesmq equipe avalia e executa os serviços;

* Os mecânicos possuem código, nome, endereço e especialidade;

* Cada OS possui:
    - número;
    - data de emissão;
    - valor; 
    - status;
    - data prevista de conclusão do reparo.

* Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS;

* Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.


![automecanica](https://github.com/geosidnei/DB-ecommerce-DIO/blob/main/e-commerce-refinado.png)

(Com base no modelo de Máximo Rodrigues e nos comentários de Danilo Saraiva)

