
# Case Study #3 - Foodie-Fi

![Foodie-Fi](images/Week03.png)


## Entity Relationship Diagram (ERD)

![Week 03 ERD](images/Week03_ERD.png)


## Schema
You can access the schema's file [here](schema).


## Case Study Questions

### A. Pizza Metrics
1. How many pizzas were ordered?
2. How many unique customer orders were made?
3. How many successful orders were delivered by each runner?
4. How many of each type of pizza was delivered?
5. How many Vegetarian and Meatlovers were ordered by each customer?
6. What was the maximum number of pizzas delivered in a single order?
7. For each customer, how many delivered pizzas had at least 1 change and how many had no changes?
8. How many pizzas were delivered that had both exclusions and extras?
9. What was the total volume of pizzas ordered for each hour of the day?
10. What was the volume of orders for each day of the week?

You can find my PostgreSQL script [here](Aweek02).


### B. Runner and Customer Experience
1. How many runners signed up for each 1 week period? (i.e. week starts 2021-01-01)
2. What was the average time in minutes it took for each runner to arrive at the Pizza Runner HQ to pickup the order?
3. Is there any relationship between the number of pizzas and how long the order takes to prepare?
4. What was the average distance travelled for each customer?
5. What was the difference between the longest and shortest delivery times for all orders?
6. What was the average speed for each runner for each delivery and do you notice any trend for these values?
7. What is the successful delivery percentage for each runner?

You can find my PostgreSQL script [here](Bweek02).


### C. Ingredient Optimisation
1.	What are the standard ingredients for each pizza?
2.	What was the most commonly added extra?
3.	What was the most common exclusion?
4.	Generate an order item for each record in the customers_orders table in the format of one of the following:
5.	Meat Lovers
6.	Meat Lovers - Exclude Beef
7.	Meat Lovers - Extra Bacon
8.	Meat Lovers - Exclude Cheese, Bacon - Extra Mushroom, Peppers

You can find my PostgreSQL script [here](Cweek02).

### D. Pricing and Ratings
1.	If a Meat Lovers pizza costs $12 and Vegetarian costs $10 and there were no charges for changes - how much money has Pizza Runner made so far if there are no delivery fees?
2.	What if there was an additional $1 charge for any pizza extras?
a.	Add cheese is $1 extra
3.	The Pizza Runner team now wants to add an additional ratings system that allows customers to rate their runner, how would you design an additional table for this new dataset - generate a schema for this new table and insert your own data for ratings for each successful customer order between 1 to 5.
4.	Using your newly generated table - can you join all of the information together to form a table which has the following information for successful deliveries?
a.	customer_id
b.	order_id
c.	runner_id
d.	rating
e.	order_time
f.	pickup_time
g.	Time between order and pickup
h.	Delivery duration
i.	Average speed
j.	Total number of pizzas
5.	If a Meat Lovers pizza was $12 and Vegetarian $10 fixed prices with no cost for extras and each runner is paid $0.30 per kilometre traveled - how much money does Pizza Runner have left over after these deliveries?

You can find my PostgreSQL script [here](Dweek02).


### E. Bonus Questions
If Danny wants to expand his range of pizzas - how would this impact the existing data design? Write an INSERT statement to demonstrate what would happen if a new Supreme pizza with all the toppings was added to the Pizza Runner menu?

You can find my PostgreSQL script [here](Eweek02).