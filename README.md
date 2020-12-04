# Answer me these questions three (bonus points if you know what movie this quote is from)

1. **Salesforce POSTMAN**<br/>
Go to this [repo](https://github.com/forcedotcom/postman-salesforce-apis) and [download](https://github.com/forcedotcom/postman-salesforce-apis) the SF POSTMAN collection. Once you have imported the collection, perform the `SOAP Login` API call under the `Auth` folder in the collection. This API Call should be done against your Developer Edition Org you signed up for ([Support Doc 1](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_login.htm) [Support Doc 2](https://trailhead.salesforce.com/content/learn/modules/api_basics/api_basics_soap)). Once you have successfully authenticated,set the following variables in the POSTMAN environment `Salesforce Template Environment`
    * `_accessToken` from `sessionId` in response
    * `_endpoint` from `serverUrl` in response (domain only)

   Once you have done this, perform the `Versions` API call under the `REST` folder. After you get the response back, create a new branch and create a file called `versions.json` and paste the result into that file

2. **Calculator**<br/>
   In whatever language you feel most comfortable with, write a small class that implements the following methods (On the same branch you created above, create the file that has this code):

   * `Integer add(Integer,Integer)
   * `Integer subtract(Integer,Integer)
   * `Integer multiply(Integer,Integer)
   * `String divide(Integer,Integer)
      * Example form of answer for 5/3 -> `1 R2`
   
