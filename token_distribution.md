## Token distribution system

In order to design a token distribution system, we need to list the requirements and parameters to take into account.

#### Challenge
- create an advantage for our first users
- make it fair (not too much of a difference) for the users that come later
- make sure the peak of distribution does not come too early as it needs time for a user to get followers, to create content and to get valuation of that content.
- the pool must hold as long as the project needs time to get profitable

#### Ingredients
- a, initial value of the pool
- b, minimum duration before money income
- C(t), median of distribution amount (depends on the value distributed and the number of users)

#### Formula
We will use the lognormal distribution. (https://en.wikipedia.org/wiki/Log-normal_distribution)
More specifically the formula of density.

![density](https://github.com/nbstr/hey-technical-whitepaper/blob/master/src/lognormal_density.png?raw=true "Lognormal distribution — density")

#### Preview
![graph](https://github.com/nbstr/hey-technical-whitepaper/blob/master/src/density.png?raw=true "Lognormal distribution — density")
