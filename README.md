EV Charging Station Usage Analysis
Project Overview

This project analyzes electric vehicle (EV) charging session data to understand how shared charging stations are used in apartment building garages. The goal is to uncover usage patterns that can help property managers improve charging availability, reduce congestion, and make data-driven infrastructure decisions.

Dataset

The analysis is based on a PostgreSQL table named charging_sessions, which contains information about EV charging activity, including:

User identifiers

Garage identifiers

Charging start times

Charging duration

Whether the charging station is shared

The analysis focuses only on shared charging stations accessible to all residents.

Key Questions Answered

How many unique users utilize shared charging stations in each garage?

What are the most popular charging start times (by weekday and hour)?

Which users have an average charging duration longer than 10 hours when using shared stations?

Analysis Approach

Using SQL, the project applies:

Filtering to isolate shared charging stations

Aggregation (COUNT, AVG) to summarize usage behavior

Grouping by garage, user, weekday, and hour

Sorting to identify high-usage patterns

Tools & Technologies

PostgreSQL

SQL (aggregation, grouping, filtering, date/time functions)

Key Insights

Charging demand varies significantly across garages

Certain weekday–hour combinations consistently show higher charging activity

A small group of users accounts for long average charging durations

These insights highlight how even straightforward SQL analysis can surface meaningful patterns from real-world operational data.

Learning Outcome

This project reinforces the value of asking the right questions, working with real datasets, and building consistency through small, focused data analysis projects.
