# Capstone-Project-Purwadhika-Module-03-Data-Analysis

# 1. BACKGROUND

**Sunrise Supermarket, London, 2015.**

In early 2012, Sunrise Supermarket began implementing a new system to record customers’ demographic information, purchasing activities, campaign participation, complaints, and purchase channels. Initially, this system was designed primarily for bookkeeping and operational reporting. However, as the dataset grew richer over time, the London headquarters recognized its untapped potential and brought in a data analyst to explore and leverage the information for strategic decision-making.

In today’s data-driven business landscape, supermarkets increasingly rely on Customer Relationship Management (CRM) systems to collect and manage valuable customer information. This includes demographic profiles, purchasing behaviors, and responses to marketing campaigns. When analyzed effectively, CRM data can provide powerful insights into customer preferences, predict future behavior, and enable highly personalized marketing strategies.

Despite this potential, many organizations still underutilize their CRM data, relying on broad, one-size-fits-all marketing approaches that fail to capture the complexity of customer behavior. As competition grows and consumer expectations continue to evolve, using CRM data for customer segmentation and behavioral analysis is no longer optional — it is essential. Through segmentation, businesses can deliver more relevant customer experiences, strengthen loyalty, and improve marketing efficiency.

# 2.  PROBLEM STATEMENT

- **Low Marketing Campaign Engagement**
A `significant portion of customers did not accept any marketing campaign offers`. This low engagement rate reflects a misalignment between current marketing strategies and customer behavior, leading to ineffective promotional efforts and missed opportunities for growth.

- **Lack of Customer Segmentation Strategy**
Although the supermarket has access to sufficient CRM data, it `lacks a structured approach to segment customers based` on behavioral and demographic characteristics. Without proper segmentation, marketing initiatives remain broad and generic, limiting their impact and efficiency.

- **Inefficient Marketing Resource Allocation**
`Current marketing efforts target the entire customer base rather than focusing on high-potential segments`. This unfocused approach increases costs and dilutes campaign effectiveness, making it difficult for the supermarket to maximize return on investment and strengthen customer relationships.

`Using a CRM-driven approach, this project aims to analyze customer behavior over the past two years to formulate a more effective market strategy.` By leveraging CRM data, the supermarket will be able to better understand customer needs and preferences, enabling it to align products and marketing activities with specific customer segments. Through data-driven insights, the supermarket can deliver more targeted promotions, build stronger customer relationships, and increase marketing efficiency.

For example, rather than investing resources to promote a new product to the entire customer base, the supermarket can identify which customer segments are most likely to respond and focus its marketing efforts on those groups. This targeted CRM approach helps optimize marketing spend, increase campaign effectiveness, and strengthen customer engagement.

# 3. STAKEHOLDER

Marketing, Store Manager and Customer Service Teams of Sunrise Supermarket.

# 4.  DATA
To answer the research questions above, this study will analyze customer data collected through the supermarket’s Customer Relationship Management (CRM) system. The dataset contains detailed information on customer demographics, household composition, purchasing behavior across various product categories, and engagement through different shopping channels. [This data](https://drive.google.com/file/d/1lGG2nBWS5lVEpmmBZp2r0Koesa4t6c7W/view?usp=sharing) serves as the foundation for identifying distinct customer segments and uncovering behavioral patterns that can inform targeted marketing and customer relationship strategies.
There are *29* columns in the Supermarket Customers dataset, namely:

People
* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Products
* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years

Promotion
* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

Place
* NumWebPurchases: Number of purchases made through the company’s website
* NumCatalogPurchases: Number of purchases made using a catalog
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to the company’s website in the last month

# 5.  DATA ANALYSIS
Outline:
- Demographic Analysis
- Customer behaviour Analysis
- Marketing/Campaign Analysis
- LRFM Analysis
- Data Visualization via Looker [link](https://lookerstudio.google.com/reporting/21a6aa4c-3343-430d-965c-07e1eea0e968)

# 6. CONCLUSION & RECOMMENDATION
## Conclusion
- In summary, by aligning the efforts of the marketing team, store managers, and customer service, Sunrise can build a stronger and more holistic customer experience strategy. This approach not only maximizes revenue potential through targeted campaigns and improved in-store engagement, but also strengthens customer loyalty, supports sustainable growth, and positions Sunrise as a customer-centric modern supermarket.

- Moreover, by leveraging a CRM-driven approach, the company can make more data-informed and holistic decisions. Centralizing customer information across marketing, sales, and service functions enables Sunrise to identify behavioral patterns, personalize campaigns more effectively, and respond to customer needs with greater precision. This integrated strategy creates a seamless ecosystem where insights turn into actionable strategies, ensuring long-term competitive advantage and stronger customer relationships.



## Recommendation
### For the Marketing Team
- Sunrise’s sales performance shows that high-value products such as Wine, Meat, and Gold play a major role in driving overall spending. This creates a strong opportunity for event-driven and experience-based marketing strategies. Marketing teams can design themed promotions—such as “Family BBQ Nights” featuring wine and meat bundles or “Couple Celebration Packages” for Valentine’s or anniversaries combining wine, gold, and sweets—to encourage larger basket sizes and stimulate repeat purchases.
- In addition, improving in-store product display and curation can enhance customer experience and trigger more impulse buying among Silver and Gold segment customers. For online channels, curating bundled products within the catalog can make shopping more seamless, personalized, and appealing.
- To support product diversification, Sunrise can also introduce green campaigns in partnership with local organic farms to promote organic fruits. This not only aligns with global wellness and sustainability trends but also attracts a segment of customers who value health and eco-friendly living. Finally, to re-engage inactive online customers, marketing can deploy strategic promotional events like payday sales or Black Friday-style campaigns, aiming to increase web traffic, conversion rates, and overall customer activity.

### For Store Managers

- Although the complaint rate remains relatively low, most issues come from in-store experiences, highlighting the critical role of store operations. Store managers should ensure that staff are trained to be proactive, attentive, and responsive, especially during peak hours or promotional events. Creating a more personalized and enjoyable shopping atmosphere can help maintain high satisfaction levels and strengthen customer trust in the brand.
- Additionally, integrating in-store promotions with marketing efforts—such as on-the-spot cross-selling suggestions or themed product corners—can enhance the impact of campaigns and encourage customers to explore more product categories during their visits.

### For Customer Service Teams

- Customer service plays a key role in sustaining the current low complaint levels and turning good experiences into loyalty-building opportunities. By ensuring quick, empathetic, and solution-oriented responses, the CS team can help reinforce brand trust. Proactive strategies such as post-purchase follow-ups, satisfaction check-ins, or exclusive loyalty messages can deepen engagement and encourage repeat transactions.
- In the long term, customer service can collaborate closely with marketing and store teams to identify early signals of churn or dissatisfaction and address them before they escalate. This integrated approach ensures that every customer touchpoint—online or offline—delivers a consistent and satisfying experience.
