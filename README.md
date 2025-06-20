# Bellman-Ford Algorithm for Forex Arbitrage Detection

This is a quick experiment in using the Bellman Ford Algorithm to detect an arbitrage opportunity in the forex market. 

This algorithm finds the shortest path in a graph, even if a negative cycle exists.

By taking the exchange rates, and then taking the inverse logarithm (-log(ex1 * ex2)) or (log(1/(ex1 * ex2))) we take the heaviest path (The most profitable) and turn it into the shortest path. If the shortest path has a total weight of less than 1, then the original path was profitable, and exchanging the currencies in that order would create a profit. 

## List of Currencies Used

- Kuwaiti Dinar (KWD)
- Bahraini Dinar (BHD)
- Omani Rial (OMR)
- Jordanian Dinar (JOD)
- British Pound Sterling (GBP)
- Gibraltar Pound (GIP)
- Falkland Islands Pound (FKP)
- Cayman Islands Dollar (KYD)
- Swiss Franc (CHF)
- Euro (EUR)
- United States Dollar (USD)
- Singapore Dollar (SGD)
- Brunei Dollar (BND)
- Canadian Dollar (CAD)
- Australian Dollar (AUD)
- Azerbaijani Manat (AZN)
- New Zealand Dollar (NZD)
- Aruban Florin (AWG)
- Bulgarian Lev (BGN)
- Bosnia and Herzegovina convertible mark (BAM)
- Belize dollar (BZD)
- Barbadian dollar (BBD)
- Fijian Dollar (FJD)
- Tongan pa'anga (TOP)
- Georgian lari (GEL)
- East Caribbean dollar (XCD)
- Qatari Riyal (QAR)
- Saudi Riyal (SAR)
- United Arab Emirates Dirham (AED)
- Malaysian Ringgit (MYR)
- Chinese Yuan Renminbi (CNY)
- Turkish Lira (TRY)
- Mexican Peso (MXN)
- Thai Baht (THB)
- South African Rand (ZAR)
