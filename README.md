docker pull mysql:5.7

docker run --name mysql5 -e MYSQL_ROOT_PASSWORD=admin -p 3306:3306 -d mysql:5.7

pip install flask

pip install flask-mysql

git clone https://github.com/stigmandroid/atividadecontinua1.git

docker ps (Precisar pegar o ID do container)

docker exec -it (ID do container) /bin/bash

mysql -uroot -p

digitar a senha do banco de dados = admin;

create schema nome do banco de dados = teste;

use teste;

CREATE TABLE tbl_aluno( aluno_id BIGINT NOT NULL AUTO_INCREMENT, aluno_name VARCHAR(45) NULL, aluno_cpf VARCHAR(45) NULL, aluno_endereco VARCHAR(45) NULL, PRIMARY KEY (aluno_id));

exit

exit

cd até o diretório do arquivo.py

python3 app.py
 
