In this analysis, I looked at data from the UCI Machine Learning repository with survey data, from Amazon Mechanical Turk, regarding whether a person will accept a certain coupon for a restaurant while they are driving.

The data includes different features regarding users (gender, age, etc.), context to the coupon being offered (weather, time of day, current destination, etc.), coupon information (coupon type and how long before it expires), and whether in that instance that user signalled that they would use the coupon or not.
More information on the data can be found at <a href="https://github.com/mattbenn/Coupon-Acceptance/blob/main/01%20Analysis/01%20Analysis.ipynb">the Jupyter notebook</a>, where I walk through the analysis and visualize findings.

My findings are as follows:
Regarding <b>bar</b> coupons...
<ul>
  <li>Customers who go to bars 3 times or fewer per month reject a coupon to a bar about 60% of the time, whereas customers who go to bars 4 or more times per month are three to four times more likely to accept a coupon to a bar.</li>
  <li>However, customers who are over 25 & go to the bar at least once a month would accept a coupon ~70% of the time, about twice as often as those who do not fit both of these criteria.</li>
  <li>Customers are more likely to accept bar coupons when they have passengers that are not children and they are not in farming, fishing, or forestry.</li>
</ul>
Regarding <b>carry out & take away</b> coupons...
<ul>
  <li>Overall, customers will accept these coupons about 70% of the time.</li>
  <li>Having children and having passengers in the car does not seem to affect these numbers.</li>
  <li>Surprisingly, distance to the restaurant also doesn't affect these numbers. Customers were as likely to claim that they would go to a restaurant 25 minutes away as one 5 minutes away. However, direction of the restaurant did matter when combined with distance; if teh restaurant was at least 5 minutes away and in the opposite direction of where the driver was currently headed, customers were only likely to accept about 65% of the time (down from 75% of the time when the restaurant was only 5 minutes away but in the opposite direction).</li>
</ul>
