# Data Management Systems --- SMM695
Databases are always there, even if you do not know. Searching for a product on
e-commerce, writing a message to a friend, or looking for a paper to cite in
your thesis, you are interacting with a database. For this reason, databases are
a fundamental component of the digital era, and this is also why it is worth
knowing their basic functioning.

Through the years, the world of databases has faced several developments with
always new approaches to structuring, storing, and interacting with data. From
the relational model to more flexible systems, the journey of databases is in
constant evolution. 

## Instructor
**Name**: Matteo Devigili, Ph.D. Student

**Contacts**: matteo.devigili.2@city.ac.uk

**Lecture**: Tuesday --- 09:00 - 10:50 (room 2002)

**Office hour**: Tuesday --- 11:00 - 13:00 (face-to-face or Zoom)

## Module Overview
This module focuses on storing, querying, and manipulating data. In
particular, we will discuss [PostgreSQL](https://www.postgresql.org) (a
prominent, advanced, and open-source relational database) and
[MongoDB](https://www.mongodb.com) (a schema-free database especially useful
with evolving streams of data). In the last week, a more exploratory lecture
(not strictly required to complete the final coursework) will drive you through
[Apache Spark](https://spark.apache.org) (a cluster-computing framework that
can scale SQL, machine learning, and network analysis pipelines) leveraging
on [PySpark](https://spark.apache.org/docs/latest/api/python/index.html#).

## Materials & Readings
For this course, you do not have to buy any book, but you need to go through
the following:

* Lecture slides (to be uploaded onto Github weekly);
* SQL/JS/Python scripts (to be uploaded onto Github weekly).

Furthermore, I will provide you with some _not mandatory and not rated homework_
to test your understanding of the lecture. 

The following references concern additional material you may be interested:
* PostgreSQL:
  * [PostgreSQL Documentation](https://www.postgresql.org/docs/14/index.html)
  * [PostgreSQL: Up and Running](http://shop.oreilly.com/product/0636920052715.do)
* MongoDB:
  * [MongoDB Manual](https://docs.mongodb.com/manual/)
  * [MongoDB: The Definitive Guide](http://shop.oreilly.com/product/0636920049531.do)
  * [MongoDB in Action](https://www.manning.com/books/mongodb-in-action-second-edition)
* PySpark:
  * [Learning PySpark](https://link.springer.com/book/10.1007%2F978-1-4842-4961-1)

## Learning Objectives and Assessment
At the end of the module, students should be able to:

* design a relational database with PostgreSQL
* design a schema-free database with MongoDB
* interact with and manipulate data in both PostgreSQL and MongoDB
* design and execute scripts providing useful insights on data

In terms of assessment, students are required to deliver one group-level
coursework project (so, _no final examination or individual assignments_).

The **final course project** will be launched in week 5, and submissions will
be evaluated on a rolling-based window and are due by July 22 (4:00 PM London
Time). Students will be required to deal with real-world data from scratch, thus
implementing what learned during this module.

Both projects will be evaluated along with the following criteria: i)
appropriate use of notions and frameworks discussed in class; ii) effectiveness
of the proposed answer or solution; iii) appropriate explanation of the proposed
solution; iv) organization and clarity of submitted materials. All criteria
carry out an equal weight in terms of the mark.

## Organization of the Module
The following table shows the schedule of the module. Based on students'
progress throughout the module, the topics included could suffer from some 
**minor changes**.

Each _**Friday** at 12:00 PM London time_, students will be provided with a
video recording of the lecture (around 60 minutes long). Also, at the [course
GitHub repo](https://github.com/mattDevigili/dms-smm695), lecture slides, code
scripts, data, and homework will be  uploaded.

Each _**Tuesday** from 09:00 to 10:50 AM London time_, an interactive in-person
lecture will be held. Hence, students have 3 full days to go through the video
recording and the uploaded materials. In the first part of the class, I will
provide a recap of the video recording and answer students' questions concerning
the topics covered. **Note**: students are invited to share their questions via
email the day before the webinar (by 8:00 PM London time). In the second part, I
will discuss some further applications of the topic covered. 

To recap:
* _MS Teams_ is the main communication channel
* _GitHub_ is where you can find all relevant material
* _Room 2002_ hosts webinar sessions

| Week (dd-mm) | Agenda         | Topics                                             |
|--------------|----------------|----------------------------------------------------|
| 1 (24-05)    | **PostgreSQL** | Introduction to RDMS                               |
|              |                | PostgreSQL (psql and pgAmin4)                      |
|              |                | Installation                                       |
|              |                | Create (Database, Schema, Table)                   |
|              |                | Data types:                                        |
|              |                | --- Numeric                                        |
|              |                | --- Monetary                                       |
|              |                | --- Character                                      |
|              |                | --- Date and time                                  |
|              |                | Drop (Database, Schema, Table)                     |
| 2 (31-05)    |                | Constraints:                                       |
|              |                | --- Not Null                                       |
|              |                | --- Unique                                         |
|              |                | --- Primary Key                                    |
|              |                | --- Check                                          |
|              |                | Import data                                        |
|              |                | Basic SQL                                          |
|              |                | Aggregate functions                                |
|              |                | Grouping                                           |
| 3 (07-06)    |                | Foreign Key                                        |
|              |                | Joins:                                             |
|              |                | --- Inner                                          |
|              |                | --- Left/Right/Full (Outer)                        |
|              |                | --- Cross                                          |
|              |                | Export data                                        |
| 4 (14-06)    | **MongoDB**    | Introduction to MongoDB                            |
|              |                | Installation (Mongo Shell, MongoDB Compass, Atlas) |
|              |                | CRUD operations:                                   |
|              |                | --- Insert                                         |
|              |                | --- Find                                           |
|              |                | --- Update (Replace)                               |
|              |                | --- Delete (Drop)                                  |
| 5 (21-06)    |                | Load data                                          |
|              |                | Query and Projection Operators                     |
|              |                | Introduction to the _Aggregation Framework_        |
|              |                | Data Export                                        |
| 6 (28-06)    | **PySpark**    | Introduction to PySpark                            |
|              |                | Connection to PostgreSQL and MongoDB               |
|              |                | Regression module                                  |
|              |                | NLP examples                                       | 


## Software requirements
During the course, students will be guided to install:
* [psql](https://www.postgresql.org/docs/14/app-psql.html) and [pgAdmin4](https://www.pgadmin.org) to explore PostgreSQL;
* The [mongo shell](https://www.mongodb.com/download-center/community) and [MongoDB Compass](https://www.mongodb.com/products/compass) to explore MongoDB.

We will also interact with [Amazon RDS](https://aws.amazon.com/rds/) and [MongoDB Atlas](https://www.mongodb.com/cloud/atlas),
so please be sure to have a stable internet connection. 

To follow the lectures in _week 2, 4, 6_ and _webinars_, you need to run Python >= 3.7. The
easiest way to do that is to install [Anaconda](https://www.anaconda.com/products/individual).

## Version history
* Created: Wed May 13 15:10:14 BST 2020
* Last Changed: Sat 14 May 2022 15:34:39 BST