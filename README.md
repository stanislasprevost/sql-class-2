# sql-class-2


CREATE TABLE test(user_id INT, name VARCHAR(24), age INT) ;
INSERT  INTO test VALUES (1,'Mary',22);
SELECT FROM test

stanislasprevost4@cloudshell:~$ sudo apt install squilte3
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
E: Unable to locate package squilte3
stanislasprevost4@cloudshell:~$ ^C
stanislasprevost4@cloudshell:~$ sudo apt install sqlite3
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
sqlite3 is already the newest version (3.37.2-2ubuntu0.3).
0 upgraded, 0 newly installed, 0 to remove and 9 not upgraded.
stanislasprevost4@cloudshell:~$ 
stanislasprevost4@cloudshell:~$ sqlite>CREATE TABLE test(
-bash: syntax error near unexpected token `('
stanislasprevost4@cloudshell:~$ ^C
stanislasprevost4@cloudshell:~$ sqlite>CREATE TABLE test(
-bash: syntax error near unexpected token `('
stanislasprevost4@cloudshell:~$ ^C
stanislasprevost4@cloudshell:~$ sqlite>CREATE TABLE test(
-bash: syntax error near unexpected token `('
stanislasprevost4@cloudshell:~$ sqlite3
SQLite version 3.37.2 2022-01-06 13:25:41
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite> 



