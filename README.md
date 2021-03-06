# TS3-Toolkit

[![Build Status](https://travis-ci.com/kevinsnijder/TS3-Toolkit.svg?token=qzJxNd8assEUHG9Fyt6e&branch=master)](https://travis-ci.com/kevinsnijder/TS3-Toolkit)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e9fc77745b644317ba5c16f95c0749fc)](https://www.codacy.com?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kevinsnijder/TS3-Toolkit&amp;utm_campaign=Badge_Grade)

![headerimage](https://imgur.com/PJM71tc.png)

<a href='https://play.google.com/store/apps/details?id=com.kevin.teamspeakstatus&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img width="175px" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'/></a>

## Initial setup
As a server owner, you'll need to do a a bit of configuration before your clients can connect with the TS3 Toolkit app.
The server groups that are allowed to use the app should have the ***b_client_create_modify_serverquery_login*** and the ***b_virtualserver_notify_register*** permission.
Don't worry, clients wont be able to kick and ban people with a serverquery if they don't have the correct permission. The serverquery will always have the exact same permissions as the user creating it.

If you're not sure how to set this up, follow this tutorial:
### Giving clients the serverquery permission
#### Step 1:
Open TeamSpeak on your desktop and connect to your server.

#### Step 2:
Make sure you have enabled the advanced permission system.

Go to tools -> options

![tutorialimage](https://imgur.com/a57oPza.png)

On the application tab, enable the "Advanced permissions system" checkbox.

![tutorialimage](https://imgur.com/Pm9l6Ix.png)

#### Step 3:
Give clients the correct permission.

- Select the group you'd like to give access to the app on the left.
- Search for 'serverquery'
- Check the *b_client_create_modify_serverquery_login* checkbox.
- Search for 'notify_register'
- Check the *b_virtualserver_notify_register* checkbox.


![tutorialimage](https://imgur.com/tH5PDJI.png)

Now your servergroup is all set up to create serverqueries for themselves!

## Creating a serverquery

#### Step 1:
Log in to the server you'd like the app to connect to.

#### Step 2:
Go to tools -> serverquery login
If the button is greyed out, the server owner has not completed the initial setup (see above) yet. Refer them to this page so he/she can set this up for you.

![tutorialimage](https://imgur.com/0bgOwi7.png)

#### Step 3:
Enter a name for your serverquery

![tutorialimage](https://imgur.com/Sh70vJn.png)

#### Step 4:
Write the credentials you received down somewhere.
Use these to login to the server with the TS3 Toolkit app.

![tutorialimage](https://imgur.com/QQ3TSDa.png)
