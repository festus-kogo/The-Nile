### The Nile

`The Nile` fullfilment agency brings everything you could possibly want straight to your door! Use your knowledge of Python functions and how to manipulate arguments to help automate practices for the biggest world-changing company.

### Not Just A River In Egypt

**1.** At *The Nile* our biggest concern is our consumers, and our biggest cost is delivering their goods to them. We want to develop a program that will help us minimize these costs so we can continue making everyone happy.

First we’ll need to calculate these costs using a function that you’re going to write called `calculate_shipping_cost()`.

Give `calculate_shipping_cost` three parameters: `from_coords`, `to_coords`, and `shipping_type`.

**2.** Both `from_coords` and `to_coords` are tuples, containing first the latitude and then the longitude. Since our `get_distance()` function looks for all four as separate arguments, we’ll need to separate these variables out.

Inside `calculate_shipping_cost` unpack those tuples into `from_lat`, `from_long`, `to_lat`, and `to_long`.

**3.** Now call `get_distance(from_lat, from_long, to_lat, to_long)` and save the result as `distance`.

There’s other ways to separate those two coordinates when calling this function, how would you have done it?

**4.** Next, get the `shipping_rate` by using the provided `SHIPPING_PRICES` dictionary and fetching the key passed in as `shipping_type`.

**5.** Calculate the `price` by multiplying the `distance` by the `shipping_rate`.

**6.** Finally, return the formatted `price`, created by calling the provided `format_price()` on the price itself.