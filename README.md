In this project, "Practical Application 1", it was asked to explore the data and utliize the attained knowledge of Planda, Pythons to create statistical summaries demonstrating differences in those (from dataset) who accepted and rejected the coupon.  I've reviewed Bar coupons as per the instruction before the indenpendent analysis and I analyzed cheap restaurant (RestaurantLessThan20) coupon acceptance as part of my indedepdent analysis.  Below is my findings from the analysis and summary how the acceptance can be increased. 

# Before Independent Analysis (For Bar Coupon)
* There are less drivers likely to accept the coupon that goes to the bar less than 3 time compare to that goes to at least once as the acceptance rate dramatically improves for the drivers that goes to the bar at least once.   
* And if the driver is over 25, it adds a ted bit like 1% of accepting the coupon   
* And if the driver has no kids, it adds about another 2% (up to 71.32%).  Additional condition of 'Farming Fishing & Forestry' job would not have been a big impact only 9 people in the dataset would have that job.
* And if the driver is less than age of 30 that goes to the bar at least once increases the acceptance rate along with having no kid and not widowed.
* However, when the additional dataset for the driver that uses the cheap restaurant more than 4 times a month and making less than 50K, the acceptance rate dropped to less than 60%.
* The drivers going to cheap restaurant and making less than 50k look to less likely to accept the coupons
* So, the drivers who goes to the bar at least once automatically increase the chance of accepting the coupon very high close to 70% and adding other conditions like having no kids and not widowed increased the rate a little more.  While the age condition of greater than 25 increased a bit, age less than 30 increased also a bit as well which make it look like age doesn't matter much. 
* To project who would accept the bar coupon, I would target the drivers who go to the bar at least once a month first as a primary target group and more specifically target that do not have kids and are not widowed among drivers within the primary target group.


# After Independent Analysis (For RestaurantLessThan20)
* temperature - 80 degrees is the best time
* time - 2PM and 6PM are the peak time
* expiration - Expiration with 1d is more likely to be accepted/used
* gender - Not that significant difference between male and female
* age - Age between 21 and 26 have the much higher acceptance
* maritalStatus - Other than divorce or widowed, more coupons are distributed and highly accepted.
* has_children - Not affecting acceptance rate significantly whether there is child or not.
* education - "some college - no degree" and "Bachelors degree" has more distribution and higher acceptance
* occupations - Too many occupations, but "sales & related" job stands out and has significant acceptance rate and it's likely because sales folks usually are outside and busy for quick bites.
* income - 25k ~ 62.5k range has more distribution and higher acceptance rates.
* direction - My initial guess was the same direction would have higher acceptance, but it was opposite on this dataset.
* I tried to target the group that would result in over 90% acceptance and here are two groups
* If the driver is going to 'no urgent place' with friend(s) on sunny day over 50 degrees temperature around 2PM lunch time, given coupon with 1 day expiration, the driver has 97% chance of accepting.
* There are few people that actually fall in this category, less than 3% (77/2779), so tried to add more people using difference conditions.
* If the driver goes to cheap restaurant more than 3 times a month and has 'some college - no degree' and coupon was sent around 2pm and 6pm, the acceptance rate goes to 90.10%.  This group of drivers is a little over 6% of the population (173/2779).
* Combining two group resulted in 92.34% acceptance rate and about 9.4% of the population.
* In general when all other factors are combined, you already know that it's about 70% acceptance for RestaurantLessThan20, but you can see which factors can result in higher acceptance rate.
* Within driver group who goes to cheap restaurance, if the drivers go to Restaurant20To50, CarryAway, CoffeeHouse or Bar at least once, then they are likely also to accept the coupons with over 70% acceptance rate.  So the coupons for other restaurants should be sent to this group as well for the 70% acceptance rate.
