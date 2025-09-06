Social Media Database Project
This repository contains the SQL script for a social media database, designed and implemented by Group 14 as a final project for an IFT/530 course. The database is structured to store information about users, their posts, comments, likes, and friendships, providing a foundation for a fully functional social media platform.

The database can be used for various purposes, including:

User Analysis: Understanding user behavior, preferences, and demographics.

Content Recommendation: Recommending relevant content to users based on their interests and past interactions.

Trend Analysis: Identifying emerging trends and topics.

Platform Improvement: Analyzing usage patterns to improve features and functionality.

Features
The provided SQL script includes all the necessary components to set up and interact with the database.

Database and Table Creation: Creates the Group14 database and defines the schema for the core tables: Users, Posts, Comments, Likes, and Friendships.

Data Population: Inserts sample data into each table for testing and demonstration purposes.

Stored Procedures & Functions: Includes a stored procedure (UpdatePostLikesCount) and a function (GetUserAverageLikes) to perform common data manipulation and retrieval tasks.

SQL Cursor Example: Demonstrates how to use a cursor to iterate through user data and post counts.

Getting Started
To use this database, you will need a SQL Server environment (the script was developed for Microsoft SQL Server 2012).

Prerequisites
Microsoft SQL Server or a compatible SQL client.

Installation
Clone this repository to your local machine.

Open the GROUP14_SOCIAL MEDIA DATABASE_CODE SCRIPT.txt file in your SQL client.

Execute the entire script.

The script will automatically perform the following actions:

Create the Group14 database (if it doesn't already exist).

Create all necessary tables with their respective columns and constraints.

Populate the tables with sample data.

Schema Overview
The database schema is organized into five main tables:

Users: Stores unique user information, including username, email, and personal details.

Posts: Contains details about each post, such as the content, the user who created it, and timestamps.

Comments: Tracks comments made by users on specific posts.

Likes: Records which users have liked which posts.

Friendships: Manages the relationships between users.

Authors
Preksha Joshi

Yogitha Putluri

Let me know if you would like to expand on a specific section of this README, or if you need any other files for your project.
