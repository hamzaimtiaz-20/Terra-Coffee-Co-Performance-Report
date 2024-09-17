# Terra-Coffee-Co-Performance-and-Marketing-Insights
### This project aims to optimize Terra Coffee Co.’s product offerings, marketing strategies, and customer retention efforts by leveraging sales data insights to increase revenue across key markets, improve customer satisfaction, and drive larger purchases through targeted campaigns and personalized offers.

Terra Coffee Co. is a fictional company that sells packaged coffee bean products internationally.

## Data Source
The dataset consisted of a single .csv file containing three tables:
- The orders table held order details, including order ID, date, and basic customer information like name and email.
- The customer table stored customer data, such as customer ID, name, registration date, and contact details.
- The products table included information on the coffee products, such as product ID, size, roast type, price, and profit margins.

Several columns in the orders table, including customer name, coffee type, size, and unit price, were missing data. To address this, XLOOKUP and INDEX functions were used to match and fill in the missing values from other tables. Once the data was complete, the date and size columns were reformatted, and the orders table was converted into a pivot table for easier visualization and analysis.

![5  formatting date and size columns and converting tab to table](https://github.com/user-attachments/assets/b080c46b-cb85-4c99-9768-8fa7d8730bdb)


## Insights Summary
### To analyze overall business performance and uncover marketing insights, the dashboard focuses on the following key areas:
- Sales trends by coffee bean type (Arabica, Liberica, Robusta, Excelsa) over time
- Geographic sales distribution by country
- Customer-driven performance with a focus on top 5 customers
- Filtering by roast type, size, and loyalty program participation, with a timeline from 2019 to 2022 for time-based insights

### Sales trends by coffee bean type
- Arabica shows more consistent sales, peaking during the middle of each year.
- Excelsa and Liberica have higher volatility, with sharp peaks and dips.
- Sales for Robusta appear more stable but have fewer spikes in revenue.
- Peak sales months are generally observed in the middle of the year (summer), with fluctuations during other periods.
  
### Geographic sales distribution
- The majority of sales come from the United States, far outpacing other countries ($35.6k), Ireland follows at $6.6k, and the United Kingdom contributes the least at $2.7k.
- This suggests a strong presence in the U.S. market, with room for growth in international markets.

### Customer-driven performance
- The top customer, Allis Wilmore, contributed $317, with other top customers contributing between $278 and $307.
- Customer sales are relatively close in value, suggesting the top customers are spread out in their purchases.
- This indicates the potential for a loyalty program or marketing strategy to encourage repeat purchases from high-value customers.

### Filtering by roast type, size, and loyalty program participation
- Roast preferences vary significantly across countries, suggesting the need for region-specific marketing strategies (light roast for the U.S. market, dark roast for the Irish market, medium roast for the U.K. market)
- There is a clear trend that larger package sizes drive higher sales, making it worthwhile to promote larger sizes to increase revenue in all regions and among key customers.
- The United States is the strongest market for both loyalty and non-loyalty members, but non-loyalty members contribute more to overall sales.
- Top customers in the non-loyalty segment spend more per individual than loyalty members.
- Loyalty members contribute to more stable sales over time, while non-loyalty members drive larger but less frequent purchases.
- Ireland shows a slightly stronger response from loyalty members, suggesting a potential growth opportunity in this market.

## Recommendations
- Tailor Marketing and Product Offerings by Region: Develop region-specific campaigns (e.g., special promotions, influencer marketing, localized ads) that highlight the most popular roast in each country.
- Promote Larger Package Sizes to Boost Sales: Expand the range of larger package options and make them more prominent in both online and in-store displays. Highlight savings or value-added offers for larger sizes to push customers toward higher-volume purchases.
- Strengthen Loyalty Program: Strengthen the loyalty program to increase membership revenue and boost sales by introducing exclusive benefits for members, such as:
  - Early access to new roasts or limited editions.
  - Tiered rewards for more frequent or high-volume purchases.
  - Personalized offers based on purchase history (e.g., discounts on their favorite roast or size).

## Dashboard
The dashboard can be found publicly [here](https://1drv.ms/x/c/44e7afdb0dddc60d/ETzMofiAYURPghVwdCnIeXIBlhe4s6BtA4IS8xWGN_nykA). This dashboard enables users to filter by roast type, size, loyalty membership, and order date.

![cropped dashboard](https://github.com/user-attachments/assets/ffdd32ae-b4dc-4506-8c27-88c366f73679)

## Presentation Sample
The presentation created walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/1cAIyW8XMK9J51erM7xtrKvAMUw_lYodd/edit?usp=sharing&ouid=105728372417079201864&rtpof=true&sd=true). Some extracts are presented below for easy viewing.

![insights 1](https://github.com/user-attachments/assets/cc8058c8-821c-4bc9-b23a-5ae195f30b3f)
![recommendations](https://github.com/user-attachments/assets/d5423e98-3b45-418e-97bd-f37ab2a4d117)
![technical process](https://github.com/user-attachments/assets/0f16f543-79f5-496b-9a8d-9773ce16159e)
