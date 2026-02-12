## Do More Airbnb istings implies Higher House Price in Paris?
#### What Changed After the 2015 Regulation?

This project addresses a central business and policy question: Has the growth of Airbnb listings contributed to changes in property pricing dynamics in Paris? Furthermore, what was the impact of the 2015 regulation on market prices?

<img width="1536" height="1024" alt="Airbnb" src="https://github.com/user-attachments/assets/ad7b2038-10be-4459-ba7e-81ab9705888d" />

### Introduction

Paris, France has long stood as one of the world’s most celebrated tourist destinations. Known as La Ville Lumière—the City of Light—it attracts millions of visitors each year to iconic landmarks such as the Eiffel Tower and the Louvre. Beyond its monuments, Paris captivates with its unmistakable je ne sais quoi: charming cafés, elegant Haussmann architecture, vibrant shopping districts, and a cultural richness that feels timeless. One of the city’s greatest strengths is its ability to constantly reinvent itself—every visit offers something new. Quite simply, Paris is always a good idea.

At the same time, Airbnb, Inc., an American technology company, has transformed the global accommodation market through its online marketplace for short- and long-term stays, experiences, and services. Operating as a platform intermediary, Airbnb connects hosts and guests while earning a commission on each booking. Over the years, Paris has emerged as one of Airbnb’s largest and most dynamic rental markets worldwide.

Understanding Airbnb listing prices in a city with such intense and sustained tourist demand is therefore crucial. Pricing dynamics affect multiple stakeholders: hosts seeking profitability, tourists making budget decisions, policymakers concerned with housing affordability, and investors evaluating market sustainability. Gaining insight into how listing prices evolve allows for more informed economic and strategic decisions.

This project addresses a central business and policy question: Has the growth of Airbnb listings contributed to changes in property pricing dynamics in Paris? Furthermore, what was the impact of the 2015 regulation on market prices? 

The following analysis explores these questions through data-driven evidence to uncover the relationship between platform expansion, regulation, and pricing trends in Paris

**Can you spot any major differences in the Airbnb market between cities?**

**Which attributes have the biggest influence in price?**

**Are you able to identify any trends or seasonality in the review data?**

**Which city offers a better value for travel?**

The Airbnb data for this analysis contains 250,000+ listings in 10 major cities, including information about hosts, pricing, location, and room type, along with over 5 million historical reviews.

 **NOTE: Prices are in local currency**
 
 **Data Source: Inside Airbnb*
 
<img width="1709" height="1302" alt="100" src="https://github.com/user-attachments/assets/d2deeb60-14b7-49fa-98d2-cc412b7f4a76" />

This just shows the log distribution of the Airbnb Listing. This is not normally distributed after taking the log. This means price are concentrated on one side


<img width="2760" height="1638" alt="101" src="https://github.com/user-attachments/assets/d056a5b2-5007-43af-9ca7-067a41440a60" />

The chart illustrates the total number of Airbnb listings across major global cities. Paris clearly leads the ranking with the highest number of listings, significantly outperforming other cities. 

This reinforces Paris’s position as one of Airbnb’s most active and competitive markets worldwide.

New York and Sydney follow, though with noticeably fewer listings than Paris. Mid-ranked cities such as Rome, Rio de Janeiro, and Istanbul show strong but comparatively moderate market presence. Meanwhile, cities like Mexico City, Bangkok, and Cape Town maintain substantial activity, though at lower levels. Hong Kong records the smallest number of listings among the cities shown.

Overall, the distribution highlights Paris as a dominant Airbnb market, which strengthens the relevance of focusing on Paris when analyzing the relationship between Airbnb growth and property price dynamics.


<img width="2906" height="1638" alt="102" src="https://github.com/user-attachments/assets/18c8eae4-acf2-4362-8ac2-1ae1ca87a22a" />

Élysée emerges as the most expensive neighborhood, with an average Airbnb listing price of €201.53 per night. This is followed closely by Louvre, where the average nightly price is €175.30. 

