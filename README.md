# Spread-Of-Malaria

### Infected populations are found by using foward Euler's method ###

            
Infected humans are found by adding the number of humans that get infected
in the particular time step subtracting those who recover in this time step
            
            
Infected mosquitoes are found by adding the number of mosquitoes that get infected
by humans in the particular time step subtracting those who die


**Infected humans:**</br>(Probability of person getting bitten * Susceptible population * probability of infection transfer) - Rate of Recovered humans

**Infected Mosquitoes:**</br>(Probability of mosquito biting a person * probability of transmission from human to mosquito) - the rate of death of mosquitoes
