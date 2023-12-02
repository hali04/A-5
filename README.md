# A-5
CMSC 462 Assignment 5

How to run the code
1.	After extracting the files, open a command prompt and navigate to the 'A-5' folder using the `cd` command.
2.	Once in the 'A-5' directory, activate the pre-configured environment to ensure all necessary libraries are available:
a.	Execute the command: `.\cmsc462assignment5\Scripts\activate`
3.	With the environment active, open the file 'Hasan_Ali_CMSC_462_A_5.ipynb'.
4.	The notebook should display pre-executed output for each cell. However, you have the option to reset and run the code again if needed.
5.	For verification, two files in PDF or HTML format have been provided as evidence that the code executed successfully on my system, in case you encounter any issues.
6.	There's a note at the beginning of the notebook, under the 'libraries' section. If you encounter an error stating “no module named pymongo”, uncomment the line indicated and re-execute the entire notebook.
7.	The notebook includes comments that might address some of your questions or clarify certain parts of the code. 
8.	Run “deactivate” in the command prompt to close environment once you are done
These steps are designed to guide you through setting up and running the provided Jupyter Notebook, ensuring a smooth experience in reviewing and interacting with the code.


Summary of all the data I have added

In this project, a comprehensive series of steps were undertaken to interact with a MongoDB database and perform various data manipulation and analysis tasks:
1.	MongoDB Connection Establishment: Initially, a connection was established with MongoDB, setting the stage for database operations.
2.	Database Deletion for Fresh Start: Any pre-existing database was deleted to ensure a clean slate for the new operations.
3.	New Database Creation: A new database was then created, marking the foundation for storing and managing the data.
4.	Movies Data Insertion: The data from `movies.csv` was read and subsequently inserted into the 'movies' collection of the database, thus populating it with movie information.
5.	Ratings Data Insertion: Similarly, `ratings.csv` was processed to insert rating data into the 'ratings' collection.
6.	Tags Data Insertion: The `tags.csv` file was read, and the data was inserted into the 'tags' collection, enriching the database with additional metadata.
7.	Unique Movies Addition: Five specially selected unique movies were added to the 'movies' collection, expanding the dataset.
8.	Custom Ratings Input: These five movies were given a personal rating, which was then inserted into the 'ratings' collection.
9.	Personal Tags Addition: Custom tags for these five movies were also created and inserted into the 'tags' collection.
10.	Movies Release Year Analysis: An aggregation pipeline was used to analyze and find the number of movies released per year.
11.	Movies Genre Analysis: Another aggregation pipeline helped in determining the number of movies for each genre.
12.	Movies Rating Distribution Analysis: The aggregation pipeline was also utilized to figure out the distribution of movies across different ratings.
13.	Tagged Movies Count: The number of movies that had tags was determined using the aggregation pipeline.
14.	Identifying the Most Popular Tag: Finally, an aggregation pipeline was used to identify the most popular tag among all the movies.
Overall, these steps demonstrate a detailed and methodical approach to managing and analyzing movie data, using a combination of database management techniques and aggregation pipelines for insightful data analysis.


Summary of what I learned while doing the Assignment


This academic exercise provided a comprehensive learning experience in utilizing MongoDB, a prominent NoSQL database system. The assignment encompassed several key aspects of database management and manipulation, offering practical insights into the functionality and versatility of MongoDB.

The initial phase involved establishing a successful connection with MongoDB, a crucial step that laid the groundwork for subsequent database operations. This was followed by the creation of a new database along with its associated collections, demonstrating an understanding of fundamental database architecture and schema design in MongoDB.

A significant portion of the task was dedicated to data handling and integration. This involved reading data from external sources, specifically .csv files, and efficiently importing this data into the newly created MongoDB collections. Such a process is essential for data migration and integration in real-world database applications.

Additionally, the task provided an opportunity to augment the existing data by adding custom entries into the database. This aspect of the assignment not only highlighted the flexibility of MongoDB in accommodating new data but also showcased the practical skills required for database updating and data entry.

The culminating component of the assignment was the application of MongoDB’s aggregation pipeline. This powerful feature of MongoDB was employed to perform complex data manipulations and queries. Through this, a variety of insightful analyses were conducted on the database, such as evaluating data distribution and identifying specific trends and patterns. The use of the aggregation pipeline exemplifies the capabilities of MongoDB in handling and analyzing large-scale data, a critical skill in the field of data science and database management.

Overall, this assignment was a thorough exploration of MongoDB's capabilities, blending theoretical knowledge with practical application. It underscored the importance of MongoDB in modern database management and data analysis, providing a solid foundation for further exploration and proficiency in database technologies.
