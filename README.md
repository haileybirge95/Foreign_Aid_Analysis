# Foreign Aid Analysis

This analysis seeks to answer the following questions regarding the impact of foreign aid on developing countries in Africa: How is foreign aid distributed? Is there a relationship between foreign aid and mortality? And finally, is population distribution related to foreign aid?

The analysis is based on data collected by U.S. Agency for International Development (USAID), U.S. Department of State, and World Bank Data. Included are 32 developing countries in the African continent, and the data spans from 2000-2022.
The significance of the results is determined by statistical testing include linear regression, p-values, and t-values.

<p align="center">
  <img src="https://i.imgur.com/WtlrkIG.png" alt="Description of image" />
</p>

## Hypotheses
### 1. Foreign aid is predominantly provided to low-income countries.
This plot shows aid in billions distributed over the years by income group. It confirms that the lowest income group received the most aid and the highest income group the least. 
![Image 1](https://i.imgur.com/x2FB9Fg.png)

### 2. There is a negative correlation between foreign aid and mortality.
To explore the hypothesis that there is there a relationship between foreign aid and mortality, a linear regression analysis was conducted. The statistical analysis resulted in a negative correlation, indicating the amount of foreign aid received has an impact on mortality rates. 
![Image 1](https://i.imgur.com/KPII16Z.png)

### 3. Countries with higher populations will receive more foreign aid.
A second linear analysis explored the last hypothesis. The linear analysis resulted in a positive correlation between foreign aid contribution and population.
![Image 1](https://i.imgur.com/qVaWCeu.png)

This analysis was based on two datasets:
1. Nasdaq World Bank - WB_DATA_d950d0cd269a601150c0afd03b234ee2.csv
2. Kaggle - us_foreign_aid_country

The Kaggle dataset is a subset of the Nasdaq World Bank dataset.
