# Amazon_Vine_Analysis

## Overview 
Performed analysis for a company called Sellby. Jennifer, an employee at Sellby and I were tasked to analyze Amazon Reviews written by memebers of the paid Amazon Vine program. The Amazon Vine program is a swervice that allows manufacturers and publishers to receive reviews for their products. Sellby pay a small fee to Amazon and provide the Vine members with products and in return will publish a review. The goal is to determine if there is any bias toward favorable reviews from Vine members. I chose a dataset on furniture reviews. I will perform my analysis and write a report on if I see any bias from my dataset.  I used PySpark, PgAdmin, PostgreSQL and Google Colab along with Amazon web services (AWS). for this project. 

## Results

* Created a dataframe of Vine Users. 

![vine_dataframe](https://user-images.githubusercontent.com/94208810/157161387-efc9cf7d-e855-4af0-b92f-821f6d0d1154.png)


* There were a total of 136 vine reviews and 18603 non vine reviews. With a Grand Total of 18739 Reviews

![TotalNumberofPaidVineUsers](https://user-images.githubusercontent.com/94208810/157161858-d27311ec-ab53-4e24-81c9-80e6e6efd68a.png)

![TotalNumberNOnPaidVineUsers](https://user-images.githubusercontent.com/94208810/157161889-a52719cd-ea9a-4091-b93d-85fca8f906c4.png)


* There were  8,616 5-star Vine reviews. Vine Member 5 star reviews =  74 and Non-Vine Member Reviews = 8542  
![TotalNumPaidVineUsers](https://user-images.githubusercontent.com/94208810/157161344-624504ae-fafa-433b-8ed4-2d3be8b20b1b.png)
![TotalNumofNonPaidVine](https://user-images.githubusercontent.com/94208810/157161229-42faf396-7a33-4a09-a2f3-eac82d08f232.png)

* 54 percent of Vine reviews were five star.
![PerctofPaidVine](https://user-images.githubusercontent.com/94208810/157161455-0ddf06ab-6ad7-464d-a517-d9a0eee41c75.png)

* 45 percent of non-Vine reviews were five star.
![PerctofUnPaidVine](https://user-images.githubusercontent.com/94208810/157161478-0ad16a36-21c9-45cc-bbb1-c3f859343772.png)


## Summary
There seems to be a lean towards a positive bias for reviews in the Vine program for paid vine users.  The results of the analysis show paid Vine Members have a higher percentage of 5 star ratings. We would need to do further analysis to say for sure.  



