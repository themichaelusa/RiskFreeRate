# RiskFreeRate

Simple script for scraping the [Risk Free Rate](https://www.treasury.gov/resource-center/data-chart-center/interest-rates/Pages/TextView.aspx?data=yield) from the U.S Department of The Treasury. Use at your own risk.

## Usage
```python
rfr = RiskFreeRate()
monthRate = rfr("1mo")
decadeRate = rfr("10yr")
```
