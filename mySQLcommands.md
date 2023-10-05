CREATE DATABASE cadastroAlunos

use cadastroAlunos

CREATE TABLE alunos (
id INT auto_increment primary Key,
     nome VARCHAR(50),
     idade VARCHAR(50),
     semestre VARCHAR(50),
     genero VARCHAR(50),
     matricula VARCHAR(50)
)

insert into  alunos(nome, idade, semestre, genero, matricula) VALUES ("Henrique", "19", "Segundo", "Masculino", "2003071001")
insert into  alunos(nome, idade, semestre, genero, matricula) VALUES ("Ana Flávia", "21", "Segundo", "Feminino", "2001150101")
insert into  alunos(nome, idade, semestre, genero, matricula) VALUES ("Vitor", "26", "Segundo", "Feminino", "1996071201")

select * from alunos LIMIT 0, 1000
