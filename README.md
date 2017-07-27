# codechef-crawler
A web crawler that can download all successful submissions of a user in Codechef. Just provide the username.

Usage Instructions:
===================
1. Download CodechefCrawler.jar from the repository.
2. $ java -jar CodechefCrawler.jar \<username\>
3. Java 8 is must.

Example:
=========
$ java -jar CodechefCrawler.jar flappy

Features:
==========
1. Retries fetching code, if it fails (upto 5 times).
2. Fetches the single best solutions for a problem submitted by the user.
(An AC submission with best score, minimum time and minimum memory usage)
3. Makes separate directories for every contest, and saves the associated submissions in the corresponding directories.
4. It times the entire process, to give exact runtime of the crawling performed.
5. Provides clear output statements to keep the user aware about progress being made, while downloading solutions.
6. Supports downloading JAVA, CPP, C and PYTHON codes, since these are the most used.
   Rest are downloaded as txt files.
