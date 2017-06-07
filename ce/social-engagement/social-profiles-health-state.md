---
title: "Check the health state of your social profiles | MicrosoftDocs"
 
description:

ms.custom: ""

ms.date: "2017-05-19"
ms.reviewer: ""
ms.service: "mse"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Social Engagement"
ms.assetid: 4d0153a1-4d21-4a73-8685-2ce2e6c55e9f
caps.latest.revision: 12
ms.author: "dechang"
---
# Check the health state of your social profiles
[!INCLUDE[pn_netbreeze_long](../includes/pn-netbreeze-long.md)] provides health state checks for tokens, social profiles, acquisitions, and interactions so you can make sure your accounts are always active. Checking health states is important so you don't miss out on any posts because of expired tokens. [!INCLUDE[pn_netbreeze_short](../includes/pn-netbreeze-short.md)] will notify you through email and in the application when your critical acquisition tokens are about to expire. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Manage access tokens](../social-engagement/manage-access-tokens.md)  
  
 socialengagement@microsoft.com will send email notifications for the following scenarios:  
  
-   Your token has been active for 30 days and will expire soon. Re-authenticate your token or add an additional token.  
  
-   Your token has been active for 45 days and will expire soon. Re-authenticate your token or add an additional token.  
  
-   Your acquisition health state has switched from green to yellow. Only one token is currently valid.  
  
-   Your acquisition health state has switched from yellow to red. No tokens are currently valid and all data will be lost if no tokens are authenticated.  
  
## Social profile ownership  
 To claim ownership of an account, go to **Settings** > **Social Profiles**. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Manage social profiles](../social-engagement/manage-social-profiles.md)  
  
||||  
|-|-|-|  
|**Health State**|**Symbol**|**Action you can perform**|  
|Valid|No symbol displayed|No action needed. Tokens are valid.|  
|Valid, but your token is not valid|![At least one token is not valid symbol](../social-engagement/media/token-not-valid-icon.png "At least one token is not valid symbol")|Re-authorize this account or delete it.|  
|The account isn’t valid; if the user has a token, it also isn’t valid|![No valid token symbol](../social-engagement/media/token-missing-icon.png "No valid token symbol")|Re-authorize the social profile if you are the owner, or claim ownership or contact one of the owners if this profile is shared with you.|  
|No owner; invalid without any owner|![No Ownership symbol](../social-engagement/media/no-ownership-icon.png "No Ownership symbol")|Claim ownership if you want to use this account. To claim ownership of an account, go to **Settings** > **Social Profiles**. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Manage social profiles](../social-engagement/manage-social-profiles.md)|  
  
## Acquisition symbols  
 The symbols below indicate whether your search acquisition or private message acquisition is valid. You can find these symbols under the Acquisitions column in your lists of owned profiles and profiles without owners.  
  
> [!NOTE]
>  These symbols will be dimmed if acquisition is inactive.  
  
|||  
|-|-|  
|**Symbol**|**Condition**|  
|![Search button](../social-engagement/media/magnifier-icon.png "Search button")|Acquisition is allowed but no search rule has been set up.|  
|![Keywords symbol](../social-engagement/media/keywords-search-rule-icon.png "Keywords symbol")|Acquisition is allowed and a search rule is in use.|  
|![Private messages symbol](../social-engagement/media/private-message-icon.png "Private messages symbol")|Acquisition of private messages has been allowed and a private message rule is in use.|  
  
## Acquisition token status overview  
 Social Engagement displays symbols to let you know if social profile data acquisition and private messages are running.  
  
||||  
|-|-|-|  
|**State**|**Symbol**|**Condition**|  
|Running|![Inidcates that data acquisition and private messages are running for this social profile](../social-engagement/media/valid-token-icon.png "Inidcates that data acquisition and private messages are running for this social profile")|At least one token is valid and used for acquisition.|  
|Allowed|![Acquisition Allowed symbol](../social-engagement/media/acquition-allowed-icon.png "Acquisition Allowed symbol")|The social profile allows acquisition but no search rule has been added.|  
|Expired|![No valid token symbol](../social-engagement/media/token-missing-icon.png "No valid token symbol")|The social profile token is expired. You need to re-authenticate your token. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Re-authenticate a token](../social-engagement/manage-access-tokens.md#reauth_token)|  
  
### See Also  
 [Manage social profiles](../social-engagement/manage-social-profiles.md)   
 [Manage access tokens](../social-engagement/manage-access-tokens.md)