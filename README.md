# Simple Implementation of Apriori Algorithm

## Description

This repository contains a simple implementation of Apriori association rule mining algorithm.
It also contains a sample tiny dataset in ***sample_data.txt***. You can simply build or use 
existing dataset in the same format: each line contains a set of items (stringS) separated by a space.
Each line represents a transaction and the dataset can contain an arbitrary number of transactions. 
And each transacation can contain an arbitrary number of elements.

This version of Apriori does not always generate rules until it reaches a N-itemset. However, you must 
explicitly provide n as an argument to the ModifiedApriori function. You must as well pass the minimum support
to this function.

The output would be the top m rules, you must specify the number of rules to be printed by passing the 
value of m to the RuleGeneration function
