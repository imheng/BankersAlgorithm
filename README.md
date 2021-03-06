# Banker's Algorithm :shipit::computer:
[*The Banker's algorithm*](https://en.wikipedia.org/wiki/Banker%27s_algorithm) is a **resource allocation** and **deadlock avoidance** algorithm developed by [Edsger W. Dijkstra](https://en.wikipedia.org/wiki/Edsger_W._Dijkstra) that tests for safety by **simulating** the allocation of predetermined maximum possible amounts of all resources, and then makes an ~~"s-state"~~ **safe state** check to test for possible **deadlock conditions** for all other pending activities, before deciding whether allocation should be allowed to continue.
<p align="center"><img src="https://www.thecrazyprogrammer.com/wp-content/uploads/2016/07/Banker%E2%80%99s-Algorithm-in-C.jpg"></p>

## Okay, but how this thing works? :neutral_face::question:
When a new process enters a system, it must declare the maximum number of instances of each resource type that it may ever claim; clearly, that number may not exceed the total number of resources in the system. Also, when a process gets all its requested resources it must return them in a finite amount of time.
