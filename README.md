# Skincare Website Scraper
## Overview
This project is a web scraper designed to extract product data from four different skincare e-commerce websites. The collected data includes Product Name, Product Description, Product Info, Product Variation Data (if any), Product Image URL, Product Benefits, and Instructions/Application info.
## Websites to Scrape
- [SkinBetter](https://www.skinbetter.com/)
- [Alastin](https://alastin.com/)
- [Skinceuticals](https://www.skinceuticals.com/)
- [Revision Skincare](https://revisionskincare.com/)
## Getting Started
### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/skincare-scraper.git
```
2. Navigate to the project directory:
```bash
cd skincare-scraper
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
### Usage
Run the main script:
```bash
python scraper.py
```
The script will save the collected data at checkpoints to minimize the risk of data loss in case of interruptions.
## Data Structure
The scraped data will be stored in a CSV file named `skincare_data.csv`. Each row corresponds to a product, and columns include Product Name, Product Description, Product Info, Product Variation Data, Product Image URL, Product Benefits, and Instructions/Application info.

# Work Outline

## Overview

This project aims to scrape product data from four skincare e-commerce websites. The following tasks outline the step-by-step process for achieving this goal.

## Tasks

### 1. Identify the Structure
- [ ] Understand the structure of each website, including how product information is organized on the pages.

### 2. Scrape Data
   - [ ] Implement the scraping logic to collect all product URLs.
   - [ ] Implement the scraping logic to collect Product Name.
   - [ ] Implement the scraping logic to collect Description.
   - [ ]  Implement the scraping logic to collect Product Info.
   - [ ]  Implement the scraping logic to collect Variation Data.
   - [ ]  Implement the scraping logic to collect Image URL.
   - [ ]  Implement the scraping logic to collect Benefits.
   - [ ]  Implement the scraping logic to collect Instructions.

### 3. Organize Data
   - [ ]  Store the collected data in a CSV format.

### 4. Testing
   - [ ] Test your scraping script to ensure it works correctly and captures the necessary information.

### 5. Save Data at Checkpoints
   - [ ] Implement checkpoints to periodically save the collected data.