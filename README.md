# acMark
acMark: General Generator for Attributed Graph with Community Structure

## Requirements
- numpy >= 1.14.5
- scipy >= 1.1.0

## Example
> $ python acmark.py
'test.mat' is generated by the example.

## Usage
In a python code,
> import acmark  
acmark.acmark(output='test.mat',n=1000,m=4000,d=100)

Other parameters are described below:

## Parameter (default)
outpath : path to output file (.mat)  
n (=1000) : number of nodes  
m (=4000) : number of edges  
d (=100)  : number of attributes  
k (=5)    : number of clusters  
k2 (=10)  : number of clusters for attributes  
