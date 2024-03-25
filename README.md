# CardioGood-Fitness-Data-Analysis

Shorcut to the content:
1. **[Project Background](#Project-Background)**
2. **[Data Analysis with Python](#Data-Analysis-with-Python)**
3. **[Conclusion and Business Strategies](#Conclusion-and-Business-Strategies)**

# Project Background
## Context
he market research team at AdRight is assigned the task to identify the profile of the typical customer for each treadmill product offered by CardioGood Fitness. The market research team decides to investigate whether there are differences across the product lines with respect to customer characteristics. The team decides to collect data on individuals who purchased a treadmill at a CardioGood Fitness retail store at any time in the past three months. The data is stored in the CardioGoodFitness.csv file.

## Project Goal
Perform descriptive analysis to create a customer profile for each CardioGood Fitness treadmill product line.

## Data Dictionary
The team identified the following customer variables to study:

- Product: Product purchased - TM195, TM498, or TM798
- Gender: Male or Female
- Age: Age of the customer in years
- Education: Education of the customer in years
- MaritalStatus: Single or partnered
- Income: Annual household income
- Usage: The average number of times the customer plans to use the treadmill each week;
- Miles: The average number of miles the customer expects to walk/run each week;
- Fitness: Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is excellent shape.

# Data Analysis using Python

## Age Distribution
TM195 and TM498 have border range in age, while TM798 shows a majority of users around 25 to 30 years old.

![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/d86cccaa-a1ba-468f-93f3-23ae25f3195f)

## Gender Distribution
- TM195 is used by the most users, followed by TM498, then TM798
- While the proportion of male and female in using the TM195 and TM498 are mostly equal, there are way more male users use TM798.
  
![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/14d3ca01-5c62-4418-be70-342334b4e19a)

## Education Distribution
- The education year of those who are using TM798 is much higher than that of those who are using TM195 and TM498.

![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/57b33b24-a736-4f4d-bc08-484e9bd57faf)

## Martial Status Distribution
In general among all three products, there are more users who have partners.
![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/37e7079a-200d-4c02-8050-fd5bf38c9479)

## Usage Distribution
- The majority usage of TM195 and TM498 are 3 and 4.
- TM798 is used more than other two products.

![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/a97e7b40-5b6f-4d88-b87a-04260239eb08)

## Fitness Distribution
- Users using TM798 have more fitness than those who use other twp products
- TM195 and TM498 seems to be a useful product for user to maintain normal fitness.

![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/30774a93-fe4a-4153-ada3-b2e80b1d980a)

## Income Distribution
- The users of TM798 have significantly higher incomes compared to those of the other two products.

![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/03f75349-47be-474b-9e73-2e2937b361b9)


## Mileage Distribution
- TM798 achieves the highest mileage score, followed by TM198 and then TM195.
- The majority mileage of TM198 and TM195 falls between 50 to 100.

![image](https://github.com/leonlin97/CardioGood-Fitness-Data-Analysis/assets/142073522/23c4e8f2-73cd-407b-a5cb-ae9c96a1df40)


# Conclusion and Business Strategies

## Customer Profile of each product

### TM195

TM195 emerges as the most popular product across all genders, boasting the highest sales figures. On average, users intend to engage with it three times per week, maintaining a standard fitness level. However, their projected mileage for walking/running falls below that of the other two products.

### TM498

As for TM498, its customer profile closely mirrors that of TM195. The key point of differentiation lies in the users' intentions to cover greater distances through walking/running with this product.

### TM798
TM798, on the other hand, caters to a more specialized demographic. Despite selling the fewest units, it stands out significantly in various metrics compared to the other two products. Noteworthy distinctions include:

- More attractive to male users.
- Be used more times, reaching 4.7 times/week in average.
- Users are more fitness with higher income.
- Users plan to walk/run more than 2 times on mileage comparing to other two products.

## Recommendation

1. **Enhance TM195 Marketing and Product Development:**
Given TM195's popularity across all genders and its position as the product with the highest sales, it is recommended to capitalize on its market appeal through targeted marketing campaigns. Additionally, consider exploring product improvements or accessory offerings to increase its usage and appeal, potentially encouraging users to increase their mileage.

2. **Position TM498 for Intermediate Users:**
TM498 users show a tendency to plan for more mileage compared to TM195 users, indicating a slightly more ambitious fitness goal. Marketing strategies should highlight TM498’s suitability for users looking to challenge themselves further in their fitness journeys. Moreover, offering tailored training programs or app integrations that help users achieve and track these increased mileage goals could enhance product value.

3. **Target Niche Marketing for TM798:**
The TM798’s appeal to a specific demographic—predominantly male users with higher fitness levels and income—suggests a niche market strategy. Emphasize the premium features of TM798 that cater to these users' needs, such as advanced tracking capabilities, durability for higher mileage, and integration with high-end fitness apps. Partnerships with fitness influencers or platforms that resonate with this demographic could improve visibility and desirability.

4. **Cross-Sell and Upsell Opportunities:**
Utilize the data to identify potential cross-sell and upsell opportunities between the product lines. For instance, TM195 users showing progress in their fitness goals could be targeted with promotions for TM498 as a next-step product. Similarly, engaged TM498 users demonstrating high usage and seeking further challenges could be prime candidates for TM798 upselling.

5. **Feedback and Continuous Improvement:**
Implement a structured feedback mechanism to gather insights directly from the users of each product line. This feedback can guide continuous improvement in product features, user experience, and customer service. Consider leveraging social media and online forums as platforms for community building and feedback gathering.

6. **Invest in User Experience and Technology:**
Recognizing the varying fitness goals and usage patterns across the product lines, investing in technology that enhances the user experience is paramount. This includes app integrations, virtual training sessions, and personalized fitness tracking. Technology that supports users in achieving their fitness goals can increase product stickiness and brand loyalty.
