# SQL
SQL-odevleri 2


select * from film
where  replacement_cost not between 12.99 and 16.99;




select first_name , last_name from actor
where first_name in('Nick','Penelope','Ed');



select* from film
where (rental_rate in(0.99,2.99,4.99)) and (replacement_cost in(12.99,15.99,28.99));
