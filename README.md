# db_connect_aws


# Configuration Guide

This document provides the necessary configuration details for setting up your application. Please ensure you have the appropriate access and permissions before proceeding.

## JDBC Configuration for Database Connection

These configurations are used to set up the JDBC connection to your MySQL database.

- **Driver Class Name**: Specify the MySQL JDBC driver.


- **JDBC URL**: Provide the URL of your database server.

- **Username**: Your database username.

- **Password**: Your database password.



## Memcached Configuration

Configure the Memcached settings for both Active and StandBy hosts.

### Active Host

- **Host**: The IP address or hostname of the active Memcached server.

- **Port**: The port number for the active Memcached server (default is 11211).


  
### StandBy Host

- **Host**: The IP address or hostname of the standby Memcached server.

- **Port**: The port number for the standby Memcached server (default is 11211).




## RabbitMQ Configuration


Details for connecting to the RabbitMQ server.

- **Address**: The address of the RabbitMQ server.

- **Port**: The port number for the RabbitMQ server (default is 5671).

- **Username**: Your RabbitMQ username.

- **Password**: Your RabbitMQ password.



## Elasticsearch Configuration

Configuration details for connecting to the Elasticsearch cluster.

- **Host**: The IP address or hostname of the Elasticsearch node.

- **Port**: The port number for the Elasticsearch node (default is 9300).

- **Cluster Name**: The name of your Elasticsearch cluster.

- **Node Name**: The name of the node within the Elasticsearch cluster.

Make sure to replace placeholders (****) with your actual configuration details. Keep this document secure and confidential.
