
# Homework Assignment 1

Submission Deadline: February 12, 2024


#### Capacity (GB) 

We can see that because we have two identical nodes we have the same capacities for their DRAM capacity which is 65.7 GB and the local disk capacity which is 238.5 GB

#### Latency (us)

From the measurements i did i can observe that the local DRAM has the lowest value of just 0.12 us. We can also see that the latency of the Rack DRAM is lower than the Rack Disk. 
For both these values i added the network latency with the the local disk latency to calculate the rack disk latency and the network latency with the local dram latency to calculate the
rack dram latency.

#### Bandwidth (MB/s)

Now if we go and see the results about the bandwidth we can see that there is a really big value regarding the Local DRAM bandwidth which is 34731 MB/S and a lot bigger than the others.
I used the "fio" command to measure the disk Bandwidth which is 174.322 MB/s. To calculate the Rack DRAM bandwidth which is basically the network bandwidth i ran the iperf command trying to find the network bottleneck which seemed to be 526.25 MB/S.

#### Conclusion

As a conclusion i can say that it is much easier and efficient to reach remote DRAMs than local disks since they have much bigger bandwidths thanks to the network being our bottleneck.






