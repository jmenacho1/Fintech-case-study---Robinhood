![Robinhood.Image](


# Robinhood - A Fintech Case Study

---

## "Empowering the Individual Investor"
 
---

## Overview and Origin

Robinhood in an online brokerage company that was founded with the thought that individual investors could be emowered through clean mobile-focused user interface, low fees, and *"outside-the-box"* investment tools.  The firm was founded by two former Stanford Univertity roommates who - after trying their hand in New York's finance industy - saw a clear need to create an individula investor-targeted online brokerage offering.  

Vlad Tenev and Baiju Bhatt lived and worked in New York after college and started up two companies in a short amount of time. The first wwas an algorithmic trading company called Celeris and the second one was a financial software company called Chronos Research. [^1]  Seeing first-hand that institutions were paying little for trades relative to individual investors and that the online technology and research afforded to this investor class was lacking.

Robinhood was incorporated on April 18, 2013 and their initial funding was $3 million. [^2]  After their May 2020 $280 million funding they have now raised $1.2 billion over  eight separate funds which gets them to an $8.3 billion valuation. [^3] The most recent yearly (2018) revenue estimate was $100.6 million. [^4}

## Business Activities:

The company has tried to even the playing field for the younger, less-established investor class as it relates to competitive fees as well as research and trading tools.  The driving force for the firm's founding was a belief that the young individal investor has been at a competitive advantage as it relates to the above.  
Tading in equities, options (non-margin), and crypto is free with no minimum balances.  In addition, in late 2018 and into late 2019, Robinhood sought to get into personal banking in an atempt to expad thier footprint in this demographic's finances.  During this time they were supposedly close to aligning with Ohio-based Sutton Bank where they would issue debit cards to customers and a supposed 3% annual interest rate to be given for bank depostis.  These deposits were to be SPIC-insured but the SPIC denied this. Robinhood had to wait until December 2019 to launch a "cash management" FDIC-backed product that would give customers a 1.8% rate on cash held at Robinhood. [^5]  

The age grouping that the firm has the most traction with is 28 to 41 years old. [^6]  In December of 2019, Robinhood signed up their 10 millionth custonmer. [^7]. Tenev was on televsion in late_april saying that Robinhood has been getting 50% of the national new brokerage accounts which is more then all the legacy players put together. [^8]  If it assumed that the company desires to be the one-stop shopping for all things financial for the  *"millennial"* generation (Ages 18 to 34) then there is more share to be gained for Robinhood as there are currently 75 million millennials in the US as of 2015. [^9]


The company's competitive advantage is the fact that they were one of the *"first movers"* with the commission free trading platform and as a result they garnered a lot of insight into the investing methods and tendencies of smaller investors. [^10]  They are looked at as a "free" platform and is the appeal from a branding ppoint of view when potential customers are wanting to deploy money. The interface is very easy to use and is very sleek and that appels to millennials versus using one of the stodgey offerings ogf the legacy players in the space. Robinhood has some pretty cool features where they have "leaderboard" and "popularity changes" which show the most popular holdings of Robinhood customers over various holding periods. The below shows the stock (ticker: AAL) and the pink line shows the stock's price while the green line shows the collective holdins og Robinhood members. This is obviously proprietary in nature as it is their userbase that is creating the graphical representation of holdings. 




![AAL.robinhood](AAL.robinhood.JPG)




**Robinhood Millennial Customer Checklist**

- [X] Free-ness
- [X] Sleek, Coolness Factor
- [X] Unique Proprietary Tools


Well so then how does Robinhood make money? They make money on cash balances, margining, and small money on customer deposits if they can use them to get a higher yield elsewhere. Back in October of 2018 they allowed that they were making almost half their revenues in payment for order flow.  That is, third-parties that pay Robinhood for their order flow so that they can dictate which routes the orders will be executed at. Meaning that the third party takes some sort of spread on a given trade to the detriment of the customer. It was discovered that Robinhood was entering into these transactions to the tune of sixty times more. [^11][^12]

Robinhood is using some neat technology infrastructure in its leading FIntech offering.  They run a nightly batch process where they reconcile all customer trades for that day and its an arduous task.  They run these batch processes against single Postgres database (an open-source database management system (RDBMS)) and it used to take hours.  Their software engineers were able to address the shortcomings in the Postgres' structure and detected bottlenecks that they addresses which resulted in ten times faster processing speed.  They did not have to change any code to make this happen. [^13][^14]

They use Kafka to synchonize data messaging between all their independant microservices and databases. Their back-end achitectre is flexible to plug in additional microservices but the Kafka helps to make sure all scenarios are accounted for which is particularly important when there is the back and forth processig of sustomer money.



## Landscape:


Industry Players | Favorable attributes
---------------- | --------------------
TD Ameritrade | BEst for beginners
Fidelity | Best Research Experience
Charles Schwab | Best for IRA accounts
E-Trade | Best Web Platform
Interactive Brokers | Best for Professionals
TradeStation | Best Platform Technology



The trajectory of the online brokerage industry over the last twenty years has been one that has had various levels of success in trying to attain its ultimate goal: empowering the individual investor to make to be able to make their own investing decisions in an inexpensive fashion.  The industry has been one that has pushed the technoogial boundaries of the Fintech realm for the better part of twenty years.  Over the last 5 to 10 years there have been continuous tweaks lower to the fee/commission system to the benefit of the customer. Additionally, real-time quotes are now the norm rather than a paid-for expense. Technology offerings such as multi-study charting capabilities and valuation metrics have come a long way since the days of retail customers using yahoo finance to go along with a delayed quote trading system.




![Steam](Steam.JPG)





The online brokerage industry is a Fintech industry that has undergone massive changes in the last year. Much of these changes occured after the industry saw several of its players try to differniate themselves by offering customers slightly varied platforms that provided things such as naunced research products and low to no fees on products such as ETFs.  In the fall of 2019, large player, Interactive Brokers, sought to gain market share by taking commissions to zero on ETF trades in their IB *"Lite"* service. [^13] 

This *"race to zero"* on fees in the back half of 2019 led to a massive consolidation 

In the last handful of years the industry has become very fragamented as players tried to differentiate themselves by offering different things to customers.

The second half of 2019 saw the industry try to come up with ways to ramp trading activity as online customers (read retail) keenly took their money out of the market as the market ground slowly to all-time highs.



* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?

* How is your company performing relative to competitors in the same domain?


## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

* Why do you think that offering this product or service would benefit the company?

* What technologies would this additional product or service utilize?

* Why are these technologies appropriate for your solution?

---

**Footnotes**

[^1]: [Tech Crunch](https://techcrunch.com/2013/04/18/robinhood-app/?_ga=2.116074886.1805704415.1593219206-71989368.1593219206)
[^2]: [Forbes](https://www.forbes.com/sites/halahtouryalai/2014/02/26/forget-10-trades-meet-robinhood-new-brokerage-targets-millennials-with-little-cash/#57a27c5a7f48)
[^3]: [Craft](https://craft.co/robinhood/funding-rounds)
[^4]: [Growjo]9https://growjo.com/company/Robinhood#:~:text=Estimated%20Revenue%20%26%20Financials,venture%20funding%20in%20May%202018.&text=Robinhood's%20total%20funding%20is%20%24539M.)
[^5]: [CNBC Robinhood](https://www.cnbc.com/2019/10/08/robinhood-makes-second-attempt-at-launching-a-high-yield-account-similar-to-banks.html)
[^6]: [Nasdaq Robinhood](https://www.nasdaq.com/articles/robinhood-millennial-obsession-2018-08-23)
[^7]: [Blog Robinhood](https://blog.robinhood.com/news/2019/12/4/ten-million-thanks)
[^8]: [Marker Medium](https://marker.medium.com/how-robinhood-convinced-millennials-to-trade-their-way-through-a-pandemic-1a1db97c7e08)
[^9]: [Brookings](http)s://www.brookings.edu/research/millennials/)
[^10]: [Quora](https://www.quora.com/What-s-the-advantage-of-Robinhood)
[^11]: [Bloomberg](https://www.bloomberg.com/news/articles/2018-10-15/robinhood-gets-almost-half-its-revenue-in-controversial-bargain-with-high-speed-traders)
[^12]: [WSJ.com](https://www.bloomberg.com/news/articles/2018-10-15/robinhood-gets-almost-half-its-revenue-in-controversial-bargain-with-high-speed-traders)
[^13]: [RH Engineering Blog](https://robinhood.engineering/robinhood-hosts-its-first-tech-talk-eb01e35f239f)
[^14]: [Stackshare](https://stackshare.io/kafka)

[^10] [Marker Medium](https://marker.medium.com/how-robinhood-convinced-millennials-to-trade-their-way-through-a-pandemic-1a1db97c7e08)






