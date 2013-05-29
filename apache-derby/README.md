KungFooGallery-Data: Apache Derby Embedded
===================

An Apache Derby Embedded version of the KungFoo Gallery database.

I recommend using Database Visualizer to view the contents. You can download the free version at http://www.dbvis.com/. 

When you create a new connection, choose the "JavaDB/Derby Embedded" driver. In the "Database" field, enter the full path to the kungfoogallery folder, not a file within that folder. Once the connection has been made, go to APP > Table to view the tables. Double-click a table to view its data and other information.

You can only make one connection to the database at a time. In order to connect via ColdFusion or another application server, you'll have to shut down DB Visualizer.
