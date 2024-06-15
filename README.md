# Call Center Dashboard
## Introduction
This project involves the analysis of call center data from October 2020, containing over 30,000 rows. The aim is to create a comprehensive dashboard that provides insights into customer interactions, sentiments, and other key metrics.

![Excel dashboard Project](https://github.com/josephabodunrin/Call-Center-Dashboard/assets/74240726/a9204322-9b6a-46bd-b2b2-f6c20e854a70)
## Dataset
The dataset includes the following columns:
- **id**: Unique identifier for each call.
- **customer_name**: Name of the customer.
- **sentiment**: Sentiment of the customer interaction (e.g., Neutral, Very Positive, Negative).
- **csat_score**: Customer satisfaction score (CSAT).
- **call_timestamp**: Timestamp of the call.
- **reason**: Reason for the call (e.g., Billing Question, Service Outage).
- **city**: City of the caller.
- **state**: State of the caller.
- **channel**: Channel through which the call was made (e.g., Call-Center, Chatbot).
- **response_time**: Response time category (e.g., Within SLA, Above SLA).
- **call duration in minutes**: Duration of the call in minutes.
- **call_center**: Call center location handling the call.

## Analysis
The analysis is structured into several key steps:
1. **Data Cleaning**: Handling missing values, correcting data types, and ensuring data consistency.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of data, identifying patterns, and visualizing key metrics.
3. **Sentiment Analysis**: Analyzing customer sentiments and their impact on CSAT scores.
4. **Performance Metrics**: Evaluating call center performance based on response times and call durations.
5. **Geographical Analysis**: Analyzing call distributions across different cities and states.
6. **Channel Analysis**: Comparing performance and sentiments across different channels (e.g., Call-Center, Chatbot).

## Results
Key findings from the analysis include:
- **Sentiment Distribution**: Insights into the overall sentiment of customer interactions.
- **CSAT Scores**: Relationship between sentiments and customer satisfaction scores.
- **Performance Insights**: Analysis of response times and call durations.
- **Geographical Trends**: Distribution of calls across various regions.
- **Channel Performance**: Comparison of performance metrics across different communication channels.

## Conclusion
The analysis provides valuable insights into call center operations, customer sentiments, and performance metrics. These findings can help in improving customer service strategies and operational efficiency.

## Usage
To replicate the analysis:
1. Clone the repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the analysis scripts or notebooks provided in the repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
