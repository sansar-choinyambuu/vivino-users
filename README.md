# vivino-users

Scrape the data on vivino users via following API's
- HTTP POST https://www.vivino.com/users/x/country_rankings - top ranked users for a country
BODY
```
  {
      "page": 1,
      "country_code": "ca"
  }
```
- HTTP GET http://app.vivino.com/api/users/mikhail-mikhail20 - user information
- HTTP GET http://app.vivino.com/api/users/mikhail-mikhail20/followers?start_from=0&limit=10 - followers of user 
- HTTP GET http://app.vivino.com/api/users/mikhail-mikhail20/followers?start_from=0&limit=10 - following of user 
