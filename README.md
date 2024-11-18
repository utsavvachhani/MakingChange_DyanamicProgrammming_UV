
# Making Change - Dynamic Programming  

This repository contains a C program that demonstrates the **Making Change problem** using the **Dynamic Programming** approach. The program calculates the minimum number of coins required to achieve a given target amount with a specified set of coin denominations.  

## Problem Overview  

The **Making Change problem** is a classic optimization problem in computer science. Given a target amount and a set of coin denominations, the objective is to minimize the number of coins needed to make up the target amount.  

### Key Features:  
- Implements an efficient **Dynamic Programming** solution.  
- Handles a variety of coin denominations.  
- Provides clear output for the minimum number of coins required.  
- Returns `-1` if it's impossible to form the target amount with the given denominations.  

### Example:  
#### Input:  
- **Coin Denominations:** [1, 5, 10, 25]  
- **Target Amount:** 47  

#### Output:  
- Minimum Coins Required: 5  

## How It Works  

1. The program uses a DP array where each index represents the minimum number of coins required to form that value.  
2. It iterates over each coin denomination and updates the DP array accordingly.  
3. After processing all denominations, the DP array contains the solution for the target amount.  

## Usage  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/utsavvachhani/MakingChange_DyanamicProgrammming.git  
   ```  
2. Compile the C program using a C compiler, e.g., GCC:  
   ```bash  
   gcc -o making_change making_change.c  
   ```  
3. Run the program:  
   ```bash  
   ./making_change  
   ```  
4. Follow the prompts to enter your coin denominations and target amount.  

## Repository Link  

[GitHub Repository: Making Change - Dynamic Programming](https://github.com/utsavvachhani/MakingChange_DyanamicProgrammming)  

## Why Use Dynamic Programming?  

Dynamic Programming ensures:  
- **Optimal Substructure:** The problem is broken down into smaller overlapping subproblems.  
- **Efficiency:** By storing intermediate results, the solution avoids redundant computations, ensuring a faster runtime.  

---
