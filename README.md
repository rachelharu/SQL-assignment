# SQL-assignment
bootcamp assignment to introduce students to SQL 


#what I learned

#create a table and insert data:
CREATE TABLE products (
 id INT NOT NULL,
 name STRING,
 price MONEY,
 PRIMARY KEY (id)
)

INSERT INTO products (id, name)
VALUES(2, "Pencil")


#how to select pieces of data based on certain criteria: 
SELECT name, price * FROM 'products'; 
WHERE id=1 

#how to update values: 
UPDATE products
SET price = 0.80
WHERE id=2


ALTER TABLE products 
ADD stock INT


UPDATE products 
SET stock = 12
WHERE id = 2


#how to delete: 
DELETE FROM products 
Where id = 2 
