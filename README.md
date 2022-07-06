# Extending-Minibase-to-support-RDBMS-functionalities

Project contributitons:

Rutva Krishnakant Patel
Riya Jignesh Brahmbhatt  
Venkata Satya Sai Dheeraj 
Akula Nithya Vardhan Reddy Veerati 
Haard Mehta
Karthik Nishant Sekhar

In phase 1, we mainly studied the existing codebase of minibase and understood it thoroughly.

In phase 2, we have worked towards implementing various methods to compute the skylines on a given dataset. There are 3 methods to design the skyline, namely- Nested Loop Skylines, Block-Nested Loop Skylines, Sort-First Skylines. Later, we used sorted B+ Trees to implement the skyline functions on the data. In the end, we conduct a performance analysis on the given methods.

In phase 3 for the project, we have further extended Minibase to include relational database management system functionalities such as GroupBy on various aggregation functions, Joins using different algorithms, TopKJoins using the naive approach as well as the NRA algorithm. Minibase only supported unclustered BTree indexes. We have further extended it to support clustered BTree index as well as clustered and unclustered hash index. Finally, we have integrated all the functionalities of phase 2 (skyline computation) as well as phase 3 into a query interface as a part of the last task. Lastly, we have tested all the functionalities on the data files provided and analysed the number of reads and writes. This phase includes the implementation of a persistent database.
