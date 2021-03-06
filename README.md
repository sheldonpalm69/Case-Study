# The Case Study of NetSpend
![NetSpend Logo](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAS0AAACnCAMAAABzYfrWAAAApVBMVEX////0giAAqNQAo9IAotEAptPF5/PZ7fb0eQCu2uy54/GAx+Oh1On0ewBOutzz+fy+5PHe7/c5sdj6xaXq+Pv1kkdyxuKY1eql2uxaut3B5/J9y+WNzeWw3+/0fg/g9Pn/+fX4uJH64dL4s4fP7PX50bn77OP2pG331cDzhCX0l1T4y7Dzhy70jDz1q3v89O/2oGXykkr3v5z63cyQyN1Ds9dyyuT0x+UEAAAKD0lEQVR4nO2ba2OiPBaAERKlTlGLFnWkiNbetXY62/3/P22BJOR2gsy+Ozo7nOdbmRiSh5NDLoznIQiCIAiCIAiCIAiCIAiCIAiCIAiCIAiCIAiCIAiCnJ98Oy3Y5pdux0V5fJhuNqclPD9lYVQQZh8P52jWn0j+sC8MZFkh4emxodzzPsx6nCzab8/WwD+JhyzqSQlPuaNY/hT2NMKnc7byD+FDl5Bl8Bh7yLKeQfRx5qZenh+WhPAWGI7voVms1NW16HqKbAlZ+GmUenyxnDKx3cr1D1DIFEGjh9cnXKosmF+o4ZcgByLLCq/HW1epwpYZhX8z0wYPH0dW5i2ERyHXetkOnJV9k4fsuSrTFFpF5urOrOuxyUNh4p4Vu3emrSIEp5ftwhn52aChUnHLRuOb22r2fuE+nI+GtMVdiNF4cOau2wv34XyctCVH44crDA+X7cIZaWGrHo2uORfGloYYjdseNBqz7ix+WtmqR6O1CVHZ6s70tKWtYqaaV+Wf7X2IDs232trqZS9Mih1e3Uny7W0VMfTGfvKcab8Jf162B+ektJWF4ctL2LgWZF5EOt9EsqyYX3SCaZRlm8e8PMm5358SJkajl296TFgWbi7a/DMzDV+P9R/PryfWQXJ7Jn/72Gfh4b07Gb7kU99Y3x5OrhvlJmGen7mxF+ctNy9EzcPR3oP2urMHYXN0rgdFeL3oW/Fv+wu19EJMX/f7/Xs9EzgVXr3w9k3++DPszjqxYJtVdrKwd88T/vHHqVlY1HvfloWPD/uoQ6vqQpYceFl0n7OLTXulIn9lh8MhKrV2yFaujbqox3YboPWgkw7Z2hiDTsy/jofWa6IO2bJCKIt4CgdP8rttawsoEeH11nI0dscWuAchTy5ajcbu2Lp3fAvCdxZajcbu2No4Blv0Q5wjnh6NaKuX9djcvvlUv2O2Gs6gxfL51Gjs0Fk19E6sdb3mVZkT78YOfQfh/HyrippWozFq+gj6L+OjKW7qnfim0dihMx/vueHjmUhuzPx0jsZufXh6cAbWx1EpdoSOqUulrxdr+SVwfcFlfU/6cw+G1xGs9a8F/HQmerFPc3Ige3Xp7JXxbqcux5nqdq8XzV469D4UbIxj1+jFGTGfSrbPwu7MS1W2t4qvLGs6rM83hzDKyv9t9vLewcBiPL9GpYQoCvebU3n78W36vpl2LmFpHH9OPzfTh87GC4IgCIIgCIIgCIIgCIJ0gfH6+2S4m40v3Y7/jl0ySm6sq4vlXOvP7grgTi1yV164uxP/xOnr1Q6XfkCCAkLjlfFvjPVAYz2GtJaF1rP1bDZWMMqMJ1D9u7VRSgdqkcqcUErJ0Li6JDSIlb+TqosWfq155oMFAuIrT6LvB5T6nOKu/mpm3HfiExMap0apvl2oZKQVK1pMfNPX+Ksopvw9iI17+V/JpEHWDalaHgy0q+vyKpH36hMfhNa3TihcwqdS+ooYhQph13pvArCKINEKmdVwAtXDqqyJkp3e26S4GqTyb9+siRY3o9+cIbYS5bUSlcNABtw12IuyclEidsgqpIsiKaScaCNj6LhP8KUUcj06eadaO9W7VbVSPmFvANdE6Z3D1jdui6oPpr2t+qGvHCV8Kjq6JqIt5QilfEgGWg5w2dLipu9qDJVlhAeqarZs7VxDhmjBbNvSAtRhC0hKMlXEdWZjNxRFqAgeNlapP7pe3N0trot0X16AYouq9+DtC+SYYraoBVEioo4afRDDtrRaoJ/Ztnz1ZqCtYN430LKCuDivMsbKKlLliGAlh0Z/VMhUnxG3RZPFdc0ijZkc2fzKFl2W//qvknSVrpIkSdXWyDFGFm5brNQokYx8HrjWe8+w5Qfy7QXb2kEVWOyYWfMyyySxdm091F8uzFZgZI1FZafOkMyWWchAyUhqs6HYChbaLydfgTmsJd/4+Kion/s/sdVvsEUd+UDAbC2Mq6OyebQe9H2wkA6zxfsmwxm0dW38NmVpx+qBx20FQ1Z5Xc9vsOVVtmLgBwqwrSrj1fmvvS26ZLpkpjdtwTWx+0FNrWyRaiKiZPrfYeurakNizkc1mmwZsdViJAZ9HiZ1RLez5VWSg7V1XdhifakzPWiLJvO04qpxgeCydc3fd/Eynafzqx2kDbYVUy1NsCy/2gFvmhpma8IGscz0LW2lVO9+jbA19lWh8AxCvGQD2qTLZcvjb2deRzH9WC7MeqAsP2ZTDzkw+to0g1DjTVEx4B0Y80zPyxi2XGOaPY/Uul7bYp7FIzwxO20cBk5bfWPFUmpf6UXYDCJeKnwxyUqFE70xdAk0QsSWNwjUTA/asjtTTaTptwZb3oLIe5+yZb5GNCkuW4ULa4EX+NDsFJguKuFs2PKhdDyoO3DHusUyvWHru8NWThxPQdpSM/0JW/DUjeO25c0SueSpQ0PV5Vz5kCtZyIytkXUfJbbEmoxl+pa2vMoWMNtRbPFsSibOvCVWI42zpgZbha9FEvssb4mgUUPDYYsStbqJ3hgCbbEMlA58yUzf0tb49EhUMz08g1jM1hWNk4BmW9VtZgU3w3nMhCkbQ5Ctcg9F36ea8Bc0x97J9LTYqrs1aG3LsRzRbfFMXzxt2FbTPpmkzeSR347pUCKV29LSVpwYe3qT1vOtodatItO3tDWnju5qtupMD9tqylaS9ra8mTE3EPOtmYL9q0nbuXzd3yuR6VvaYhsAwK11WyLTL+lZbFWTR2W9zG2duE97W3VFvFurMjOftjUHNgAYhi2e6dlA//22YiPN/49tybH0Jbt10takikT3qlqxNZNb1Zat78294DhtpXG8AIqqM4BfsPULecurM30LW2O2Id6wY6PYUnZfrXWi2DZb1UAP2DVBnpNyMqrs2c3m5iz9F2zRVX9ioK6AzNiqlyqArfm6ZjdM+HSQgE/DsiVnokqP9XWisrn7ZVXotFU93WKiReIkKdbVyRdhNwqUxWJ7W/p2NJt4KUFqxpbI9IAtP5AnZHIWCE15IVv1YZdlCwCY1bts1adCbGEOngf8gi2oMTJKrdgSmR6wBcBy6dobe/q6H7DFM716wOC0BeRCl60heMCiHQL+Q1vKys6OLZHp1fmdwxZlUZrudslO71+56DTDjmV69ZRo4Djw9M3jTY8fjhJght33rVU1JfomxKw69W1eK9RHbbb5VC9jNI6/wJSrYE3F0oFZ3qW7f8+NaEiKRGI2bx0XaUDb3rky0oQY58AeUPEACIEXPpNErg/LAUlGpuw5CRy/VUjtzwyqJKrOkJaEEjP37MoEoFW/InoeLqsaiQX8ZD6Zza6MOtbQQutmYG7U3UgGgxv+TQccBbMBsEkrWjxfsmU19ZcpcOf1HbjuMypZaLD1YqqPu0Viv7DH85Fxz0mqMV/0TwT2BShXNP+nXyQhCIIgCIIgCIIgCIIgCIIgCIIgCIIgCIIgCIIgCPJX8B9Z4blBJQS2qwAAAABJRU5ErkJggg==)
## Overview and Origin

* Name of company *NetSpend*

* When was the company incorporated? In 1999 NetSpend was incorporated in Austin, Texas

* Who are the founders of the company? NetSpend was founded by two brothers attending University of Texas, Roy and Bertrand Sosa.

* How did the idea for the company (or project) come about? 
In 1999 the two Mexican immigrant brothers noticed a much need system to allow persons with no access to traditional banking system to still have access to debit cards. 

* How is the company funded? How much funding have they received? The company was reportedly funded with USD 750, form the brother’s personal contribution, after they have established the brothers used the proceeding from the revenues or the sales of pre-paid debit cards until 2010 when the company went public with an IPO, raising 204 Million US$ from sale of 18.5 million common shares.

## Business Activities: Netspend is a reloadable pre-debit card distribution company, with a variety of card options ranging from:
1. Personal Cards & Bank Accounts
2. Payroll Cards
3. Small Business Accounts
4. Skylight One Cards
5. Tip Pooling Accounts

* What specific financial problem is the company or project trying to solve? Netspend cards have been resolving issues for 68 Million underbanked consumers, or with not sufficient credit, and that are not able to open traditional bank accounts, also helping immigrants with no credit build credit to be able to open bank accounts in the future. NetSpend has also resolve small business spending problems with their small business account. 

* Who is the company's intended customer?  Any person with a SSN is able to purchase a prepaid card and activate the account with-in minutes to start enjoying cashless, and touchless purchases. Small Business that will not want to invest in additional banking features to issue employees debit cards. 
Is there any information about the market size of this set of customers? In 2020 the today market for reloadable transactions was 377 Billion US Dollars.
What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?) Netspend has the great advantage to create additional cards for family members with-in one account. This makes it easier to share the one account unlimited. The tip sharing feature is great for hospitality employees to split tips and keep track of the total amounts for tax purposes. Business account feature also gives the employer the power to issue cards for employees with adequate credit and at the same time prevent overspending. Customers can also enroll in the Government stimullouse plan and receive their benefits. With its alliance with Global Payments, NetSpend can offer 

