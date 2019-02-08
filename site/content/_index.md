---
date: 2019-02-08T13:25:23.572Z
description: >-
  Install the add-on for bulk email verification directly on Google Sheets,
  where you have contacts collected
image: /img/evaddon-share.png
title: Email Verification directly on Google Sheets
---
Email Verification Add-on prevents bounced emails and low-quality contacts because:

1. It provides a real-time validation lookup directly on Google Sheets. You receive fresh data upon request and don’t need to export/import contacts for the verification process.

2. It shows you non-existent, non-deliverable and misspelled addresses.

3. It has two verification levels: Simple and Pro. At the Simple level you can get 2 data columns: B) an email address is deliverable or not, C) a domain exists or not. At PRO level, there are 2 extra data columns: D) inbox status and E) catching-all status.

![The Advanced level columns](/img/4columns.png "The Advanced level columns")

*Four columns of verification data*

4. It shows you if inboxes are full or in a catch-all message mode. That can help you understand how often people check their inbox and for what reason.

#### Pricing

With a free account, you can get 200 free verifications at the beginning and 50 per day after that. If you need more, choose the amount you want to increase that quota by. It is a one-time payment without the expiration date for the purchased quota:

*2,000 verifications for $12;
*5,000 verifications for $20;
*10,000 verifications for $33;
*25,000 verifications for $65;
*50,000 verifications for $100;
*100,000 verifications for $180.

#### Common questions

**How do you validate the data?**
We have built a service to carry out validation at different levels: an address format, information about a domain, its mail server, and a response from that mail server. The add-on is connected to the service via API.

**How can I be sure that you will not steal my data?**
For security reasons and in order to protect your data, we do not collect (or share data) from your validation lookups on our servers. We don’t even have a database to store data.

**What column shows me that my email will not be bounced?**
The «Is deliverable» column is what you need. It shows that mail server accepted this email address. Next, you can check if that email is not in a catch-all messages mode.

**When will you reset my free usage?**
A free account gives you 200 free verifications at the beginning and 50 per day after that. We reset usage at 1 am every day.
