# Wolt Pricing Scraper

## Context and Objective

The main objective of building a pricing scraper is to help the pricing team and our stakeholders to get real-time pricing data of our competitor in a more efficient and effective way. Previously, it was done by manually go to the website and check one by one the prices of each store in order to compare the prices. As it is a time-consuming process, our stakeholders requested our support to provide a solution that could be adopted and applied at scale.

The data that should be provided include:

1. Delivery Fee of each store based on the input location
2. If the prices vary based on the distance from the user, what is the exact distance tiers and the corresponding Delivery Fee?

## Solution

The solution is to build a simple scraper that would provide the answers of the questions requested by our stakeholders by simply providing the geo location of the "user". The only step to execute is to provide the geo location and the script would automatically output the Delivery Fee of each store and the distance tiers applied in that specific geo location.
