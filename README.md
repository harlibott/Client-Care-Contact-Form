# Client Care Contact Form

![Manheim Logo](https://s3-prod.autonews.com/s3fs-public/styles/width_792/public/RETAIL04_160209885_AR_-1_SNSLYZCJWPEE.jpg)

## Introduction
During my 3 months of internship, I was tasked with creating a client care contact form for the Manheim website. Manheim is the worlds largest buying, selling, and trading used cars market. As a Cox Automotive brand, Manheim allows dealers and buyers to go to auctions in-person or online through a live simulcast. Each seller and buyer has their own account where they can sell, buy, and trade their used cars. 

## The Problem
Before this form, Manehim's client care (customer service) for everything related to the website was sent to one single email address. When clicking on the email us link, the website brought up a single blank email where the customer could type in anything they wanted concerning their issue with no guide to follow. This became a problem because client care recieved about 200-300 emails a day concerning issues. Most issues were very vague where the client did not leave any contact information or reference numbers to the issue. So client care asked me to create a form for them requiring the client to fill out all of the neccessary information needed to answer their issue more efficiently. 

## Technical Resources

###### Front End

* Created the visuals of the form using HTML & CSS. Used a company created UI called a MUI (Manheim User Interface) for styling.
* Used JavaScript for validation and error checking.

###### Back End
* Used a service called Simple Email Service owned by Amazons Web Services to send emails.
* Created a Lambda Function in Java to gather the information to send to AWS.
* Sent the lambda we created into an API gateway in AWS.
* Called AWS Simple Email Service to send the filled out email form to client care.
* Supported file uploads up to a certain size by using byte maniuplation and decoding.

###### Deployment and Testing Automation
* Experienced Automation Testing using Ruby's framework Watir.
* Hosted the client care form through AWS in Manheim's Website.

## Demo

https://www.youtube.com/watch?v=EauPXyLnvx8&feature=youtu.be

www.manheim.com
