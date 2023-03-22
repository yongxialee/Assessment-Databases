### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  
  PostgreSQL is a free and open source for database management system.

- What is the difference between SQL and PostgreSQL?
  
  `SQL` is a database management and analysis system which is mainly used for e-commerce, and business. `PostgreSQl` is an object relational database management system which provides support to the extended subset of SQL standards including different transactions, foreign keys, subqueries, triggers, and different user-defined types and functions.

- In `psql`, how do you connect to a database?
  
  \c database_name

- What is the difference between `HAVING` and `WHERE`?

  `WHERE` is used for row's data and filter which rows get include, but not for aggregated data while `HAVING` works on aggregated data and decide which groups if grouped, to keep.

- What is the difference between an `INNER` and `OUTER` join?
  
  `INNER` join will keep only the information from both tables where the rows that match the condition in both tables. 
  `OUTER` join returns the rows that include where an inner join would return but also incudes other rows for which no corresponding match is found in the other table. 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  
  `LEFT OUTER` join is taking all the rows from the first table  combined with matching rows form the second table on the right side.
  `RIGHT OUTER` join is the matching rows from the first table(left side) combined with rows from the seond table(right side) 

- What is an ORM? What do they do?
  `ORM` or Object Raltional Mapping is a technique that lets you query and manipulate data from a database using an object-oriented paradigm.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  AJAX request allows web pages to be updated asynchronously by exchanging data with a web server behind the scenes using javascript. This means that it is possible to update parts of a web page, without reloading the whole page. 
  The library `requests` allows you to send HTTP requests using Python. The HTTP request returns a Response Object with all the response data (content, encoding, status, etc).

- What is CSRF? What is the purpose of the CSRF token?
  
  CSRF or Cross-Site Request Forgrey is an attack that forces authenticated users to submit a request to a Web application against which they are currently authenticated. It's used to secure random token that is used to prevent CSRF attacks. 

- What is the purpose of `form.hidden_tag()`?
  To generates a hidden field that includes a token that is used to protect the form against CSRF attacks.
