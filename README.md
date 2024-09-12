# Opaper Backend Take Home Test

## Assignment
Return your answer by sending us the link to git repository or email us at `tanjung.kusuma@opaper.app` the zip file including the `.git` folder so we can see your commit history.

Design and implement a simple wallet REST API service that can receive and send money to other wallets. Please implement the code in golang, use whatever libraries you want, and the database whatever you want as long as it is sql based database (sqlite, postgres, mysql, etc.). Do include the api documentation in the repo (example: you can put swagger file in the docs folder) you can use any documentation tool you want ([swagger](https://swagger.io/specification/), [postman](https://www.postman.com/), [yaak](https://yaak.app/), [bruno](https://www.usebruno.com/), etc...) as long you provide how to use it.


### hints
- handle concurrent transactions problem, for example: if you have 50.000 rupiah, and you want to send 30.000 to other wallet, but somehow the user send requests from 5 different ip addresses at the same time, how to handle it?
- plan if the wallet transactions have like 10million transactions, how does the wallet will perform?