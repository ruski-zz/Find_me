Find_Me
=======

Find_Me is a lightweight Python tool designed to discover hidden or common
endpoints on a web server using a wordlist.
It works by sending HTTP requests to possible paths and reporting accessible
endpoints based on HTTP status codes.

This project was created as my first GitHub project, with the goal of learning
Python, HTTP requests, and multithreading.


Features
--------
- Fast endpoint discovery using multithreading
- Simple and clean command-line interface
- Custom wordlist support
- Highlights accessible endpoints (200 OK)
- Beginner-friendly and easy to modify


Requirements
------------
- Python 3.x
- requests library

Install dependency:
pip install requests


Installation
------------

Linux:
------
git clone https://github.com/yourname/find_me
cd find_me
chmod +x find_me
sudo cp find_me /usr/local/bin/

You can now run it from anywhere:
find_me -h


Windows:
--------
git clone https://github.com/yourname/find_me
cd find_me
python find_me.py -h

(Optional)
Add the project folder to your PATH or create a .bat file to use find_me
as a global command.


Usage
-----
find_me -u https://example.com -w wordlist.txt


Options
-------
-u, --url       Target URL
-w, --wordlist  Path to wordlist
-t, --threads   Number of threads (default: 50)


Disclaimer
----------
This tool is intended for educational purposes only.
Use it only on systems you own or have explicit permission to test,
such as CTFs, labs, or local test servers.

Unauthorized scanning of real websites is illegal.


What I Learned
--------------
- Python multithreading (ThreadPoolExecutor)
- Making HTTP requests with requests
- Command-line argument parsing
- Writing cleaner and simpler Python code
- Publishing a project on GitHub


Future Improvements
-------------------
- Status code filtering (200, 301, 302, etc.)
- Save results to a file
- Recursive endpoint discovery
- Better error handling
- Packaging with pip install


Author
------
Created by Ruski
First GitHub project
