# Service Order Control System for a Mechanical Workshop

 ### 🎯 Challenge Title:

Creating a conceptual scheme for the context of a mechanic's workshop.

### 💭 Challenge Origin:

Challenge proposed by Professor **__Juliana Mascarenhas__** for the project challenge "Building a conceptual scheme for a database" on the **__DIO__** platform.

### 💭 Narrative:

Service order execution control and management system in a mechanic's workshop
Customers take vehicles to the mechanic's workshop to be repaired or to undergo periodic inspections
Each vehicle is assigned to a team of mechanics who identify the services to be performed and fill out a service order with a delivery date.
The service order is used to calculate the value of each service.
The customer authorizes or denies the execution of the services.
The mechanic validates and performs the services.
Mechanics have a code, name, address and specialty.
Each service order has: number, date of issue, a value, status and a date for completion of the work.

### ✅ What is contained in the schema:

:black_square_button: Entities

:key: Primary Keys

:white_circle: Simple Attributes

:large_blue_diamond: Relationships

( :one: , :one: ) Cardinality

### ✅ Concepts used:

In this small project, Inheritance concepts were used, which we can observe when viewing the "*Person*" entity that has generic attributes, thus avoiding information redundancy. Specialization concept, when dividing the "*Mechanic*" entity from the "*Customer*" entity, each with its own specific attributes.
Each entity has its own identifier, thus allowing a flexible model.


**__Created by Leonardo Lindoso 💻__**

Titulo do Desafio: 


Criando um esquema conceitual para o contexto de uma oficina mecânica.



Origem do Desafio: 


Desafio proposto pela professora Juliana Mascarenhas para o desafio de projeto "Construindo um esquema conceitual para banco de Dados" na plataforma DIO.  



Narrativa:
 
Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica

Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas

Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.

A partir da OS, calcula-se o valor de cada serviço.

O cliente autoriza ou não a execução dos serviços.

O mecânico valida e executa os serviços.

Os mecânicos possuem código, nome, endereço e especialidade.

Cada OS possui: número, data de emissão, um valor, status e uma data para conclusão dos trabalhos.



O que está contido no esquema:


Entidades
Chaves Primarias
Atributos simples 
Relacionamentos
Cardinalidade


Conceitos utilizados:


Neste pequeno projeto, foram utilizados conceitos de Herança, onde podemos observa-los ao visualizar a entidade "Pessoa" que possui atributos genéricos, desta forma evitamos redundância de informações. Conceito de especialização, ao dividirmos a entidade "Mecânico" da entidade "Cliente", cada qual com seus atributos específicos.

Cada entidade possui seu próprio identificador, permitindo assim, um modelo flexível.
