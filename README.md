# Genetic Algorithm for Delivery Optimization

This project maximizes profit for a delivery service with:
- **10 vehicles** (each max 800 kg).
- **Packages** (weight, profit, deadline).
- **Penalty** for overdue packages (deadline < 0).

## How It Works
1. **Data Loading**: Reads `lagerstatus.csv`, calculates penalty for late packages.  
2. **Allocation**: Scores packages by profit, weight, lateness, then places them in vehicles.  
3. **Genetic Algorithm**: Tries different allocations, mutates solutions, and stops when no improvement is found.  
4. **Results**: Shows best fitness, leftover packages, and saves final allocation in CSV files.
