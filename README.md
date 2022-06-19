# Future-Ready-Talent- PROJECT DEMO AND TESTING


/Deployment steps followed withdeploymentURL for a AZURE CHATBOT with AZURE RESOURCES/


We are going to make a chatbot on AZURE ClOUD and we will be hosting it on our own website.


In this project we host our website withoutany coding involved. We are going to host it on a google website were we will be using google sites like HTML. You can also use buy domain. Here I am going to use google sites just to make easier.


//STEPS FOR DEPLOYMENT//


> MAke a free account on Azure.

![Screenshot (55)](https://user-images.githubusercontent.com/91434729/174470365-749e20be-34e3-48d6-bc45-c2fef80b58fa.png)



> Type QnA maker in search box.

![Screenshot (55)](https://user-images.githubusercontent.com/91434729/174469979-eb1efdf4-7cde-4e14-9e4c-790280b86f98.png)



> Click on QnA maker.

![Screenshot (64)](https://user-images.githubusercontent.com/91434729/174471702-0eddefba-2e28-4cd7-8ed1-915ada57b6b7.png)


![Screenshot (56)](https://user-images.githubusercontent.com/91434729/174470036-35e4c692-9bae-48db-833a-8cd3270719f8.png)


> Insert all the details such as "Resource Group". Here I used "QnA Bot COVIDIND".

![Screenshot (57)](https://user-images.githubusercontent.com/91434729/174470266-a3b43341-a029-4eb1-b31f-5892a1263777.png)



> Add "Resource Group Location". Try keeping it near to where you live. Here I used US West.
 

![Screenshot (58)](https://user-images.githubusercontent.com/91434729/174470975-f9688db3-25f7-4373-b55d-fd6f042c8901.png)



> "NAME YOUR BOT". Should be UNIQUE. In my project i used QnABotCovidIND

![Screenshot (58)](https://user-images.githubusercontent.com/91434729/174471101-bedcdf01-74b3-489d-9944-91eae555b5c2.png)



> Use "Free F0 pricing Tier" which is completely free or if you have pay as you go account this don't cost money unless you buy domain.

![Screenshot (58)](https://user-images.githubusercontent.com/91434729/174471169-aaa7455b-8dbe-4111-848f-338a66c75726.png)


> Disable "APP Insights" and click create.

> Wait for the deploymwnt to successfully complete.

>After deployment is successfull "Click on go to Resource".

>Navigate to "Quick Start" under "Resource Management". Click on number two "Click Q&A Maker Portal"

![Screenshot (60)](https://user-images.githubusercontent.com/91434729/174471409-45afb6d0-c079-4b46-8c7c-91e3bf3dbb1a.png)


>Next we are going to connect our Q&A Service to Knoweledge Base. This Knoweledge Base stores all our data for our CHATBOT.

![Screenshot (62)](https://user-images.githubusercontent.com/91434729/174471524-91e440ae-08a9-43f2-b4b4-686a2e7b6c89.png)


>Make sure your "directory ID" is pre filled or else select the first thing in the select menu.

>Select your Azure Subscription.

>Select the bot you just made.

>Select your Language.


>Name your Knoweledge Base.


>Here I am going to add data from my own source and this step is optional. You can also create your own questions and answers manually. But here Iam going to take a source https://www.cdc.gov/coronavirus/2019-ncov/faq.html

>Copy and Paste the URL if you are using from Internet.

>Choose templates. I choosed none.

>Click on create KB.

![Screenshot (66)](https://user-images.githubusercontent.com/91434729/174471836-3994f508-e835-433c-9592-79e348f22a13.png)


>Next you will see all questions and answers in your Knoweledge Base KB.

![Screenshot (67)](https://user-images.githubusercontent.com/91434729/174472040-a1788a2d-89a1-4769-817b-f9ecc5d4e5c5.png)


>Click on Test on the left to test your CHATBOT.
![Screenshot (69)](https://user-images.githubusercontent.com/91434729/174472202-245ed619-bb13-4d5d-bcc8-e0c19176c02b.png)


>You can also add your own QandA pairs.

![Screenshot (70)](https://user-images.githubusercontent.com/91434729/174472320-bf08a3b0-6245-4ce4-8203-d73235c0ac78.png)


>Click on save and test to review your added questions.

>Now your bot is finished "Click On Publish". 

>![Screenshot (71)](https://user-images.githubusercontent.com/91434729/174472520-4eb2d88e-f9f6-4950-9de4-8533a8f23e02.png)


>Now we are going to link it with actual AZURE BOT SERVICE.

![image](https://user-images.githubusercontent.com/91434729/174472594-7bf4bf0c-c1e0-4766-b3fd-8c7622489b85.png)


>Click on create bot and name accordingly.

>Change the pricing tier to free if you want to keep it as free.

>Turn off Application Insights and click create.

>After successful deployment "Click on go to Resources". Go to Channels under settings next to configurations.

>You can also connect your bot to load of different things like Alexa, Email, Facebook...etc.

![Screenshot (74)](https://user-images.githubusercontent.com/91434729/174472718-90361c2d-e5e0-4960-a3f1-eb6818ed4d22.png)


>Now we are going to going to embed the HTML onto Google Sites.

>Click on "Get bot Embed Codes".

![Screenshot (74)](https://user-images.githubusercontent.com/91434729/174472800-257b1cee-4141-428d-a778-996342405f7c.png)


>You will find secret keys and they are important keep the tab open.

![Screenshot (75)](https://user-images.githubusercontent.com/91434729/174472854-3a0bbfbd-8ef3-4471-b33c-46484775d30b.png)


>Copy the embed code and create a new google site.

![Screenshot (76)](https://user-images.githubusercontent.com/91434729/174472990-4928dd08-f41a-4bbe-b87a-a659a34565be.png)


>Name the Google Site and click on embed--> Paste the code.

![Screenshot (77)](https://user-images.githubusercontent.com/91434729/174473027-dd82c36c-315d-4c3d-8c1d-59295011cddc.png)


>Replace "Your secret here'" with any of the secret kwys. Click next and insert.

![Screenshot (77)](https://user-images.githubusercontent.com/91434729/174473059-b5d5e507-b76b-4427-b390-a2995ad993ae.png)


>Click on publish type in the web address and "Click on Publish"

![image](https://user-images.githubusercontent.com/91434729/174473116-03a17388-e48f-4e8f-9d24-c90c3d4c50cd.png)


Your Bot is ready now :)

Links-


Azure Portal Link: portal.azure.com

Chit-Chat Guidance: https://tinyurl.com/chitchatcustom

QnA Logging: https://tinyurl.com/appinsightsqnalogs

Bot Customization: https://tinyurl.com/botcustom


