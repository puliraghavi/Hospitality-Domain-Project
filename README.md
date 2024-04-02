# Hospitality-domain-project

![White and Violet Professional Modern Technology Pitch Deck Presentation](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/f1271da4-f2df-4d67-acf2-d48d717d40c6)

***

## 📚Contents
- [Problem Statement](#problem-statement)
- [Analysis](#analysis)
- [Power BI Report](#power-bi-report)
- [Insights](#insights)

# Problem statement
**Project title: Provide Insights to the revenue team in the hospitality domain**

This data analytics resume project challenge was conducted by Codebasics in the hospitality domain. 
In this case study we analyse the revenue metrics of AtliQ Grands.AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue.

Tasks :
1. Create the metrics according to the metric list.
2. Create a dashboard according to the mock-up provided by stakeholders.
3. Create relevant insights that are not provided in the metric list/mock-up dashboard.

# Analysis
- A total of 5 datasets were provided for this project, which includes two fact tables and 3 dimension tables
- **Datasets :**
  1. dim_date - Contains all the dates in the months- **May,June,July**
  2. dim_hotels - Details of all the hotels - Id, Name, category, city
  3. dim_rooms - Has columns room_id, room_class (Standard, Elite, Premium, Presidential)
  4. fact_aggregated_bookings - Conatins aggregated booking details for each property.
  5. fact_bookings - Records all the bookings at all the properties. 

- The datasets were cleaned accordingly and a **star schema** data model was created.
- **Data Model :**

![atliq data model](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/a40f88f4-7f32-4a43-9802-baac99651288)

- A list of metrics was provided to define the requirements.
- The primary focus of these metrics was to track revenue performance, guest preferences, and operational efficiencies on a daily basis.
- I have used DAX in Power BI to calculate these metrics.
- A few important ones include :
   1. Revenue
   2. Total Capacity,
   3. Occupancy %,
   4. Cancellation %,
   5. No Show rate %,
   6. ADR (Average Daily rate)
   7. RevPAR(Revenue Per Available Room)
   8. DBRN(Daily Booked Room Nights)
   9. DSRN(Daily Sellable Room Nights)
   10. Week over week change % of revenue, occupancy, ADR, RevPar, DSRN

# Power BI Report

Link to the dashboard - https://www.novypro.com/project/atliq-grands-revenue-report-power-bi

![atliq](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/0eb0d5e3-e554-4fa3-b4a4-794b6030fdc7)


A tooltip was added to all the KPIS view view the distribution among different categories of a rooms :

![atliq tt](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/61c7fff2-b52e-46da-a1d4-11a4d7b21aee)


# Insights 
1. Atliq grands operate in 4 major cities - **Bangalore, Hyderabad, Mumbai, Delhi**
2. The revenue generated over the 3 months totaled to **1.69 billion**, of which week 24 genarated the highest revenue.
3. **Mumbai** is found to be the hightest revenue generating city followed by bangalore
4. There are 7 types of properties under AtliQ, among which **AtliQ Exotica is the highest revenue contributor** (18.75%) and the **lowest contributor is AtliQ Seasons** (3.87%)

![rev by property](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/903a96ea-27f8-4a97-89ed-4dd67813c83b)

5. Among the two categories of the hotels i.e business and luxury, the **most booked are the luxury ones (61.62%)**.
6. Upon studying the distribution of total bookings among different room classes, we find that the most booked rooms come under **Elite class and Standard class**

![bookings by rooms](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/b56a40a8-ff24-444f-9e07-1e8bf62e60e9)

7. AtliQ Bay has the highest occupancy rate of 66%
8. Comparing cancellation rates, **Delhi** leads among cities, while **AtliQ Palace** holds the highest rate (25.2%) for individual properties.
9. Majority of bookings were made through online websites. Sites such as Make your trip, logtrip were the mostly used.

![bookings by rooms](https://github.com/puliraghavi/Hospitality-domain-project/assets/119037510/56ba07a8-c343-4d47-ad4b-230862242e38)

10. The occupancy% was high during weekends(62.6%) than weekdays(55.8%).





















