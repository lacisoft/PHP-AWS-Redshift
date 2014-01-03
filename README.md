PHP-AWS-Redshift
================

PHP - Basic library for connecting to AWS Redshift. Includes SSL cert for secure handshake via the Postgres client.


Requirements:

* PostgreSQL module for php5
* PHP 5.3 +

Ubuntu install PostgreSQL module for php5 with:

  ~> sudo aptitude install php5-pgsql
  
Library usage:

  $connection = Connection::getInstance('host_1','your_database_name');
  $connection->exec('SELECT * FROM ....');
