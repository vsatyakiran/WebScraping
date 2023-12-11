# WebScraping
Web Scraping using the python beautiful soup

Web Scraping is the key technique for data collection which is really should learn skill for data engineer.

I have taken AmbitionBox website for scraping the data of Companies in India. Link to the ambitionbox is provided in sub_codes file.

I have used Python BeautifulSoup module and request module which are really powerful modules in python used for data collection.

Request Module fetchs the source code of the webpage and BeautifulSoup helps in extracting the data from the source pages.

Some webpages do not allow users to scrap the data for security reasons, AmbitionBox is one among them. If you observe the code I have used headers parameter.
The headers, including the User-Agent specified in the code, are specific to the website you are trying to access (http://www.ambitionbox.com in this case). Websites can use these headers to identify the type of client making the request, and sometimes they may block requests that appear to be from a bot or a non-standard user agent.

For each website, you might need to inspect the network requests using browser developer tools (F12 in most browsers) to see what headers are sent during a normal request. Then, you can mimic those headers in your Python code.

Different websites may require different headers, and it's common for websites to use anti-scraping measures that may require some trial and error to bypass. Always check a website's terms of service to ensure that you are scraping data in compliance with their policies.

Headers: Set user-agent and headers to mimic a real browser request. This can sometimes fool the server into allowing your request.

Session: Use a session to persist the connection and handle cookies.

Proxy: Use a proxy to make requests. This can help in bypassing IP-based restrictions.

Try above three differnt methods to get access to the websites.
Codes to the above methods are provided in sub_codes file
