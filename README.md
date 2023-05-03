Download Link: https://assignmentchef.com/product/solved-cs341-project-3-sales-database-sql-training
<br>
The project is to write a series of queries against a database containing sales data.  This database contains 4 tables with data about customers, orders, stores, and items in the orders.

I’ve provided templated code for the files I’d like you to submit.  Fill in the SQL in the individual files, and copy those queries into the Proj3ALL.sql file when you are done and ready to submit.

You will be required to use an SQL <strong>join</strong> when retrieving data from more than one table.  You can join tables by putting commas between them in the FROM clause, then including the condition that the primary key matches the foreign key in the WHERE clause.  Alternatively, you can use other forms of joins like the ones discussed in class on 4/8, or nested queries.

Given the importance of database applications, there are numerous tools that generate SQL for you (e.g. from the database schema).  Such tools cannot be used — you are required to write your SQL queries yourself, from scratch.

<h1>Assignment</h1>

For each of the following problems, write a query which retrieves the data containing the answer in Prog3_##.sql, where ## is the number of the question, such as 01.  The basic description of the query can be found here, and the detailed description of the fields and sample output can be found in the template code.




<ol>

 <li>Generate a table containing nicely formatted customer information.</li>

</ol>




<ol start="2">

 <li>Find the contact information for a particular customer. The order will be provided in @oid, be sure that your query does not include the setting of this variable.</li>

</ol>




<ol start="3">

 <li>Filter out only the active orders. It is useful to have a table containing only the active orders so that the company can see what needs to be done.</li>

</ol>




<ol start="4">

 <li>Investigate how long it takes in general (average number of days) for an order to get completed (time from order to shipping).</li>

</ol>




<ol start="5">

 <li>Create a table similar to the one in question 3, limiting the results to only the orders exceeding the average time computed in question 4 and ordered by the time since ordering. The current day will be provided in the variable @today, to produce consistent results for what the output should be.   Do not hard code the value for average time with the value in the data set.</li>

</ol>




<ol start="6">

 <li>For each store, report the Average turnaround (time from order to shipment).</li>

</ol>




<ol start="7">

 <li>For each store, list the percentage of orders which did not ship until after the required_date.</li>

</ol>




<ol start="8">

 <li>For each store and customer pair where more than one order has been made, list the number of orders that customer has made at that store.</li>

</ol>




<ol start="9">

 <li>List the receipt information about each order containing the total list price and discount applied.</li>

</ol>




<ol start="10">

 <li>Identify whether there may be some correlation between the amount ordered and the time it takes to ship the order. Include the average and std deviation of the ratio of these factors.</li>

</ol>




<h1>Electronic Submission and Grading</h1>

The grade reported by Gradescope will be a tentative one.  After the due date, submissions will be reevaluated against a new database to see that the correct answers are still being computed on a new set of data.




When you are ready to submit your program for grading, login to Gradescope and upload all your “Prog3_##.sql” source files, in addition to Prog3ALL.sql, either as a zip or individually.  You have unlimited submissions, and Gradescope keeps a complete history of all submissions you have made.  By default, Gradescope records the score of your last submission, but if that score is lower, you can click on “Submission history”, select an earlier score, and click “Activate” to select it.  The activated submission will be the score that gets recorded, and the submission we grade.  If you submit on-time and late, we’ll grade the last submission (the late one) unless you activate an earlier submission.


