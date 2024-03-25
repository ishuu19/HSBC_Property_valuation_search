# HSBC Property Valuation API

## Description

This Python script fetches the valuation of a property using the HSBC Property Valuation API. The API takes parameters such as zone ID, district ID, estate ID, block ID, floor, and flat to determine the valuation of the property.

## Functionality

- The `get_hsbc_valuation` function takes the following parameters:
  - `zoneId`: Zone ID of the property.
  - `districtId`: District ID of the property.
  - `estateId`: Estate ID of the property.
  - `blockId`: Block ID of the property.
  - `floor`: Floor number of the property.
  - `flat`: Flat number of the property.
- It sends a POST request to the HSBC Property Valuation API with the provided parameters.
- The response contains the valuation of the property, which is printed in the console.

## Requirements

- Python 3.x
- requests library

## Usage

- Ensure Python and the requests library are installed.
- Call the `get_hsbc_valuation` function with the required parameters (zoneId, districtId, estateId, blockId, floor, flat) to fetch the property valuation.

## Example

```python
get_hsbc_valuation("2", "22", "693", "nil,6185,nil", "9", "D")
```

## Output
```python
The Valuation of the property in Flat D, 9/F, Block/Tower 2, Bailey Garden, Hung Hom, Kowloon is: $6,340,000 HKD
```

## Author Name
Anayed Hossain Eshan