Listings in Élysée are therefore approximately 20.1% more expensive than those in Louvre, the next most costly area.

At the lower end of the price distribution, Ménilmontant records the most affordable listings, with an average nightly price of €74.94. 

In comparison, prices in Élysée are roughly 181% higher, highlighting a substantial disparity in short-term rental prices across Paris neighborhoods.


<img width="2578" height="1638" alt="103" src="https://github.com/user-attachments/assets/c0bf4810-89de-4a61-870f-af06df79b7b6" /> 

Interestingly, the data reveal an unexpected pattern: listings accommodating 11, 13, or 14 guests are priced higher than those with even greater capacity. This deviates from the typical expectation that larger accommodations command higher prices due to increased space and utility.

Rather than a strictly linear relationship between capacity and price, this suggests a possible nonlinear or reverse effect at certain thresholds. It may reflect differences in property type, location, luxury level, or demand segmentation—where mid-to-large group accommodations are positioned as premium offerings, while very large listings compete differently in the market.

In other words, more capacity does not automatically translate into higher prices; pricing appears to be influenced by additional structural or market factors beyond simple accommodation size.


<img width="2605" height="1580" alt="104" src="https://github.com/user-attachments/assets/004dcad4-86c3-457d-8357-68b89aa49735" />

At Airbnb’s entry into the Paris market, the platform had only a handful of hosts. However, as its popularity surged, host registrations expanded rapidly, reaching nearly 12,000 new hosts. This rapid growth coincided with increasing public concern. Policymakers and local communities—particularly in high-value neighborhoods such as Élysée—began to worry that short-term rentals were driving up property prices and reducing long-term housing availability.

In response, authorities introduced regulatory restrictions in 2015, limiting who could lease properties and for how long listings could remain active. The impact was immediate and pronounced: new host registrations dropped sharply following the policy intervention, signaling a clear structural break in market entry.

<img width="2552" height="1580" alt="105" src="https://github.com/user-attachments/assets/05d3b4b4-42f3-43df-b475-478ec07d3ccc" />

In the early phase of Airbnb’s expansion, average listing prices remained relatively high. However, as more hosts entered the market, increased competition appears to have exerted downward pressure on prices—consistent with basic supply and demand dynamics.

Following the 2015 regulation, the trend reversed. With tighter restrictions limiting new entries, average prices began rising again, eventually returning to pre-pandemic levels before 2020.

While this pattern suggests a strong relationship between host entry and pricing dynamics, it is important to distinguish correlation from causation. Although we cannot definitively claim a causal effect without further econometric testing, the timing and magnitude of these shifts strongly suggest that reduced host entry may have eased competitive pressure, contributing to higher average prices after the regulatory intervention.

<img width="2772" height="1580" alt="106" src="https://github.com/user-attachments/assets/8f93647a-4654-4812-a912-f3c17ea2dbfd" />

By plotting host growth and average prices together, the relationship becomes even clearer. Periods of rapid host entry align with declining average prices, while the 2015 regulatory shock corresponds with a sharp drop in new hosts and a subsequent rise in prices.

The visual evidence highlights a significant structural shift in 2015, reinforcing the hypothesis that regulation altered market dynamics in Paris’s short-term rental sector.

<img width="2853" height="1407" alt="107" src="https://github.com/user-attachments/assets/331a8b6c-00ba-4968-bfa3-7eefb4f12427" />

Demand for entire apartments is the highest. This is not surprising, as many people prefer not to share living spaces with strangers. 
However, while this explanation seems plausible, it cannot be confirmed without further analysis.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Conclusion

Due to the limitations of the dataset, particularly its lack of recency, I am unable to provide policy or strategic recommendations at this stage. The data may not accurately reflect current market conditions or recent regulatory developments.

Access to a more up-to-date dataset would allow for a more robust and relevant analysis, and I would welcome the opportunity to reassess the findings using current data.
