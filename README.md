# Exploratory Analysis on Suicide Rates 

## About Us

### Group Members - Project Group 26
Yaksh Joshi - yakshjoshi

Olivia Ramos - oliviaram

Umairuddin Mohammed - Umairuddin

Ajaane Kanagasabai - ajaane


## Introduction

The topic we're reporting on is global suicide rates. The dataset that we're using for this analysis is Suicide Rates Overview 1985 to 2016 and can be found here:
[Kaggle](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016 "Kaggle").

This dataset contains the suicide rates of all the countries from 1985 to 2016 and has the following attributes.

	country - Country in the world
	year - Year for which data is shown
	sex -Gender description (i.e. male, female)
	age - The cluster of age group
	suicide_no - Number of suicides
	population - Population of the country
	suicides/100k pop - The number of suicides per 100k population
	country-year - country-year composite key
	HDI for year - Human Development Index for that year
	gdp_for_year ($) - GDP of the country for that year (USD)
	gdp_per_capita ($) - GDP per capita for that country (USD)
	generation - The generation of a particular group

As global suicide rates are increasing, we chose a dataset that provides enough data with a wide range of attributes that can demonstrate a correlation between
key socio-economic factors (i.e., the status of particular groups) and suicide rates. Since this dataset provides socio-economic background for each nation on 
the basis of years, we can attribute increased/decreased sucicide rates among different groups within a particular time, generation, country, etc. Therefore, 
the collection of such data can demonstrate certain indicators of increased suicide rates, which is useful in the cause of suicide prevetion. 

Supplementary Dataset

We used two supplementary dataset in conjunction with our primary dataset.

1) country to continent

Source: https://www.kaggle.com/statchaitya/country-to-continent

This dataset contains information on countries, including the continent and sub-region it belongs to.

	country - Country the data belongs to.
	code_2 - 2 letter country code
	code_3 - Alternative 3 letter country code
	country_code - Numeric country code
	iso_3166_2 - ISO 3166 Standard
	continent - Continent the country belongs to
	sub_region - Subregion the country belongs o
	region_code - Numeric region code
	sub_region_code - Numeric subregion code

This dataset was used to categorize countries to their continent. This way our analysis specturm can be broaden.

2) Global Death Cause

Source: https://www.kaggle.com/tahminashoaib86/global-cause-of-the-deaths-other-than-diseases?select=Caused+of+Deaths.csv

This dataset shows the Global Cause of death other than diseases

Description of data

	Country: Contains the Names of the Country
	ISO_CODE: Is the ISO-3 country identification code
	Year: Year of the number of Deaths
	Deaths: Total death of the individuals (including both male and female)	
	Cause: Cause of the death such as Conflict and Terrorism
	Male POP: Male Population with given Country
	Female POP: Female Population within given country
	Total Pop: Total Population with each country
	GDP: GDP (current US$)
	PCAP: GDP per capita (current US$)

We used this dataset for 2 primary reasons, 1) Comparison and 2) Corelation with our primary dataset.


## Discussion
This dataset compiles suicide rates from each country ranging from 1985-2016. The suicide rates are attributed to each country, year, sex, age, GPD, population and generation. On the basis of suicide prevention and prediction, we must look into these values to negate, or find a correlation between the trend of suicide rates against multiple variables. This dataset helped us determine such trends. For instance, we have deduced that males make up the majority of the global suicide rate, at a significant percentage of 78.9% vs 21.1% for females. This proportion is demonstrated in each country. Thus, men face an increased risk of suicide rates. This may be attributed to the stigma regarding mental health, particularly men’s mental health, as societal standards may defer at-risk men from seeking help or finding ways to cope with mental health. Despite the disproportion between men and women, both sexes follow the same trend (increase/decrease) of suicide rates throughout the years. 

Furthermore, the older generations face an increased risk of suicide, with the Silent Generation at 33%; Boomers, Gen X, and G.I. Generation at approximately 20% each. Throughout the range of years, those 75 years and older face the highest suicide rate overall. While all age ranges, generations, and sexes follow the same trend of suicide rates, there are certain years in which the suicide rate peaks. Since 1985, the suicide rate has been increasing steadily. We can attribute the growth in population to this, of course, however; there are more factors than simply an increase in suicide rates due to population increase that we must consider. Initially, we decided to determine whether there existed a correlation between the GDP per capita and suicide rates. Assuming wealthier countries exhibited decreased suicide rates was false. Instead, countries with a greater GDP were those with higher suicide rates than those with a lower GDP. So, given that a country’s accumulation of wealth is not an indicator of suicide risk, we investigated other factors. For instance, the time period in which suicide rates spike are significant factors such that certain world events can be attributed to this. From the data, we have seen that the global suicide average increases drastically after 1990 and peaks in 1995. This is also where we see the increase of male-dominated suicides, whereas during this time period, the female rate actually decreases slightly. Thus, we compiled a chart of the countries with the highest suicide by total population average, and have seen that the top countries are the Russian Federation, Lithuania, Belarus, Lativa, Hungary, Kazakhstan, etc. All the countries are post-Soviet and have formed from the aftermath of the collapse of the Soviet Union in 1991. We can infer that such a drastic world event has sparked unrest following its ethical, and economic disintegration.  Moreover, 2002 and 2003 display high sums of the total global suicide rate. A major world event preceding this was 9/11. After 2003, the total amount of suicides declines slightly, then peaks again in 2009, following the stock market crash in 2008. Thus, we can attribute an increase in suicide rates to the effects of global crisis, societal unrest, and economic disintegration. 

By performing EDA on Global Death by Causes other than diseases, we can see some correlation on suicide rate/year vs deaths/year, there was increasing number of suicides and deaths after 1991, which peaked around 1995, we can conclude conflict as the main reason as Soviet Union dissolved. There are multiple factors such as mental distress after the loss of some-one close, economical burden on families, unstable state governance, induced fear by roits. We can also factor that the most deaths occured were the cause of some form of terrorism or conflict in a state. We can also observe negative correlation in terms of deaths by suicide/continents vs deaths by different causes/continents. Developed countries are leading in terms of suicide, on the other hand, the total number of deaths in undeveloped or developing nations is much higher. In terms of total number of deaths by suicide and total number of deaths by different causes, suicides data is negligible to that of different causes. We can also observe that as year progress the number of deaths and suicides both decreases, we can attribute this change to improved lifestyle, stable economic condition and drastic innvoation in technological and agricultural sector.


## Conclusion
In this project, the concept is to analyze statistically significant data on suicide rate. All in all, we see that the details show what we see in the newspapers, on television and so on, in our view many of the conclusions we reached were already predicted; just think of the tremendous number of teen suicides, never seen in the data.

Often, the suicide rate is related to a number of factors. 
- First, the national GDP per capita. We have seen that the suicide rate in many countries is closely related to the national gdp, indicating that the level of world wealth has a somewhat lower rate of suicide.

- Second, the age. According to the suicide rate of each age group, the rate of elderly is high, so young people should be especially concerned about the elderly. In addition, the well-being of the elderly throughout the world may be at stake.

- Third, mental health. Suicide is one of the leading causes of death among all American adults. Data show alarming differences in suicide for different sexes. It’s evident that males are more inclined to suicide, than females. In addition, Mental health is a major predictor for suicide.
## Acknowledements
This project was submitted as the final course project for CSCI 2000U “Scientific Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cited.

## README
Download and extract all of the files in the same directory structure to run the code and produce the expected output.


