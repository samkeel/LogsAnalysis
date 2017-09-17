# Logs analysis

Udacity Logs Analysis project.

## Project Overview

This project is about practicing with data that could have come from a
real-world web server log, including fields such HTTP status codes, articles
and authors.

## Configuration

- Install Virtual box and Vagrant using the default installation options.
- Download the supplied VM Configuration - FSND-Virtual-Machine.zip
- Use a Unix-style terminal Git Bash is recommended.
- Bring Vagrant online by executing the following commands.
```
vagrant up
vagrant ssh
/vagrant
```

1. Download the mock database.
2. Unzip the 'newsdata.sql' file and place it in the /vagrant shared folder.
3. Populate the database by running the SQL file.
```
psql -d news -f newsdata.sql
```

## Running

- Run the program by running news.py:
```
Python news.py
```
