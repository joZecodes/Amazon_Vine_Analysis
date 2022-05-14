# Amazon_Vine_Analysis

## Analysis Overview

The purpose of my project was to select 1 out of 50 reviews and assess the Amazon Vine Member Reviews program in order to determine if there is a bias towards favorable reviews. Manufacturers and publishers can use Amazon Vine to get product reviews. These reviews help them market their products on Amazon, and are helpful to them. 

The dataset I chose is from Amazon reviews of video games sold on Amazon. As a result of these reviews, I aimed to find out if the paid reviews of Amazon Vine programs were correlated with those written by unpaid users (the rest of the users). As a result of this correlation, I will know if there is actually a bias towards favorable reviews from Amazon Vine members.

## Resources
- Data Source: [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Video Games Review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
- Software: Google Colab Notebook, PostgreSQL, pgAdmin, AWS

## Results
### Total number of reviews
- Vine reviews <p align="center">
    <img src="https://github.com/joZecodes/Amazon_Vine_Analysis/blob/main/Total%20paid.png"> 
</p>

<br>

- Non-Vine reviews <p align="center">
    <img src="https://github.com/joZecodes/Amazon_Vine_Analysis/blob/main/Total%20unpaid.png"> 
</p>
<br>

### Percentage of 5-star reviews
- Vine reviews <p align="center">
    <img src="https://github.com/joZecodes/Amazon_Vine_Analysis/blob/main/Vine%20reviews.png"> 
</p>

<br>

- Non-Vine reviews <p align="center">
    <img src="https://github.com/joZecodes/Amazon_Vine_Analysis/blob/main/non%20vine%20reviews.png"> 
</p>
<br>

## Summary
In the Vine program, 51% of the reviews were 5 stars, compared to only 39% in non-Vine reviews. In the Vine program, this describes an optimism bias for reviews.
