# s3zipdownload
Java program to download a zipped (.gz) file from an AWS S3 bucket, unzip the file, read the csv 
and perform the following operations on the CSV data

-count all the users
- count the number of devices with resolution 640*960
- total amount spent by all users
- first user who joined the organization
-

The program was written in Java, using JAVA 7.
Install java and run the program from command prompt

The program accepts one input parameter as the address to the S3 bucket.
example : java Zipdownload "http://s3.amazonaws.com/brightfuture/mydata.csv.gz"