* Which technologies are they currently using, and how are they implementing them? Integratable API’s, to connect with most ERP POS and Digital Solutions. Unified commerce platform, EMV technology, with encryption and tokenization to protect credit card data. NetSpend has created an integration of API’s that links C2C, B2B and P2P. For example, a bar or a restaurant can intergrade the TipSimply API, in their POS, for simple tip booking and process to payroll system: 
https://www.netspend.com/business/tip-network/how-it-works/

. (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.) TipSimply API


## Landscape:

* What domain of the financial industry is the company in? Financial and Banking Services. 

* What have been the major trends and innovations of this domain over the last 5-10 years? In 2011 the company formed a partnership with PayPal expanding the direct deposit program by merging the 300 million PayPal users with the 68 million clients using NetSpend. In 2013, Total System Services Acquires NetSpend for 1.4 Billion US Dollars to further expand the customer base and globalization of the Netspend Card usage. In 2014 a partnership was formed with Western Union the world leader in financial transactions strengthening the brand. In 2016 NetSpend Rebrands and solidifies the lead in the Reloadable Pre-Paid Debit cards and financial services. 


## Results

* What has been the business impact of this company so far? The Sosa brothers has founded and revolutionized the prepaid card industry by increasing its customer base from 100,000 in 2002 to over 10 million in 2020.  Processing a staggering 800 Million in revenues, established 120,000 distribution points In the USA and 130,000 card reloading sites. Along with strategic partners like, Western Union, PayPal, HEB, MLB and numerous more to come. Netspend has made a significant impact to the payment processing market. Today NetSpend trades on NASDAQ as NTSP at USD 15.98 per share, compare to IPO release price of USD 11.03 per share.

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics? Competitors like, Card.com, RushCard, Ingo, CardHub, Kaiku, WorldPay, and simple have all been out perform by NetSpend with the exception of GreenDot. 

