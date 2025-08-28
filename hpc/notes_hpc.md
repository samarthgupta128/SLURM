#serial computing vs parallel computing

what do we mean by performance:- 

for scientific and technical programming use flops(floating point operations per second)
now mordern computers measure in PFLOPs

similarly other disciplines have their own performance methods like frames per second, database acceses per second


---------------------------------------------------------------------------------
#HPC
* not a gui based environment
* share the system with many users
* resources more tighly monitored and controlled
**disk quotas
** cpu usage

![Alt text](pictures/hpc%20system.png)tigh


----------------------------------------------------------------------------------------
#parallel computing

##tightly coupled problem :- when the complex problem divided into parallel tasks and the cores working parallely need to communicate frequently communicate with each other 

##embarissing parallel problems :- requires almost no communications between parallel occuring tasks

#geometric decomposition
*splitting the problem up does have an associated cost
**namely communication between processors
**Need to carefully consider granualarity
**Aim to minimise communications and maximise computation

![Alt](pictures/geometricdecom.png)




