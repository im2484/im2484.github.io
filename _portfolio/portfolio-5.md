---
title: "The Economics of Space (2024)"
excerpt: "Carolina Planning Journal Vol. 49<br/><img src='/images/EJ_protest_newark.jpg'>"
collection: portfolio
paperurl: 'https://issuu.com/carolinaplanningjournal/docs/cpj_vol49'
---

(This research article was published in the Spring 2024 issue of the UNC-Chapel Hill Planning Journal.)

Synopsis: New Jersey has seen an unprecedented expansion of warehouse distribution centers since 2020, with corporations such as Amazon and Wayfair pouring thousands of trucks into local communities. This has strained local infrastructure and created a threat to public health. Air and noise pollution produced by heavy-truck traffic increases the risk of preterm births and respiratory disease.
It is anecdotally understood that distribution centers are typically developed in areas with high Black and Hispanic populations. Yet, the scale of this disparity is not documented since the state does not track warehouse development.
To quantify the scale of this problem, I used warehouse data obtained from a financial database and a dataset of 6 million registered voters obtained through the NJ Department of Elections. I applied a race prediction algorithm (fBISG) using the [wru] package in R and imputed racial probability using party affiliation, first and last name, and county of residence. I geocoded all registered addresses in ArcGIS and conducted a spatial analysis at different distance intervals to measure racial and economic disparity.
[View Code Here](https://github.com/im2484/fBISG_code).
