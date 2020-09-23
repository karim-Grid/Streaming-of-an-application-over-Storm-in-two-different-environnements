# Introduction
In this project we have explored some data streaming  and data science techniques to prove the following assumption:  Streaming the applications in the Edge+Cloud is much better than streaming them only in the Cloud. The supervisor has given me the opportunity to reserve nodes in different locations to simulate first the Cloud environnement: Powerful nodes in terms of hardware and also to simulate the Edge+Cloud environnement where we mitigate some powerful nodes to be the cloud and other powerless nodes to be the Edge. We have used this reserved nodes to install Storm and then to stream one prototype generator application named : NAMB over the Storm installed. At the end of the streaming, we have retrieved the log files that contain a list of tuples generated in the reserved nodes to parse them and then calculate the throughput and the latency of the streaming of the application NAMB over Storm first in the Cloud only and then in the Edge+Cloud to compare them and check if our assumption is valid or not.
# Tools:
- Grid5000 : is a large-scale and flexible testbed for experiment-driven research in all areas of computer science, with a focus on parallel and distributed computing including Cloud, HPC and Big Data and AI.it provides access to a large amount of resources: 15000 cores, 800 compute-nodes grouped in homogeneous clusters, and featuring various technologies: PMEM, GPU, SSD, NVMe, 10G and 25G Ethernet, Infiniband, Omni-Path.
- Storm : Apache Storm is a distributed flow processing calculation framework. It uses custom-created "spouts" and "bolts" to define information sources and manipulations for batch processing and continuous data distribution.
- NAMB : is a prototype application generator that we have executed above Storm in our experimentation's.
# Requirements:
 - Pandas
 - Grid5000 account
 # Results : 
  After accomplishing our experimentation's we have found that the processing of the applications in the Fog+Cloud environnement is efficient in term of processing throughput and latency compared to the Cloud environnement.
