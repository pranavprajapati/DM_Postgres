# Data Engineering Nanodegree by Udacity

## Project: Data Modeling with Postgres


## Introduction

Sparkify is a company that wants to analyze the user activity and song data on their platform. Presently, the data resides in a directory of JSON logs of user activity and another directory of JSON metadata of the songs in the application. Thus they do not have an easy way to query their data. They are looking for a Data Engineer to make this whole process simpler.

## Purpose
Creation of a Postgres database and ETL pipeline to optimize queries so as to help Sparkify's data analytics team.

## Description
The concepts of data modeling with Postgres and building an ETL pipeline using Python were learnt in the Udacity course. Fact and Dimension tables are defined for a star schema and an ETL pipeline is created that moves/transfers data from JSON directories into Postgres tables.

## The Database
There is one fact table called songplays.
There are 4 dimension tables - users, songs, artists and time.

## How to run
Run create_tables.py
Run etl.py to transfer data to tables


### Query examples
1. Which song was released on which year?
2. Where do the most popular artists live?
3. Which are the most popular artists of 2018 ?
 