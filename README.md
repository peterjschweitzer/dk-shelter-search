# Danish Shelter Availability Checker

A Python command-line tool to search for available bookable shelters in Denmark from [book.naturstyrelsen.dk](https://book.naturstyrelsen.dk).

## Features
- Search by start date and number of nights
- Filter by region
- Optionally cache place IDs for faster repeat searches
- Outputs results to CSV with GPS coordinates and region
- Can list all regions found in API
- Debug/probe mode for quick testing

## Requirements
- Python 3.8+
- `requests`
- `argparse`

Install dependencies:
```bash
pip install requests
