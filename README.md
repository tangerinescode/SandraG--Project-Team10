# Reducing the false positives in cyber security


## Contents

- [Submission or project name](#submission-or-project-name)
  - [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
    - [The architecture](#the-architecture)
  
  

## Short description

### What's the problem?

With the digital payments market soaring as the world shifts towards online and card-based
payment methods, comes a growing and pressing issue of cybersecurity and fraud which is now
becoming more common than ever. Because of this, ensuring payment fraud detection is now a
priority for all banks and financial organizations. Track historical data patterns and build a fraud
detection algorithm to prevent abnormal transactions in this scenario. 

### How can technology help?
Optimize cyber security algoritms - Technology to optimize cyber security algoritms and to reduce False positives.

### The idea

Using client data to train a machine learning model, you can decrease the amount of false positives for certain items more accurately in the future, and contribute that your clients are able to purchase what they want without the transaction being declined . I will assume for the purpose of this project that many clients will rather go to their online banking on their phone and add the product/name of the merchindise that they are about to purchase so that specific transaction dont get declined. This project includes a change in the way the banking aplication currently are designed, banks will need to add a feature in their aplication where the client can add the product they about to purchase or the company that they are about to pay so that information is sent to the cyber security software so the system can decided if the transaction needs to be rejected or accepted.  Many merchandisers loose money when the bank reject a transaction because many of those clients dont try again and simply leave the phisical store or virtual store. Banks also loose money beacuse they dont get the fee that they can obtain by running the transaction.
 According to forbes on Jan 11,2022 in its article" Make false positives reduction a new year's resolution" at least 50% of the alerts are false positives. According to David Hemingway in his february 7, 2019 article" how high-tech AI is helping stop real-time payment fraud", states that IBM safer payments which uses AI and real time detection reduced its 90% false positives to 20%. Now it is time for the banks aplication to help to reduce even those numbers. This will need clients to be involve in the process.


## The architecture

![Video transcription/translation app](https://github.com/tangerinescode/SandraG-SLackathon-Project-Team10/blob/main/20221013_212847.jpg)

1. new feauture is add to the bank aplication.
2. Client add the product or name of the company before making transaction.
3. banks has a large data base where a merchandiser are assigned products. If the client choose a product that they are about to purchase and the company that appear in the transaction is related with this product,the probability that the algorithms accept the transaction increase. this is time sensitive so the client has about an hour to complete the transaction that he/she add to the bank aplication.
4. The false positive will decrease as more transactions will be accepted.

## Sources


##Article

"How high-tech AI is helpimg stop real- time paymrnt fraud, David Hemingway, IBM.org

" Make false positives reduction a new year's resolution",Jeffrey Giannetti, forbes.com

##Data Base:

Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015

Dal Pozzolo, Andrea; Caelen, Olivier; Le Borgne, Yann-Ael; Waterschoot, Serge; Bontempi, Gianluca. Learned lessons in credit card fraud detection from a practitioner perspective, Expert systems with applications,41,10,4915-4928,2014, Pergamon

Dal Pozzolo, Andrea; Boracchi, Giacomo; Caelen, Olivier; Alippi, Cesare; Bontempi, Gianluca. Credit card fraud detection: a realistic modeling and a novel learning strategy, IEEE transactions on neural networks and learning systems,29,8,3784-3797,2018,IEEE

Dal Pozzolo, Andrea Adaptive Machine learning for credit card fraud detection ULB MLG PhD thesis (supervised by G. Bontempi)

Carcillo, Fabrizio; Dal Pozzolo, Andrea; Le Borgne, Yann-Aël; Caelen, Olivier; Mazzer, Yannis; Bontempi, Gianluca. Scarff: a scalable framework for streaming credit card fraud detection with Spark, Information fusion,41, 182-194,2018,Elsevier

Carcillo, Fabrizio; Le Borgne, Yann-Aël; Caelen, Olivier; Bontempi, Gianluca. Streaming active learning strategies for real-life credit card fraud detection: assessment and visualization, International Journal of Data Science and Analytics, 5,4,285-300,2018,Springer International Publishing

Bertrand Lebichot, Yann-Aël Le Borgne, Liyun He, Frederic Oblé, Gianluca Bontempi Deep-Learning Domain Adaptation Techniques for Credit Cards Fraud Detection, INNSBDDL 2019: Recent Advances in Big Data and Deep Learning, pp 78-88, 2019

Fabrizio Carcillo, Yann-Aël Le Borgne, Olivier Caelen, Frederic Oblé, Gianluca Bontempi Combining Unsupervised and Supervised Learning in Credit Card Fraud Detection Information Sciences, 2019

Yann-Aël Le Borgne, Gianluca Bontempi Reproducible machine Learning for Credit Card Fraud Detection - Practical Handbook

Bertrand Lebichot, Gianmarco Paldino, Wissam Siblini, Liyun He, Frederic Oblé, Gianluca Bontempi Incremental learning strategies for credit cards fraud detection, IInternational Journal of Data Science and Analytics










