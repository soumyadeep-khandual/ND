<link href="assets/styles.css" rel="stylesheet"></link>

# Scenarios for Network Design 

## Scenario: High-Demand Surge 

- **Change:** Increase demand by 30% for selected high-growth demand locations (e.g., metro cities). 

- **Goal:** Test if the current facility network and capacities can meet increased demand while maximizing profit. 

## Scenario: New Facility Entry 

- **Change:** Introduce a new low-cost manufacturing facility in the “Facility Master” sheet. 

- **Goal:** Evaluate its impact on total profit when added to the distribution network. 

## Scenario: Regional Capacity Constraint 

- **Change:** Reduce capacity of a key facility in the “Facility Capacities” sheet (e.g., due to maintenance). 

- **Goal:** Analyze how the network adapts and where profit is lost or gained due to re-routing. 

## Scenario: Variable Service Level Requirements 

- **Change:** Modify “Default Service Level” sheet to increase service levels for premium demand locations and reduce for others. 

- **Goal:** Test profit trade-off between service level adherence and logistics costs. 

## Scenario: Product Portfolio Change 

- **Change:** Add or remove SKUs from the “Product Master” and adjust corresponding entries in distribution and delivery sheets. 

- **Goal:** Understand profit impact from reducing product variety or adding a new high-margin product. 

## Scenario: Transportation Cost Spike 

- **Change:** Increase transport costs in “Product Distribution” and “Product Delivery” sheets for certain lanes. 

- **Goal:** Observe which facilities become suboptimal and if profit can still be maintained. 

## Scenario: Disruption Recovery 

- **Change:** Temporarily disable one major facility in “Facility Master” (simulate natural disaster or disruption). 

- **Goal:** Measure profit loss and the effectiveness of alternate sourcing strategies. 

## Scenario: Dual Sourcing Policy 

- **Change:** Impose policy to source each product from at least two facilities to reduce risk. 

- **Goal:** Understand how redundancy in sourcing impacts profit. 

## Scenario: Capacity Expansion Investment Option 

- **Change:** Provide an option to expand capacity at selected facilities for a fixed investment cost. 

- **Goal:** Evaluate if investment returns are positive under various demand patterns. 

## Scenario: Facility Grouping Restriction 

- **Change:** Assign specific products to facility groups using “Facility Group Master” and “Facility Group Details.” 

- **Goal:** Analyze how limiting product processing to groups of facilities affects network profitability. 

## Scenario: Inflation
- **Goal:** Analyze impact of inflation
- **Solution:** update plan parameters to add :
    - Cost Inflation Rate
    - Transport Cost Inflation Rate
    - NPV Rate	
    - etc