Download Link: https://assignmentchef.com/product/solved-cs220-assignment4
<br>
In this your fourth project you write a function int maxflow(n, int *cap, int *flow, int *residual)

that takes the number n of vertices, and the three n×n arrays cap, flow, residual, which contain the edge capacities, the current flow, and space for the residual capacities matrix. Your function implements one step of the maximum flow iteration, so it constructs the residual capacities graph, based on the current flow, finds a path with positive residual capacities from vertex 0 to vertex n-1, and updates the flow along that path. It returns the amount of additional flow it sent from 0 to n-1; so when no improvement is possible, it returns 0. I will call your function many times, until you do not find any improvement; so each time you receive back that flow. You get the matrix for the residual capacities as argument, so that you do not have to allocate each time a new matrix.