# Stockouts to Savings: Inventory Optimization for a Gas Station Network

A team project (Python) that explores fuel-level, tank, location and invoice data for a network of gas stations, analyzes how well each station manages its fuel inventory, and proposes a cost-effective inventory policy.

## Questions answered in the notebook

1. **Inventory management:** How well does each station manage its fuel inventory and order quantities? Fuel levels were plotted for every tank over time to find stations with effective practices and tanks at risk of stockouts.
2. **Order-quantity savings:** What are the potential savings from optimizing order quantities to maximize supplier discounts while keeping enough inventory? The notebook gives specific recommendations per station.
3. **Purchase timing:** What additional savings are possible if purchases were consistently made on the best-priced day in the data?
4. **New tank:** Which station benefits most from an additional tank, after subtracting the estimated cost of the tank?

The inventory policy uses the Economic Order Quantity (EOQ) and a Reorder Point (average daily consumption x lead time + safety stock).

## Data preparation

- Combined two fuel-level files (about 1.86 million readings) and merged them with the tank, location and invoice tables.
- Cleaned the merged data, handled missing values and checked for inconsistencies before analysis.


## Data

The datasets (`Fuel_Level_Part_1.csv`, `Fuel_Level_Part_2.csv`, `Tanks.csv`, `Locations.csv`, `Invoices.csv`) came with the course project and are not included in this repository because of their size. To run the notebook, place the files in the same folder as the notebook.

## Tools

Python, pandas, NumPy, Matplotlib.
