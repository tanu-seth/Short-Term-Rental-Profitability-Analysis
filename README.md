# Short-Term-Rental-Profitability-Analysis
 
### Problem Statement
Build a data product to assist a real estate company to understand which zip codes are profitable for short term rentals within New York City.

### Data Sources

* Cost Data : Estimate of value for two-bedroom properties provided by Zillow.
* Revenue Data : AirBnB Data Set with relevant short term rental information.

**Assumptions Made:**
The investor will pay for the property in cash (i.e. no mortgage/interest rate will need to be accounted for).
The time value of money discount rate is 0% (i.e. $1 today is worth the same 100 years from now).
All properties and all square feet within each locale can be assumed to be homogeneous (i.e. a 1000 square foot property in a locale such as Bronx or Manhattan generates twice the revenue and costs twice as much as any other 500 square foot property within that same locale.)

### Extra Assumptions:

* The company is planning to buy the property in 2019.
* There is no increase in rent Year over Year for airbnb listings.
* The price host is charging per night is for the entire property irrespective of private room/entire house listing.
* Yearly Maintenance of property does not exceed around a month’s rent.
* Property repair for damage caused by tenants is totally covered by the security deposit charged.
* Vacancy rate remains consistent across years. No seasonality.
* Properties are active listings for 365 days.

### Factors considered

Four factors are considered while estimating the profitability of investment in short term rental propertys. Rental Demand and competition is something which cannot be controlled but hugely impacts the success of rental business. Gross monthly income is calculated based on the average rent per month of a 2 bedroom property in a particular zip. It is again an estimate of what people are willing to pay for that area in an average. Payback time is calculated based on the purchase price of property and the gross annual income.

* **Rental Demand** - Determined by Average Vacancy Rate in the area
* **Competition** - Determined by percentage of superhosts in the area
* **Gross Monthly Income** - Determined by average monthly rent in the area
* **Payback Time in Years** - Determined by property purchase price and gross annual income

Other parameters like cleaniless, amenities, host behavior can be controlled and modified based on the budget available and long term business plan and can ultimately be used to predict a competitive price for our listing. Hence, I did not include them in analysis for now.

### Conclusion
Zipcodes to invest in:

**10025** - The payback time is close to 16 years as compared to the least for all zipcodes - 13 years(zip 11434). Based on the gross monthly income of $9134 , this zipcode will be overall more profitable for long term. It also among the top 5 in demand and competition analysis.

**10036** - The payback time is 24 years and Effective gross income is close to $8000.

**10011** - This zipcode has only 8% superhosts , hence adequate competition. The payback time is 26years and Gross monthly
