# Grocery Bill Calculator (Java)

## Overview
This program calculates a family's weekly and monthly grocery expenses based on four weeks of input. It also applies a coupon discount and compares results with and without the discount.

## Features
- Prompts user for a coupon amount (decimal format)
- Defaults coupon to 15% if input is invalid (≤ 0 or > 1)
- Collects grocery bills for 4 weeks
- Calculates:
  - Monthly total (without coupon)
  - Weekly average (without coupon)
  - Monthly total (with coupon)
  - Weekly average (with coupon)

## How It Works
1. User enters a coupon value (example: 0.15 for 15%)
2. Program asks for grocery bills for weeks 1–4
3. Program calculates totals and averages
4. Results are displayed with and without coupon applied

## How to Run

### Compile:
javac GroceryCalculator.java

### Run:
java GroceryCalculator

## Example Input
Coupon: 0.15  
Week 1: 120  
Week 2: 135  
Week 3: 110  
Week 4: 125  

## Example Output
Without Coupon:
Monthly Total: $490.00  
Weekly Average: $122.50  

With Coupon:
Monthly Total: $416.50  
Weekly Average: $104.13  

## Concepts Used
- Variables and data types
- User input with Scanner
- If/else validation
- Arithmetic calculations
- Console output formatting

## Author
Samantha Widell
