# Google Dorks Simplified

A simple explanation of google dorks, its uses and collection of best google dorks to get the best and desired information.

## Some of our useful products for OSINT loves -
[OSINTverse](https://osintverse.com) is an OSINT ecosystem, Your go-to place for anything related to OSINT — tools in [SearchIn](https://osintverse.com/searchin), blogs and webinars on the Hub, and the community in the open. 
SearchIn is a fully fledged investigation workspace — not a bookmark list. Start from an identifier, query every provider we integrate in one UI, compare structured results, and keep the trail in a case you can reopen. Prepaid credits. Your wallet or a shared team wallet.


## Authors

- [@dheerajydv19](https://twitter.com/Dheerajydv19)

## Documentation

[1. What are Google Dorks ](#what-are-google-dorks)

[2. How Google Dorks works](#how-google-dorks-works)

[3. Why we need Google Dorks](#why-we-need-google-dorks)

[4. What can we find from Google Dorks](#what-can-we-find-from-google-dorks)

[5. How to use Google Dorks](#how-to-use-google-dorks)

[6. Collection of Most Useful Google Dorks](#collection-of-most-useful-google-dorks)

[7. Special Collection for Cybersecurity Learners](#special-collection-for-cybersecurity-learners)

[8. Special Collection for bug bounty hunters](#special-collection-for-bug-bounty-hunters)

[8. Special Collection for sql injection](#special-collection-for-sql-injection)

[9. How to safeguard information from Google Dorks](#how-to-safeguard-information-from-google-dorks)

[10. Faqs](#faq)

### Disclaimer
This tutorial is for informational and educational purposes only. We believe that ethical hacking, information security and cyber security should be familiar subjects to anyone using digital information and computers. We believe that it is impossible to defend yourself from hackers without knowing how hacking is done.

## What are Google Dorks

 Google Dorks, also known as Google dorking or Google hacking is a hacking technique which is  used to find the best desired search results without wasting time in exploring google for required information.
Normally, google dorks is used by researchers or hackers to find critical information about a company, individual, a software or app, a research topic or anything else.
But a normal person can also use google dorks in many places and can save time and will definitely get better information.

## How Google Dorks works

As you all know, Google crawls almost all websites and indexes almost everything available on that website including some sensitive information.
That simply means google exposes too much information about websites including the technologies used, username, passwords, and some other general vulnerabilities.

By using some simple techniques which we call google dorks, we are just exploring that sensitive information.
Apart from this, by using google dorks, we can also help google to understand more about what search results we are expecting from google.

## Why we need google dorks

Everyone uses google dorks for a different purpose. Below are some of the most common reasons for using google dorks -

- cybersecurity experts uses google dorks to find critical information which gets exposed by mistake or exposed by someone knowingly about anything so that they can later on hide or delete that so that no one can use that for any wrong purpose.
- researchers, content writers, journalists ,etc uses google dorks to gather all the information available on google about a particular topic so that they can use that information for reaching their own goals.
- students mainly uses google dorks to find answers to their questions which are from their textbook or asked by someone or for finding leaked versions of a course or a book for free.
- companies and their employees uses google dorks to gather information about their competitors and for finding honest reviews of their products or services so that they can use that information further for improving their products and services and which in results helps their company grow faster.

## What can we find from Google Dorks

Google dorks can be used to find a variety of information in many aspects but it mainly used to find the information described below -

- critical information of a website, company, organization, softwares
- blogs, articles, research papers, etc on a particular topic
- leaked courses and ebooks
- reviews about a company, it's product and about it's services
- finding solutions of answers of textbook questions

Apart from these, there exist many other kinds of information which can be found via google dorks very easily.

## How to use Google Dorks

Let's learn this by an example.
While searching for any free ebook , once add filetype:pdf in your google search box along with book name and in results google will only show you only those search results which have a pdf with the same name as you typed in the search box.
For a better understanding, once try this on your own.

#### Note -
Also for the betterment of our users, we have shown examples of what and how you should type search queries in google.

## Collection of Most Useful Google Dorks

| Google Dork |      | Used for               |Example |
| :-------- | :------- | :------------------------- | ----------- |
| "specified_phrase or statement" | | shows only those pages that contains exact word or statement |"Is hacking illegal" |
| site: | |removes search results from all other websites except the mentioned one | site:amazon.com smartwatches  |
| inurl:specified_phrase | | shows only those search results which contains the specified word in url | inurl:ethical hacking
| inurl:word1 word2 | | shows search results that contain either of the word or both | inurl:hacking programming |
| allinurl:word1 word2 | | shows the search results that contain both of the words | allinurl:hacking programming |
| intitle:word1 word2 | | shows those search results that mention word in their title and mention the word “word” anywhere in the document | intitle:hacking networking  |
| cache: | | shows the website homepage even if website is down | cache:netflix.com |
| intext:word1 | | shows only those pages containing that specific word (or words) somewhere in the context | intext:bug hunting |
| allintext:word1 word2 | | only shows pages containing those words somewhere in the context | allintext:hacking networking |
| intitle:”index of” | | shows open ftp servers | intitle:”index of spiderman movie” |
| inurl:view/index.shtml | | shows live cameras that don’t have any protection | inurl:view/index.shtml |
| filetype:pdf/doc/ppt specified_phrase | | shows only pages that contains the document of that type and contains specific word in file name | filetype:pdf ethical hacking |
| + | | shows only those pages that must contain that specific word | ethical hacking + free course |
| - | | avoid showing results that contain certain words | ethical hacking - paid course |

## Special Collection for Cybersecurity Learners

| Google Dork |      | Used for               |
| :-------- | :------- | :------------------------- | 
| intitle:”index of” | | shows open ftp servers |  
| cache: | | shows the website homepage even if website is down |
| inurl:view/index.shtml | | shows live cameras that don’t have any protection |
| login: *password*filetype:xls | | shows password list of some random websites | 
| allintext:username filetype:log | | shows log files of random websites | 
| inurl:/proc/self/cwd | | used to detect vulnerable or hacked servers | 
| intitle:"index of" inurl:ftp | | shows open ftp servers | 
| filetype:xls inurl:"email.xls" | | used to find database of emails | 
| intitle:"Index of" wp-admin | | used to find wordpress login page of random websites  | 

If you want to know about some more google dorks used in cybersecurity, then we suggest you explore Google Hacking Database.

https://www.exploit-db.com/google-hacking-database

## Special Collection for Bug Bounty Hunters
List of Google Dorks to search for companies that have a responsible disclosure program or bug bounty program which are not affiliated with known bug bounty platforms such as HackerOne or Bugcrowd.

- [Click Here](https://github.com/InfuriousICC/Google-Dorks-Simplified/blob/main/bug%20bounty%20dorks)

## Special Collection for Sql Injection
Nice list of google dorks for SQL injection

- [Click Here](https://github.com/InfuriousICC/Google-Dorks-Simplified/blob/main/google%20dorks%20for%20sql%20injection)

## How to safeguard information from Google Dorks?
You can take the following safety measures to protect your information from being disclosed by google dorks -

- Protect pages that contain sensitive information via username and password.
- Run regular dork queries against your website to discover the sensitive information.
- Request removal of sensitive information if found via google search console
  
  https://support.google.com/webmasters/answer/9689846?hl=en&visit_id=637871614748203924-38706967&rd=1

- Block sensitive content by using a robots.txt file located in your root-level website directory.




## FAQ

#### What is a search query?

anything that you type and search for in google is called google search query.

#### Can i use more than one google dork in a single search result ?

Absolutely yes , you can use n number of google dorks in a single google search.

#### Does their exist dorks for other search engines ?

Yes, their exist dorks for yahoo,bing,github and for many other platforms too.

#### Can i use these google dorks on any other platform too like yahoo,gihhub,etc or not ?

You can try but as we know every search engine has its own unique algorithm and shows results according to that, so it is better to use dorks made especially for that platform.

#### Is using google dorks illegal ?
NO, using google dork is legal but misusing the information gathered by google dorks for wrong purpose or for bad intentions is illegal.

## Credits

- [Bug Bounty Dorks Github Repo](https://github.com/sushiwushi/bug-bounty-dorks)
- [Sql Injection Dorks list Github Repo](https://github.com/rootac355/SQL-injection-dorks-list)

## Contributions

Contributions are always welcome!

You can contact us any time on any of our social media platforms for any kind of suggestions and Contributions.

Official Mail - dheerajyadavmandlana@gmail.com

GitHub - [https://github.com/dheerajydv19](https://github.com/dheerajydv19)

Twitter - [https://twitter.com/dheerajydv19](https://twitter.com/dheerajydv19)

Telegram - [https://t.me/dheerajydv19](https://t.me/dheerajydv19)

Instagram - [https://instagram.com/dheerajydv19](https://instagram.com/dheerajydv19)

Developed with ❤️ in India 🇮🇳 

