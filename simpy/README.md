# Beer Simulation Game

Simulate the beer simulation game in simpy. Assume each time step corre- sponds to one week. Consider the supply chain that is similar to what you played in in the game.
Retailer → Wholesaler → Distributor → Factory. 

- Assume a lead time that has a uniform distribution between one and four weeks. (The lead time can be one, two , three or four weeks with equal probability). This lead time exists between all entities.
- Assume the customer demand is 100k with probability 15%, 150k with probability 15% and 200k with probability 70 %. The cost of holding a case is 0.5 $ and cost of missing an order is 1$. For each entity in the chain, assume the algorithm used to calculate the demand if is similar to the newsvendor problem.

Run the game for 50 time steps.

For the above game, submit the following: -
1. Plot the weekly costs of each entity as a function of time. 
2. Plot the inventory as a function of time.
3. Plot the orders placed by each entity a function of time.

# Risk Pooling
Simulate the risk pooling game as discussed in the lecture. For this problem as well, assume that one time step corresponds to one week. Consider two scenarios. One with two warehouses catering to the two different products (A,B) and the second scenario corresponding to a centralized warehouse. 

- Assume the demand for products A and B for both warehouses in scenario one comes from normal distributions N(40,12) and N(1,1) respectively.
- Assume that the demand for the centralized warehouse in scenario 2 comes from N(80,20) and N(2, 2) respectively.
- Assume a random lead time of [1, 2] weeks. (i.e. the lead time can be 1 or 2 weeks with equal probability).
- Assume the warehouses use the (s, S) policy to manage inventory. Assume that the starting inventory for both warehouses in scenario 1 is 50 units and 2 units for products A and B respectively and for scenario 2 2, it is 80 units and 3 units respectively.

Run this scenario for 100 time steps.

1. Find out the stockout rate (fraction of time periods) in scenario 1 as well as scenario 2.
2. Compare the total holding inventory in both the scenarios over the toal time.(use the same parameters for holding cost, ordering cost and service rate as mentioned in the lecture notes. )
