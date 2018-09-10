# sql-fun-time
BeaverHacks Fall 2018 - Project to set up a Microsoft SQL database, upload csv. sales data and display with a graph.

Goal:

To brain storm and find a better way to display Amazon client(s) sales data in a chart or dashboard for my company. Currently we use Excel files to make pivot tables, etc but I think that using a SQL database would be a vast improvement because we could display the data in new more efficient ways. Also, storing years worth of data in Excel workbooks is not efficient nor safe - we've had dashboards break and lose years worth of data.

Steps Completed:

A. Set up local Microsoft SQL Server
B. Created a new database called "SQL FUN TIME" and a table called "dbo.US - Vendor_A"
C. Created a new table called Vendor_List and added columns
D. Uploaded a .csv file with sales info, PO #'s, Amazon vendor code, ship date and week number

Steps that didn't go so well

E. Had difficulty getting the local sql database to work with node.js and realized that making a graph on a webpage from scratch would be a lot harder than I thought

Improvised steps

F. Found Plotly https://plot.ly/ through searching online and set up their Falcon SQL Client. The free version lets you connect your SQL database to their website and run queries. Once you get connected, their website makes it easy to try multiple ways to display data! You can then share the results through website links or images.
G. Link to the graph I made - didn't turn out the way I wanted, but I know now what to fix: https://plot.ly/~northyg/4/#plot

What I learned:

Even though I didn't get as far as I wanted to, I enjoyed learning about how to set up a server, practicing working with SQL and thinking about how best to display data. I ran out of time, but now that I have a better understanding of how to run queries, I think I will be able to make some helpful graphs in the future!
