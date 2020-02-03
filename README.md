# Test Case Metrics Generator
A simple application that receives as input the test requirements and a set of test paths, to create the following test case metrics:
* AvgPathLength
* Hasloop
* AvgCountLoop
* CountReqPPCCovered
* CountReqECCovered
* PrimePathCoverage
* EdgeCoverage


We developed this tool to generate the defined metrics to build the dataset detailed in the paper "A dataset based on two graph coverage criteria: prime-path and edge coverage"

An important note is that this tool can be used to generate the specified test case metrics for each test method or test path (e.g.,  an assert statement).
