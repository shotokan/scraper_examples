> Libraries or Frameworks used:

BeautifulSoup, 
Selenium, 
Requests, 
PhantomJs, 
Pandas, 
Urllib3, 
Unidecode (represent unicode in ASCII), 
SlAlchemy, 
re,
html.parser,
lxml,
html5lib

> In 200 words or less, describe the working flow:

First I need to know all requirements and main purpose for crawler. Then, I need to define what data I will need to  take and in what format It will be saved. Afterwards, It's necessary to understand how the web site works (what it is requesting and receiving, form elements, errors, status codes, etc.) and inspect in detail the source code to understand what technologies are used, the web site structure and if I will need to clean up or fix the structure. To do that, I usually use chrome's developer tools, Postman and Owasp ZAP. Once everything is clear, We can choose the best tools (libraries or frameworks) to begin  working. It is similar to how a hacker does a recognise of his objective or  perform the information gathering phase.


> Explain difference between python list and tuple.

Tuples are immutable, so they can’t change once created. They take up less space in memory, so they are faster than the 
lists.

> Explain what a Python generator is

Generator: They are a simple way of creating iterators, so that they will allow us to obtain their results little by 
little. That is, every time we call  the function they will give us a new result. They only compute an item when we 
ask for it (It takes less memory, so They are faster) and use the yield statement.
