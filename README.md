## Introduction
This project is the third project for Udacity's Data Engineering Nanodegree Program. The project aims to test the understanding of Data warehousing concepts. The task includes facilitating the Sparkify start up in setting up a data warehouse that would have the songs data to which the users are listening to. This would help Sparkify analyze the user activities.

The project is written in `python` and uses `Amazon s3` for file storage and `Amazon Redshift` for database storage and data warehouse purpose.


## Database Schema Design

![Our Database looks like the following](https://github.com/hamadalaqeel/data-warehouse-aws/blob/master/Database%20Schema.png)

## Instructions
* Update the `dwh.cfg` file with you Amazon Redshift cluster credentials and IAM role that can access the cluster.
* Run python `create_tables.py` This will create the database and all the required tables.
* Run python `etl.py` This will start pipeline which will read the data from files and populate the tables.
