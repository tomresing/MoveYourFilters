# Move Your Filters

This project contains test code from a Microsoft OneWeek Hackathon project helping people create Outlook rules and folders to better organize incoming email.

# Story

> I get hundreds of emails a day sent to various listservs and groups of people. The most challenging part of switching from Gmail to Outlook was having to recreate all of my filters 1 by 1 with Outlook rules. It took me nearly a week to get everything in order and in the meantime, my inbox was a disaster. 

> *Customer #1*

When an organization chooses to move or explores moving to Office 365 from Google's GSuite, they run into lots of challenges. One challenge with switching was discovered recently: the need to create new Outlook rules. A Google customer was moving over. Some employees found themselves in a bad situation when they were moved over without their filters. Their inboxes were filling at a rapid rate! We collected some example rules from one user.
Gmail offers filters, not rules, so the move may not always be one to one. However, many filters can be moved over directly to rules in Outlook. We'll concentrate on those as our intial product. We hope to leverage this open source project both to complete that initial offering and then to grow from there.

# Setup

Current code is all client-side Javascript. The dependecies are currently setup through CDN. To test locally, clone the repo and start a webserver at port 8000.

# Project Steps

## Completed

Code to authenticate to Google and list filters via API
Code to authenticate to Microsoft Graph API with Outlook write access for rules

## Proposed

Code to process exported filters XML file
Code to create new Outlook rules in Graph API

### Proposed logic for creating new rules in Outlook

MVP list: move based on email address or content keywords, move to folders, check for existing folders, create new folders, and mark as read

# Office UI Fabric Prototype Design

The prototype design was created based on Office UI Fabric and the three proposed screens are pictured below.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
