1. SELECT ROUND(AVG(rental_rate), 3) FROM film;

    ![](./images/1.png)

2. SELECT COUNT(*) FROM film
   WHERE title LIKE ('C%');

    ![](./images/2.png)

3. SELECT MAX(length) FROM film
   WHERE rental_rate = 0.99;
   
    ![](./images/3.png)

4. SELECT COUNT(DISTINCT replacement_cost) FROM film
   WHERE length > 150;

    ![](./images/4.png)