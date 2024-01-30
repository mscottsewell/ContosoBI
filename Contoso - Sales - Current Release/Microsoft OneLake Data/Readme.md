# Sample Dataverse Sales Report - two flavors
* One version connects to the data in the lakehouse using a Power Query 'native query' (SQL) stored in the report.
* The second version uses views created in the lakehouse, and has a simple reference to them in the report.

Both reports have the same front-end / visuals / data model - it's just a difference in where the queries are stored.  The advantage to the first is that it's 100% self-contained.
  
The advantage to the 2nd is that the queries (Views) can be shared across multiple reports as a curated source for the team/department/company.

It's all a matter of what works well for your scenario.
