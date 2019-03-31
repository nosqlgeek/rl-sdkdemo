# SDK Demo for RedisConf 19

## Demo outline

### Clustered Database with Proxy

* Creation of a clustered database in Redis Enterprise
* Standard client example with ‘redis-py’
* Show a database’s sharding expression
* Explain MULTI EXEC on a clustered database
* Explain LUA scripts on a clustered database 

### Sentinel Discovery

* Show how to use the Sentinel Discovery Service

### OSS Cluster

* Creation of an ‘OSS Cluster API’ enabled database in Redis Enterprise
* Show and explain CLUSTER SLOTS
* How ‘redis-cli’ works with OSS Cluster databases
* DBSIZE via ‘redis-cli’ on an OSS Cluster database
* Give a Cluster API example with ‘redis-py-cluster’

# How to use

1. Bring up an 'rl-docker' environment: https://github.com/nosqlgeek/rl-docker
2. Start the Jupyter server: `cd jupyter; ./start_jupyter.bash`
3. Connect to the Jupyter server: http://localhost:8080
4. Enter the token which you can find on the command line after the line 'Currently running servers:'
5. Upload the file 'RedisClustering' which can be found under the 'python' folder here
6. Follow the instructions in the workbook
