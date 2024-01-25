---
layout: default
title: Clients & Contacts
permalink: /contacts
---

## Web Login Status

The small text to the right bottom of the Web Login field should show 7 possible options:  

| Active, Exempt or Deactivate | person can login |
| No Login, Suspended, Blocked or Reactivate | person can **not** login |

1.  **Active** means there's a Web Login 
1.  **Exempt** means there's a Web Login and Exempt from Health Requirements is checked
1.  **Deactivate** means they are Active but now Ineligible. It will show during the grace period, but they will have access until going to Suspended or Blocked.
1.  **No Login** means Web Login is empty
1.  **Suspended** has Disable Web Access checked
1.  **Blocked** has Disable Web Access checked and Disable Automatic Renewals checked
1.  **Reactivate** means they are Suspended but now Eligible. It will rarely show as the person will be reactivated at the next nightly run and usually gets that status at the start of the run due to a new eviction.

## Email Status

- For events, it filters off of "No Email" or "Unsubscribe" or "Mailing List Opt Out" which are customizable (on/off) at list creation.
- No processes are making sure "Mail" is in the Status field.
- The other use of that field is during website deactivations, it will mark that field as "Unsubscribe" if they go ineligible and "Mail" if they go eligible again. 