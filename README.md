# POC_PromotedLinks_SharePoint2016
Copy item from master list to child SharePoint list using event receiver-ItemAdded

**This is POC created based on below requirement:**
Businesss users want to maintain promoted link lists of many team sites in SharePoint from one place.
**Approach:**
Create configuration SharePoint list at one root level site (Master site). Configuartion will contain master site URLs and child site Urls who will be part of event receiver.
Once, Promoted link list from master site gets new item/updated existing item->same action will be copied over in all child sites' promoted link lists.

**POC in this repository:**
In this POC, ItemAdded event rceeiver is created.
Master site and child site are hard coded currently.
When new item gets added in promoted link list of master site, this gets added i child site-Promoted link list usnig event receiver**

**Environment:**
Used SharePoint 2016, Visula studio 2017 to develop this.


