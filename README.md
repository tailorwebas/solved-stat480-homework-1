Download Link: https://assignmentchef.com/product/solved-stat480-homework-1
<br>
Use RStudio for all exercises, and use either SQL commands or operations on big.matrix objects. Efficiency is important. Use efficient programming techniques discussed in class, and use the data objects we have already created (creating a new database or big.matrix backing file when the data is already available in another format is inefficient because it costs both time and memory).




You should provide one script (a .R or .rmd file) that contains all the code and includes code comments noting which code is for which exercises. You will also need to show and comment on the results, so place the results in a Word (or Open Office or HTML or PDF) document and write sentences to answer the questions, or use knitr to programmatically create your document. <strong>Script files must be the actual script files</strong>, not unevaluated code pasted into some other document.




Include your name in the name for each file submitted (‘&lt;Your-First-Name&gt; &lt;Your-Last-Name&gt; HW#.R’, e.g. ‘JaneDoeHW1.R’).




Any code based on code from elsewhere (e.g. code provided with the text) <strong>must reference in code comments</strong> the source of the original code.




<h1>Exercises for All Students</h1>

<ul>

 <li>This exercise is for aggregate departure delay information for flights from 1987 to 1989 in the data.

  <ol>

   <li>Using SQL, obtain the total number of flights in the data in the 1980s.</li>

   <li>Using SQL, obtain the number of flights with departure delayed by more than 15 minutes in the 1980s in the data.</li>

   <li>Comment on the percentage of flights with departure delayed by more than 15 minutes during that time period.</li>

  </ol></li>

 <li>Now we look at the similar delay information by month during that period. (Note: This is just by month, not by month and year. For instance, flights for January 1987, January</li>

</ul>

1988, and January 1989 will be aggregated together.)

<ol>

 <li>Obtain a table for the total number of flights in our data by month in the 1980s from the data.</li>

 <li>In a separate table, obtain the number of flights by month with departure delayed by more than 15 minutes in the 1980s in the data.</li>

 <li>From the results in parts <strong>a</strong> and <strong>b</strong>, programmatically calculate the percentage of flights delayed by more than 15 minutes by month of year during that time period, and comment on how the monthly rates compare to the overall rate found in exercise 1.</li>

</ol>

<ul>

 <li>Now we look at aggregate flight data for 2007 and 2008.

  <ol>

   <li>Obtain the total number of flights in 2007 and 2008, the number of flights delayed by more than 15 minutes during that time period, and the percentage of flights delayed by more than 15 minutes during that time period.</li>

   <li>Comment on how this delay rate compares with the rate found for the 1987-1989 flights.</li>

  </ol></li>

 <li>Now we look at the delay rate per year for 2007 and 2008.

  <ol start="2008">

   <li>For each year from 2007 to 2008, calculate the number of flights and the number of flights delayed by more than 15 minutes. (You should have counts for 2007 and counts for 2008.) Be sure to use efficient programming techniques.</li>

   <li>Compute the percentage of flights with departure delayed by more than 15 in each of those two years and compare the annual rates with the aggregate rate found in exercise 3.</li>

  </ol></li>

</ul>

<h1>Additional Exercises for Graduate Students</h1>

5) This exercise is to compare delay rates by day of week from 1987 to 1989 with delay rates by day of week from 2007 to 2008 within the data provided.

<ol>

 <li>Calculate the percentage of flights delayed by more than 15 minutes for each day of the week for the period from 1987 to 1989 in the data provided.</li>

 <li>Repeat part <strong>a</strong> for 2007 and 2008 data.</li>

 <li>Comment on similarities and differences in the delay rate on particular days of week between the two time periods.</li>

</ol>