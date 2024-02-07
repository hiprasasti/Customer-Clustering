# Customer-Clustering-
The dataset consist of several information files of the supermarket , such as user_id, aisle, department, and order. The analysis only up to customer clustering using KMeans. (I plan to continus up to cluster persona and market basket analysis though)

# **DataSet**
The dataset consist of several information files of the supermarket , such as user_id, aisle, department, and order. The analysis only up to customer clustering using KMeans. (I plan to continus up to cluster persona and market basket analysis though)

**Data Relation**: https://docs.google.com/spreadsheets/d/1U5FWT15rf95dGdG7Ujc1Zb__08ElQ0UZApw9ZOHqNrA/edit?usp=sharing

**Data Aisles**: https://drive.google.com/file/d/1Tef5EIeW-glO75LvtT3WAaOJO7xMD0Kc/view?usp=drive_link

**Data Department**: https://drive.google.com/file/d/10GJoF6QhTaR6cGJkSgEeFR1W4Qdmbi9J/view?usp=drive_link

**Data Product**: https://drive.google.com/file/d/10GJoF6QhTaR6cGJkSgEeFR1W4Qdmbi9J/view?usp=drive_link

**Data Order**: https://drive.google.com/file/d/1Phzwv5ZUe9jpX7tcJk9AJmQVbwMP6v6e/view?usp=drive_link

**Data Order Prior1**: https://drive.google.com/file/d/1fYRM-SCow7k0vRO3YPL8KynElAJla-yB/view?usp=drive_link

**Data Order Prior 2**: https://drive.google.com/file/d/1nvJrxLTtHJbUmy0uLVa4PuGfKeKSOrP5/view?usp=drive_link

# **Questions**
1. How many customer that shop at the store?
2. How often they shop?
3. What are popular items?
4. Who mostly buy the items?
5. How many customer clusters?
6. What kind of the cluster persona?
7. How recent the customer shop?
8. How frequent their shop?

# **Findings**
+ There are 4 clusters of customers
+ **Cluster 0 or Small Family, or Single parent - 32195**
Profile: **had quite a time for shopping, average frequency and amount. a baby (maybe more kids too), a pet, a working husband, and a home wife, prefer to eat at home (cook/homemade therefore the percentage of bakery, beverages, breakfast, dairy eggs, deli, dry good pasta, frozen are high).**
+ High order in alcohol 87.8%
+ high order in babies 18.8%
+ high order in bakery 15.6%
+ high order in beverages 41%
+ a little bit high in dairy eggs, deli, dry goods pasta
+ High order in frozen food 24%
+ high order in households 35%
+ international goods, pantry a little bit
+ Higher order in personal care
+ higher order in pets
+ avg gap time 16 days
+ lower order count than other
+ lower quantity compare to the average

+ **Cluster 1 or New Family (working parents with baby and pet) - 11736**

Profile: **had the longest range of shopping time, because by once they shop, they prefer to buy in bulk or heavy quantity/amount. New families with babies with pets, order food outside (Uber Eats) occasionally.**
+ lower order in alcohol -37%
+ high order in babies 41%
+ high order in bulk 32%
+ high order in dairy eggs 12%
+ high order in personal care 21%
+ high order in pets 21%
+ a little high order in bakery, produce, snack
+ a little lower in beverages, canned goods, dry good pasta, frozen, household, international, meat seafood.
+ lower gap time than average
+ highest order count and quantity

+ **Cluster 2 or Big Family - 30626**

Profile: **come back in recent days, a short period of shopping time, lowest of frequency (might be influenced by store facilities such as online services, or have other options of store based on discount). Big family, shopping for monthly groceries, priority in family need, such as food and household. the women who do the groceries. kids are already grown up, not a baby.**
+ higher order 25% alcohol
+ high order in beverages 16%
+ high order in breakfast 14.5%
+ high order in  canned goods 12.5%
+ high order in dry good pasta 15%
+ high order in households 48%
+ high order in pantry 13%
+ high order in personal care 30%
+ high order in pets 30%
+ high order in snack 11%
+ a little bit higher in bakery, deli, international, meat
+ lower in babies, bulk, dairy eggs, produce
+ higher than average 66%
+ order count lower than average -67%
+ quantity lower than average -71%

+ **Cluster 3 or Healthy Lifestyle People - 25443 users**

Profile: **single, healthy addict, active in sport (or diet), buys in the short time range, has other options of shopping place, buy in low quantity, as produce goods and meat seafood easily gone bad in a short time, and for bulk goods need time (in 1 month at least).**
- lower alcohol to -75%
- lower order in babies -52%
- lower in bakery 26%
- lower in beverages -47%
- lower in breakfast -37%
- lowe in dairy eggs -16%
- lower in deli -12%
- lower in dry pasta -13%
- lower in frozen -30%
- lower in household -57%
- lower in international -6%
- lowe in pantry -13%
- lower in personal care by 50%
- lower in parts 75%
- lower in snacks -41%
+ high order in bulk 17%
+ a little bit in canned goods, meat seafood,
+ high order in produce 66%
+ a little bit high of avg times
- lower in order count -41%
- lower in quantity -45%
