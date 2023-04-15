# Assigment-5.1

"Prompt.inyb" file submitted has solutions for the promted questions as well as additional analysis performed on "Coupons for Coffee House"

Functions created 
- percent_accept: Since ratio of prospects who used the coupon vs. who didn't was the primary metrics thus, to estimate it again and again, created a function as 
  count of prospects for which Y =1 over total number of prospects in that dataset 

Following is the summary of analysis of Coupns for "Coffee House":
- Desitnation have impact on coffee coupon acceptance. Coupon acceptance is better when cutomer is not in "Hurry" and much lower if they are going to Home or Work.
- Weather has some impact on coffee coupon acceptance. Coupon acceptance is better when it's "Sunny" or "Rainy" weather instead of "Snowy"
- Time is having significant impact on Acceptance rate. Better acceptable rate in Morning and Afternoon than late evenings or night.
- If customer is not within 15 mins distance of coupon place than acceptance rate of coupon is higher and need to add effect of direction of travel
Another Hypothesis I tested : Would Price senstive customer (who spend less than $20 in a visit) and are frequent dinners (>4 times a month) have high chance to accept than others and answer is "Yes"

Next Steps: 
1) Since most of the analysis was done with only factor at a time thus, recommended next step is to  expand the analysis to include multiple factor analysis to better understand interaction between factors.
2) Expand the analysis to coupon categories other than "Bar" and "Coffee House" and use more advanced statistical techniques like 2 t-tests to validate if % difference between 2 categories is statistically different.
