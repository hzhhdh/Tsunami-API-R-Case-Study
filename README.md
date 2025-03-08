# Tsunami API Case Study using R  

## Overview  
This repository contains **five use cases** demonstrating how to use PARSIQ's Tsunami API. The study showcases how to interact with the Tsunami API for real-time blockchain data analysis, fetch transaction details, and process data within an R environment.  

## Features  
- Fetch real-time blockchain transaction data using the **PARSIQ Tsunami API**.  
- Process and analyze blockchain data with **R**.  
- Visualize and interpret results using **R packages**.  

## Prerequisites  
Before running the scripts, ensure you have the following installed:  

- **R (>= 4.0)**  
- **RStudio** (optional but recommended)  
- **Required R packages:**  
  - `httr`  
  - `jsonlite`  
  - `ggplot2`  
  - `dplyr`  

## Installation  
Clone the repository:  
```sh
git clone https://github.com/hzhhdh/tsunami-api-r-case-study.git
cd tsunami-api-r-case-study
```
Install required R packages:
```
install.packages(c("httr", "jsonlite", "ggplot2", "dplyr"))
```

## Usage
Set up your PARSIQ API key and paste it in 'Bearer' in the script.
Run the R script to fetch blockchain data and analyze it.
Explore and visualize the results.

## Use cases
1. Active Multichain Bridge Users
Identifying active users who used the Multichain bridge to transfer PRQ tokens from BSC to Ethereum in January 2023.

2. Lido Protocol Interaction Frequency
Analyzing the frequency of unique addresses interacting with Lido Protocol in January 2023.

3. Gas Fees Before and After Shapella Upgrade
Comparing Ethereum gas fees before and after the Shapella upgrade.

4. Forecasting Ethereum Block Gas Fees
Predicting future gas fees for an Ethereum block.

5. IQ Protocol Rentals
Exploring how users can leverage on-chain data to maximize their IQ Protocol asset rentals.

## Contribution
Since PARSIQ has discontinued access to the Tsunami API for new users, further contributions to this project are not necessary. However, feel free to explore the existing code or fork the repository for personal use.

## License
This project is just for fun! Feel free to use it however you like, but no guarantees that it works!

## Contact
For any inquiries or discussions, open an issue in the repository.
