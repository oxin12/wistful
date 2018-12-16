# Messenger Platform Sample -- node.js

This project is an example server for Messenger Platform built in Node.js. With this app, you can send it messages and it will echo them back to you. You can also see examples of the different types of Structured Messages.

It contains the following functionality:

* Webhook (specifically for Messenger Platform events)
* Send API
* Web Plugins
* Messenger Platform v1.1 features

Follow the [walk-through](https://developers.facebook.com/docs/messenger-platform/quickstart) to learn about this project in more detail.

## Setup

### Step 1:

go to [Glitch.com](https://glitch.com/)

![step1](/pics/step1.png)

### Step 2:

Login with facebook or github.

![step2](/pics/step2.png)

### Step 3:

Create new express project

![step3](/pics/step3.png)

### Step 4:

Go to **Advance options**

![step4](/pics/step4.png)

### Step 5:

Select **import from github**

![step5](/pics/step5.png)

### Step 6:

Enter the github repo as [**ddrdushy/fbChatBotBoilerplate**](https://github.com/ddrdushy/fbChatBotBoilerplate)

![step6](/pics/step6.png)

### Step 7:

Need to change the values in **config/default.json** values

![step7](/pics/step7.png)

### Step 8:

Create new app in [Facebook developer page](https://developers.facebook.com)

![step8](/pics/step8.png)

![step8_1](/pics/step8_1.png)

![step8_2](/pics/step8_2.png)

### Step 9:

Create new app ID

![step9](/pics/step9.png)

### Step 10:

Select messenger in dashboard.

![step10](/pics/step10.png)

![step10](/pics/step10_1.png)

### Step 11:

Select the page which you need to intergrate this bot.

![step11](/pics/step11.png)

![step11_1](/pics/step11_1.png)

Face book will generate an access token for the particular page. copy that token and replace it in **config file**.

![step11_2](/pics/step11_2.png)

### Step 12:

Go to setting section in dashboard. get the **App Secret** and place it in the **config file.**

![step12](/pics/step12.png)

![step12_1](/pics/step12_1.png)

make sure that bot is in **live Status.**

![step12_2](/pics/step12_2.png)

### Step 13:

Copy the **Glitch** project URL. go to **messenger settings** under products menu and click on **Setup Webhooks**.

![step13](/pics/step13.png)

![step13_1](/pics/step13_1.png)

Paste the **callback URL** as **Glitch project URL** and add **webhook** at the end of the URL as shown in the below picture. and tick on *messages* and *messaging_postbacks*.

![step13_2](/pics/step13_2.png)

![step13_3](/pics/step13_3.png)

### Step 14:

Go to Facebook Messenger and search for the page name and start using the Chatbot.

![step14](/pics/step14.png)

Successfully deployed the chatbot.

![step14_1](/pics/step14_1.png)

![step14_2](/pics/step14_2.png)
