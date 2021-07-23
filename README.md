# infoSec - cybersec Notes

## SQL Injection

- find the structure where your payload is fitting

	> ' UNION YOUR_NEW_QUERY --
	- Union merges the resultSet of new select statement to old one.

#### Things to do after SQL injection discovery
- Find the DB version (e.g for Oracle DB)
> SELECT * FROM V$version 

