<img src="E:\Programação\GitHub\dio\bootcamps\inter-frontend-developer\cadernos\curso-22\img\logo-curso-22.png" alt="https://hermes.digitalinnovation.one/courses/badge/ea03f839-894b-4652-b2f4-b80e8a0e5dfe.png" style="zoom:25%;" />

# Curso 22

>    Modelando um banco de dados na prática com SQL SERVER

>   Neste curso, você verá na prática como modelar um banco de dados com SQL SERVER, criando desde as tabelas relacionadas do projeto, até a implementação da interface.



## Aula 01 - Criando as tabelas relacionadas do projeto

### Comando Create Table e criação da primeira tabela Planetas

foi criado o banco de dados do projeto, cujo o nome é: 'EstrelaDaMorte'.

```sql
CREATE TABLE Planetas (
	IdPlaneta int NOT NULL,
    Nome varchar(50) NOT NULL,
    Rotacao float NOT NULL,
    Orbita float NOT NULL,
    Diametro float NOT NULL,
    Clima varchar(50) NOT NULL,
    Populacao int NOT NULL,
)
GO
ALTER TABLE Planetas ADD CONSTAINT PK_Planetas 	PRIMARY KEY (IdPlaneta);

```

### Criação da tabela Naves e a Pilotos
