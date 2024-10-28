## Summary of Analysis
#### Data Preparation:

The analysis utilized a SQL query to extract subscriber data from the turing_data_analytics.subscriptions table, focusing on subscription starts between January 1, 2021, and February 7, 2021.
The data was organized into weekly cohorts, allowing for a clear view of subscriber activity over time.
#### Overview
The heatmap shows subscription retention rates across cohorts from November 2020 to January 2021. The percentage indicates how many users from each cohort remain subscribed after subsequent weeks. For earlier cohorts (e.g., November 2020), the retention rates steadily decline over time, reflecting natural subscriber churn. Later cohorts (e.g., December 2020) maintain higher retention rates in the initial weeks, with some retaining over 90% of users through week 6. However, for the most recent cohorts, such as January 2021, retention data is incomplete, showing 0% past week 2, due to the cutoff period (February 7, 2021).

Recommendations:
Retention Strategies: Focus on sustaining the higher retention rates seen in December 2020 cohorts by analyzing successful engagement tactics.
Churn Analysis: Investigate why retention stabilizes around 85-88% for earlier cohorts and implement interventions at key drop-off points (e.g., weeks 2-4).
Future Cohorts: Test strategies for new cohorts that resemble the strong performance of December, ensuring timely and relevant engagement across the subscription lifecycle.
