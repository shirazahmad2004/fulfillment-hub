# Fulfillment Hub

A simple order-fulfillment tool for a small e-commerce business (XYZ). It replaces spreadsheets and shared folders with one screen per job.

## What it solves
- Order status at a glance (Board)
- Priority orders and deadlines (Board, Office)
- Wrong product or variant shipped (Warehouse: scan check)
- Missing stock and stock in the second warehouse (Warehouse)
- Missed courier pickups (Dispatch)
- Problems handled informally (Issues log)

## Screens
- **Board:** owner view with KPIs, stages, and "Needs attention" filter
- **Office:** create labels, courier pre-selected (fastest for priority, cheapest for others)
- **Warehouse:** one order at a time, bin numbers, scan check, "Can't find it", move stock from Warehouse 2
- **Dispatch:** courier-wise pickup countdown, missed pickup handling
- **Issues:** log and resolve problems

## Run locally
No install and no build step.
1. Download or clone this repo.
2. Open `index.html` in any modern browser (double-click it).

## Demo tips
- Header button **+30 min** moves the clock forward so delays and missed pickups appear.
- Header button **Reset demo** restores the sample data.
- In the Warehouse tab, type the code shown under an item name and press Enter to verify it. A wrong code is blocked.
- Try ORD-1043 (needs stock moved from Warehouse 2).

## Notes
- All data is sample data kept in browser memory and resets on refresh.
- Scanning is simulated by typing the code.
- Built as a single HTML file with plain JavaScript, no dependencies.