* How is your company performing relative to competitors in the same domain? Netspend total revenue for 2020 was a reported 800 Million US Dollars compared, World Pay at 4.1 Billion and GreenDot at 1.18 Billion US Dollars. Remarkably and notably is the fact GreenDot and NetSpend were both were formed in 1999. The diversity of the business partners shows that strategically the partnerships formed by World Pay, and GreenDot has resulted in higher revenues than NetSpend even though netspend raised ten times more fund than GreenDot with their IPO. World Pay raised 500 Million US Dollars with their IPO, managed to gain a large landscape of the market by offering the services cross borders in many countries.  


## Recommendations
Netspend did 20 years of business in the USA only, without considering strategic global partners to penetrate under develop countries with needs of similar services. As a recommendation I would recommend a strategic partnership with Mastercard/ Maestro. Maestro Cards issued and accepted in South America, Europe, and Asia as the main debit card brand. Even though this is a Master Card Product the issuance of the card has different digits that is not recognize by most US based payment systems. A study from statista.com shows just the country Belgium for 2019, had a total of 1.5 Billion Euro in transactions with 100 Million Euro recorded for the Maestro Cards. 

* If you were to advise the company, what products or services would you suggest they offer? NetSpend is inline with most financial services, however with the new spike in crypto currencies I will advise the company to develop a multichain backbone system to offer transactions to and from crypto accounts. I will also advise the company to penetrate international markets and offer their pre-paid debit card program.

* Why do you think that offering this product or service would benefit the company? Most countries works with chartered banking services. As a Global Payment Company, NetSpend can offer their products to these countries for less overhead cost. Most traditional banking system now a days are transaction fee’s dependent, and minimum deposit amounts which are not feasible for most small business owner, or an individual with no credit, and more so if you are an undocumented immigrant with a job. 

* What technologies would this additional product or service utilize? Global Pay system would be the link of choice, because of their already involvement with NetSpend. I will also suggest a KYC company like Global Pass as a customer compliance police. 

* Why are these technologies appropriate for your solution? Simply API and SDK and Token Processors, would help resolve the processing speed of the transactions also a KYC program to resolve and prevent any fraudulent transactions. 




###### References:
https://www.researchandmarkets.com/reports/5116894/prepaid-cards-in-the-u-s-7th-edition?utm_source=dynamic&utm_medium=CI&utm_code=v4k9xf&utm_campaign=1405586+-+United+States+Prepaid+Cards+Market+2020-2024%3a+COVID-19+Pandemic+Reshaping+the+Industry&utm_exec=joca220cid
www.netspend.com


