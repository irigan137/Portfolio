# Forecasting customer churn for a fitness center

## Project description

Analyze and prepare an action plan for customer retention:

- learn to forecast the probability of churn (at the level of the next month) for each client
- form typical portraits of clients: identify several most prominent groups and describe their main features
- analyze the main attributes that most strongly influence churn
- Formulate the main conclusions and develop recommendations to improve the quality of work with clients

## Data description

A file that contains data for the month before churn and the fact of churn for a particular month (gym_churn.csv) with the following columns:
- 'gender'
- 'Near_Location' - living or working in the area where the fitness center is located;
- 'Partner' - employee of a partner company of the club;
- 'Promo_friends' - the fact of the initial entry within the 'bring a friend' promotion;
- 'Phone';
- 'Age'
- 'Lifetime' - time since the first visit to the fitness center (in months);
- 'Contract_period' - duration of the current valid subscription (month, 6 months, year);
- 'Month_to_end_contract' - period until the end of the current valid subscription (in months);
- 'Group_visits' - the fact of attending group classes;
- 'Avg_class_frequency_total' - average frequency of visits per week for the whole time since the beginning of the subscription;
- 'Avg_class_frequency_current_month' - average frequency of visits per week for the previous month;
- 'Avg_additional_charges_total' - total revenue from other services of the fitness center: cafe, sport goods, beauty and massage salon.
- 'Churn' - the fact of the customer churn in the current month.


## Technologies used

pandas, plotly, scikit learn, scipy, matplotlib
