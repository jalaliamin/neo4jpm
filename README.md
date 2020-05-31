﻿# neo4jpm

This repository stores the evaluation data for the use of neo4j for process mining. To reproduce the result:

1. unzip the data in the import folder and import them into neo4j as batch.
2. start the neo4j
3. Use cypher to query the DFG

If you like to repeat the evaluations for scaling, you need to run pm4py and neo4j in a docker container and assign values for CPU. You need to change the value many times and run the containers to collect data. Then you can plot the result.
