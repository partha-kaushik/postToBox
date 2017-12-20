# postToBox
Posting to box.com from automated processes
box.com uses oAuth2 for secure communications, as do many other sites. The API that box.com provides has one restriction, at least for me: getting a bearer token requires a mandatory interactive login. This stymies any automated process running on a headless machne from easily interacting with Box.  
This project is an attempt to get around the restriction mentioned above.
