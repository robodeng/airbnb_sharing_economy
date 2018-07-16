# airbnb_sharing_economy
MIDS Python Bridge Course Final Project

Authors
Collin Reinking (Plotting (folium), Data Pipelining & Analysis)

Robert Deng (Behavioral Segmentation, Data Pipelining & Analysis)

Blake Williamson (Lasso Regression, Amenities Matrix Analysis)

Objectives:

1. Is AirBnB really an example of the ?sharing economy??
2. How do the the listings that ?sharers? post compare to those that ?businesses? post?
3. What features of a listing create value on AirBnB?


1. In our data set, only 62% of the 3,585 listings are listed by hosts with 2 or fewer listings. Thus 38% are what we might consider outside of the traditional ?sharing? economy. Interestingly enough, 11% of all listings belong to hosts with 50 or more properties in Boston. These are no mom and pop operations!

2. Business audiences tend to have more amenities that optimize revenue - luxury (gym, cable, etc), as well as room for additional guests and longer minimum night requirements. Sharers however, have slightly better ratings (93 vs 90) likely due to the local experiences and host interaction that make the Airbnb experience unique to hotels. 

3. Amenities analysis using Lasso regressions, separately of amenities by revenue and ratings yield a 2x2 performance matrix based on the positive/negative signs on coefficients. Amenities that benefit both revenue and reviews include cleanliness, wifi, and bed & breakfast inclusions while amenities that are detrimental to both audiences include having pets on property and bringing pets.