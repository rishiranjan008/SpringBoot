# SpringBootCQRS
This Repository is used to implimentation of CQRS design pattern of microservices. i.e. How we can use the Master DB for write operation and Slave/Read-Replica DB for read operation. 
Assumption:- Master-Slave or Master-ReadReplica DB are in sync i.e whenever there is some command( CUD ) operation executed in master DB then that changes is available in Slave or ReadReplica DB to execte read operation.
