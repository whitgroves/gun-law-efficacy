# Analysis of Gun Law Efficacy in the United States

This is a follow-up to my 2016 review of [Motherjones' mass shooting analysis](https://github.com/whitgroves/motherjones-mass-shooting-analysis), which sought to determine whether state gun laws had any impact on the number of mass shootings. My original results were inconclusive.

As of 2025, the impact of firearm restrictions on gun crimes is still an open question in US politics, so I am reviewing it once again to see if 9 years of experience can help me find some clarity on this issue.

## Data Used
- [Motherjones Mass Shooting Database 1982-2024](./data/Motherjones%20Mass%20Shooting%20Database%201982-2024.csv) - An updated version of the [Motherjones US Mass Shootings dataset](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/)
- [FBI Crime in the US](./data/fbi-crime-in-the-us/) - The FBI's [Crime in the United States](https://ucr.fbi.gov/crime-in-the-u.s) datasets, by State (Table 5 for 1999-2015, 2017; Table 3 for 2016)
- [State Gun Laws](./data/state-gun-laws/) - Gun laws in the United States by state - originally compiled from [Wikipedia](https://en.wikipedia.org/wiki/Gun_laws_in_the_United_States_by_state) by Olivia Cheng in 2016
- [Census Population Change Data](./data/Census-Population-Change-Data-1910-2020.csv) - US Census Bureau [Historical Population Change Data 1910-2020](https://www.census.gov/data/tables/time-series/dec/popchange-data-text.html)

## Flaws in the original analysis
- I should have looked at per capita to descale the total number of events.
- The gun law data represented firearm restrictions they were in 2016, which would've shown how these events impacted state legislation, not the other way around.

## Updated approach
1. Find updated statistics on mass shootings
2. Re-use the compiled laws from 2016 to observe impact from that date onwards
3. Repeat the original 2016 analysis using new data on mass shooting events and looking at per capita numbers

## Acknowledgement
Each and every one of these events is a tragedy, and though it feels heartless to look at them through a statistical lens, their pervasiveness suggests a deeper problem in society that warrants taking a deeper look.

However, because this is an emotional - and for many, a personal - issue, I will not make any policy recommendations in my conclusion; it is on the reader to interpret the results as fits their worldview.