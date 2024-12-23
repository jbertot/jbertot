# Valuation

### 1 – Prerequisite & general inputs <a href="#id-1-1---prerequisite---general-inputs" id="id-1-1---prerequisite---general-inputs"></a>

1. **Explicit / Implicit valuation:** Users have the possibility to choose which income method will be used to assess the value of the property. Users can either opt for implicit income capitalisation methods or an explicit Discounted Cash Flow. \[EF1]&#x20;
2. **Valuation date:** Use this field to indicate the valuation date. This will be used as reference to calculate the remaining leases durations across the property.

<figure><img src="../../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

### 2 – Valuation <a href="#id-2-2---valuation" id="id-2-2---valuation"></a>

<figure><img src="../../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

1. **Timing of Cash Flow:** the valuation models can be tailored to factor the timing of cash flow: user can assume payments are received annually in arrear or quarterly in advance. This impacts the present value of future cash flow.
2. **Exchange rate:** If the lease currency is different than the country currency, users are prompted to enter an exchange rate that will be used to convert the results of the valuation.
3. **Method selection:** There are many implicit valuation methods to choose from in Interval . Not all methods are suitable for every valuation, as this will depend on the nature and contents of the lease as well as of the interest valued. Some methods are applicable for freehold valuation while others are suited for leasehold valuations.
   * **Freehold Cap rate on perpetuity:** This method assumes that the property generates a perpetual income stream, typically at market rent. The value is calculated by capitalizing the net annual income at a capitalization rate (cap rate)
   * **Freehold Cap rate on short term tenure let at market rent:** This method is applied when the property is let at market rent for a defined short-term period. The income is capitalized for the specific term, and adjustments are made for any reversionary interest and void period after the initial lease end.
   * **Term & Reversion – Hardcore & layer:** A valuation approach where the income is divided into two components:
     * Hardcore: Represents the secure, long-term income stream.
     * Layer: Refers to the additional, less secure income, obtained upon reversion in case of rent review.
   * **Term & Reversion – Hardcore & froth:** Similar to the "Hardcore & Layer" method but here focuses on:
     * Hardcore: Base income considered reliable.
     * Froth: Excess income above the sustainable base, often speculative or temporary (only applicable for the term)
   * **Leasehold at market rent dual rate with Annual Sinking Fund (ASF) and allowance for tax:** Used to value leasehold properties let at market rent. The method applies a dual-rate approach:
     * One rate for the income.
     * Another rate for sinking fund provisions, allowing for depreciation and tax liabilities
   * **Leasehold under market rent dual rate with Annual Sinking Fund (ASF) and allowance for tax (double ASF):** a variation for leasehold properties let at below-market rent. It uses a dual-rate approach to capitalise the profit rent, with additional sinking fund adjustments to account for under-rent situations and tax implications.
   * **Leasehold under market rent dual rate with Annual Sinking Fund (ASF) and allowance for tax (Parnell approach):** A specialized method for under-market rents that applies the dual-rate approach with the "Parnell Adjustment." This involves a more granular treatment of allowances for tax and sinking funds.
   * **Freehold with terminable life building & reversion to site value:** For properties where the building has a finite useful life, the valuation combines:
     * The present value of income from the building during its life.
     * The reversionary value of the site after the building's termination
   * **Freehold with terminable life building & provision for rebuilding:** This approach considers a finite building life but assumes continued income stream and provision for rebuilding. The valuation accounts for:
     * The present value of income on perpetuity.
     * Costs of reconstruction upon building’s end of useful life.

### 3 – Model assumptions <a href="#id-3-3---model-assumptions" id="id-3-3---model-assumptions"></a>

Each valuation method relies on a series of inputs. Some inputs are the same for all valuation methods, while others are specific to some. The full list of inputs and their description is presented below

1. **Effective Rent per year:** This is the rent of the lease after incentives have been considered.
2. **Market rent per year:** if applicable, use this field to enter the market rent per year for the same premises, inclusive of recoverable and expenses.
3. **Unexpired lease term:** this field is automatically calculated based on the valuation date and start date of the lease.
4. **Years to review:** if applicable, automatically calculated based on the rent review schedule of the lease.
5. **Years to write off:** if applicable, automatically calculated based on the write off schedule of the lease.
6. **Years to break off:** if applicable, automatically calculated based on the break off option schedule of the lease.
7. **Activate break off option:** if applicable, users can choose to activate the break option in the lease. If activated, the lease is terminated and income stream interrupted until a new tenant takes on the premises (after a void period or not)
8. **Growth rate per year until reversion:** if applicable, use this field to enter the growth rate to be applied for market rent or CPI / RPI estimates.
9. **Capitalisation rate / All-risk Yield:** use this field to enter the yield to capitalise the income on perpetuity or for the first term of the lease. Please justify the figure (i.e. sourced from market evidence) in the appropriate field.
10. **Reversionary Yield:** use this field to enter the reversionary yield to capitalise the income upon reversion. Please justify the figure (i.e. sourced from market evidence) in the appropriate field.
11. **Annual Sinking Fund (ASF):** when valuing a leasehold interest, use this field to enter the applicable rate for the ASF
12. **Tax rate on ASF:** when valuing a leasehold interest, use this field to enter the applicable tax rate for the ASF
13. **Secured rent:** when adopting the method “Freehold with terminable life building & reversion to site value”, use this field to indicate the secured rent until the building reaches the end of its useful life.
14. **Estimated rent for the land p.a.:** when adopting the method “Freehold with terminable life building & reversion to site value”, use this field to indicate the rent for the land that will be capitalised on perpetuity upon the end of the life of the building.
15. **Cost of rebuilding:** when adopting the method “Freehold with terminable life building & provision for rebuilding”, use this field to enter the estimated cost of rebuilding upon the end of the useful life of the existing building
16. **Estimated void period:** use this field to enter the void period after lease end. If let blank, the valuation will assume that the premises are re-let directly after the initial lease is terminated. Please justify the figure (i.e. sourced from market evidence) in the appropriate field.
17. **Purchaser’s cost:** if applicable, enter the purchaser’s cost here. They will be deducted from the capitalised income value.
