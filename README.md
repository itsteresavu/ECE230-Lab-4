# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

|Item|Description|Value|
|-|-|-|
|Summary Answers|Your writings about what you learned in this lab.|25%|
|Question 1|Your answers to the question|25%|
|Question 2|Your answers to the question|25%|
|Question 3|Your answers to the question|25%|

## Lab Summary

Summarize your learnings from the lab here.

We learned how to use k-maps, how to make min terms and max terms. We got to experiment more with Vivado. We practiced how to convert truth tables into SOP and POS forms. The lab showed us how grouping 1s or 0s in KMaps can help reduce the number of logic terms. We also learned how to implement naive into Verilog and verify that all code/versions were able to produce the same output.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges? 

Groups can go across edges because the KMaps wraps around. The edges are actually next to each other logically, so we can group them to simplify the equation more.



### Why are the names Sum of Products and Products of Sums? 

Sum of products means AND terms are added together with OR. Products of Sums means OR terms are multiplied together with AND. The names are to describe how the terms are combined.



### Open the test.v file – how are we able to check that the signals match using XOR?

XOR checks if two signals are different. If the XOR result is 0, then the signals match. if it's a 1, then they don't match.

