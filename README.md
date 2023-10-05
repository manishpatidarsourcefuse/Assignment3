"#" 

<!-- CREATE TYPE role AS ENUM ('1', '2', '3')

CREATE TABLE customers (
    id serial PRIMARY KEY,
    name character varying(50) NOT NULL,
    website character varying(50) NOT NULL,
    address character varying(100) NOT NULL,
    role_id bigint,
 )

 INSERT INTO customers(name, website, address, role_id) VALUES ('Manish', 'www.superadmin.com', 'Indore', '1'),('Vijay', 'www.admin.com', 'Indore', '2'),('Pankaj', 'www.user.com', 'Indore', '3');

 CREATE TABLE roles (
    id role,
    name character varying(50) NOT NULL,
	description character varying(100) NOT NULL
 )

  INSERT INTO roles(id, name, description) VALUES ('1', 'user', 'He has perform operation'),('2', 'admin', 'He has autority to handle operation of user'),('3', 'superadmin', 'He has autority to handle operation of user and admin');

  SELECT customers.name, roles.name FROM customers, roles
  WHERE customers.role_id = roles.id; -->



