---
title: "Manage Dynamics 365 (online) updates | MicrosoftDocs"
ms.custom: ""
ms.date: 09/30/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: 7341c21e-88d7-4996-ab74-3731f9cbaa1b
caps.latest.revision: 6
author: "jimholtz"
ms.author: "jimholtz"
manager: "brycho"
---
# Manage updates

[!INCLUDE[cc-applies-to-update-9-0-0](../includes/cc_applies_to_update_9_0_0.md)]

You have options for when you update your Dynamics CRM Online organization to the [!INCLUDE[pn_crm_8_2_0_online](../includes/pn-crm-8-2-0-online.md)]. To prepare for a smooth process, use the information in this topic.  
  
 You, as a [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] system administrator, decide when to install [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] service updates for your organization. To update to the latest release of [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)], complete these two steps:  
  
1.  Review the information in the Updates page in the [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] Administration Center ([https://portal.office.com](https://portal.office.com) > **Admin centers** > **Dynamics 365** > **Updates** tab) to find out what instances are ready to update, and the schedule.  
  
2.  Approve the update.  
  
    > [!IMPORTANT]
    >  Your instance will not be updated unless you approve it. This means your organization will go without the latest features and functionality until you explicitly give approval for the update to happen. Keep in mind, we do have an update policy that will make some updates mandatory, with no approval required. Please see [Update policy](../admin/manage-updates.md#BKMK_Policy) below for further details.  
  
 You’ll receive an email before the service update is available with a scheduled update date. This email will also include instructions about how to reschedule the update, if you choose. You’ll receive reminders 90, 30, 15, and 7 days before the update begins. The service update will happen during a 12-hour window, and during that time your organization might be unavailable for several hours. Most updates typically take 2-4 hours. We’ll let you know when your organization is updated and ready to use. For more information, see the [Schedule for update communications](../admin/manage-updates.md#BKMK_CommSchedule) later in this topic.  
  
> [!NOTE]
>  If you’re a [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] customer who is in the process of transitioning billing to the [!INCLUDE[pn_ms_online_services_environment](../includes/pn-ms-online-services-environment.md)], note that a [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] service update is not the same as the subscription billing transition. The billing transition is a one-time occurrence that affects your billing platform. Service updates are recurring releases that affect the features and capabilities that you receive in [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)].  
  
<a name="BKMK_UpdateDynamics365"></a> 
  
## Updating to [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)]  
 Microsoft is introducing [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)], the next generation of intelligent business applications that enable your organization to grow, evolve and transform to meet the needs of your customers and capture new opportunities. As a result, Microsoft is introducing new plans for customers effective November 1, 2016, that are similar but not identical to your current plan.  You have some choices to make. Please review the following:  
  
-   [Important information for CRM Online customers](../admin/important-information-customers.md)  
  
-   [Switch from Dynamics CRM Online to Dynamics 365 (online)](../admin/switch-dynamics-crm-online-dynamics-365.md)  
  
-   [Quickly navigate with the Office 365 app launcher and the Dynamics 365 home page](../admin/quickly-navigate-office-365-app-launcher.md)  
  
<a name="BKMK_Policy"></a>   

## Update policy  
 Microsoft delivers new features and improvements to the [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] service twice a year through service updates. To ensure our customers always get the best possible value, we advise customers to run the latest version of the service. However, we also realize that in certain circumstances, some customers are unable to update their solutions with the frequency of our service updates.  
  
 In early 2015 we enhanced the customer experience by giving customers the ability to provide consent prior to updating their organization. Customers today have a wide choice of days to choose from to best suit their business, and we will continue to provide that flexibility for service updates. In Fall of 2015, customers will have the choice to take the two updates as they become available, or take only one update per year. If a customer chooses to take only one update per year, this update becomes mandatory and the customer will be required to take the update during the available dates for that release.  
  
 In other words, at any given point a customer must be on the current version (n) or a version prior (n-1). For example, if you are on [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] (n-2) and chose not to take the available [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] (n-1), then you would need to take [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] (n) as a mandatory update. This policy is intended to provide the latest and greatest features and platform experience to our customers to ultimately suit their business needs.  
  
<a name="BKMK_Scenarios"></a>   

## Update scenarios  
 Your [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] update process depends on what version you have and how you’d like to update. Consider the following scenarios.  
  
> [!NOTE]
> -   For information on [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] instances, see [Manage Dynamics 365 (online) instances](../admin/manage-online-instances.md)  
  
### [!INCLUDE[pn_crm_online_2016_update](../includes/pn-crm-online-2016-update.md)] – Approach One (recommended)  
 This scenario applies to those who have Production and Sandbox instances of [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] (n-2).  
  
 For version information, see: [Recent versions of Dynamics 365 (online)](../admin/manage-updates.md#BKMK_Versions)  
  
|Version||Update to|  
|-------------|-|---------------|  
|Sandbox (n-2)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Sandbox (n-1)|  
|Sandbox (n-1)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Sandbox (n)|  
|Production (n-2)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Production (n)|  
  
 n = current version, [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)]  
  
#### Recommended update approach  
  
1.  Update your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] **Sandbox** instance to [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    1.  Select your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] Sandbox instance and approve the update to target version [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    2.  Once your Sandbox instance has been updated to [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)], test the update for your solutions and customizations.  
  
         If the update is unsuccessful, reset the Sandbox instance and reschedule the update until any issues are resolved.  
  
2.  Update your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] **Sandbox** instance to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    1.  When the [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] update becomes available, select your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] Sandbox instance and approve the update to target version [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    2.  Once your Sandbox instance has been updated to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], test the update for your solutions and customizations.  
  
         If the update is unsuccessful, reset the Sandbox instance and reschedule the update until any issues are resolved.  
  
    3.  Prepare a plan to train your users for the changes in [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
3.  Update your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] **Production** instance to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], skipping [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    1.  Do not approve the [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] update.  
  
        > [!NOTE]
        >  If you have already approved the update, you can change the scheduled date to coincide with the availability of [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    2.  When the [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] update becomes available, select your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] Production instance and approve the update to target version [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    3.  Once your Production instance has been updated to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], confirm the update for your solutions and customizations.  
  
         If the update is unsuccessful, reset the Sandbox instance and reschedule the update until any issues are resolved.  
  
    4.  Train your users for the changes in [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
### [!INCLUDE[pn_crm_8_2_0_online](../includes/pn-crm-8-2-0-online.md)] – Approach Two  
 This scenario applies to those who have Production and Sandbox instances of [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] (n-2).  
  
 For version information, see: [Recent versions of Dynamics 365 (online)](../admin/manage-updates.md#BKMK_Versions)  
  
|Version||Update to|  
|-------------|-|---------------|  
|Sandbox (n-2)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Sandbox (n-1)|  
|Production (n-2)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Production (n-1)|  
|Sandbox (n-1)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Sandbox (n)|  
|Production (n-1)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Production (n)|  
  
 n = current version, [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)]  
  
#### Recommended update approach  
  
1.  Update your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] **Sandbox** instance to [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    1.  Select your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] Sandbox instance and approve the update to target version [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    2.  Once your Sandbox instance has been updated to [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)], test the update for your solutions and customizations.  
  
         If the update is unsuccessful, reset the Sandbox instance and reschedule the update until any issues are resolved.  
  
2.  Update your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] **Production** instance to [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    1.  Select your [!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)] Production instance and approve the update to target version [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)].  
  
    2.  Once your Production instance has been updated to [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)], apply what you learned from the Sandbox instance update and confirm your Production instance update.  
  
3.  Update your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] **Sandbox** instance to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    1.  When the [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] update becomes available, select your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] Sandbox instance and approve the update to target version [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    2.  Once your Sandbox instance has been updated to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], test the update for your solutions and customizations.  
  
         If the update is unsuccessful, reset the Sandbox instance and reschedule the update until any issues are resolved.  
  
    3.  Prepare a plan to train your users for the changes in [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
4.  Update your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] **Production** instance to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    1.  When the [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] update becomes available, select your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] Production instance and approve the update to target version [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    2.  Once your Production instance has been updated to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], apply what you learned from the Sandbox instance update and confirm your Production instance update.  
  
    3.  Train your users for the changes in [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
### [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)]  
 This scenario applies to those who have Production and Sandbox instances of [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] (n-1).  
  
 For version information, see: [Recent versions of Dynamics 365 (online)](../admin/manage-updates.md#BKMK_Versions)  
  
|Version||Update to|  
|-------------|-|---------------|  
|Sandbox (n-1)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Sandbox (n)|  
|Production (n-1)|![One-way sync arrow (right) in Dynamics 365](../admin/media/one-way-sync-arrow-right-2.png "One-way sync arrow (right) in Dynamics 365")|Production (n)|  
  
 n = current version, [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)]  
  
#### Recommended update approach  
  
1.  Update your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] **Sandbox** instance to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    1.  When the [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] update becomes available, select your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] Sandbox instance and approve the update to target version [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    2.  Once your Sandbox instance has been updated to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], test the update for your solutions and customizations.  
  
         If the update is unsuccessful, reset the Sandbox instance and reschedule the update until any issues are resolved.  
  
    3.  Prepare a plan to train your users for the changes in [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
2.  Update your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] **Production** instance to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    1.  When the [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)] update becomes available, select your [!INCLUDE[pn_crm_8_1_0_online_subsequent](../includes/pn-crm-8-1-0-online-subsequent.md)] Production instance and approve the update to target version [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  
    2.  Once your Production instance has been updated to [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)], apply what you learned from the Sandbox instance update and confirm your Production instance update.  
  
    3.  Train your users for the changes in [!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)].  
  

<a name="BKMK_Versions"></a>   

## Recent versions of [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)]  
 To determine your version, sign in to [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)], and in the upper-right side of the screen, click the **Settings** button ![User profile Settings button](media/user-profile-settings-button.gif) > **About**.  

For recent versions, see [Recent versions of Dynamics 365 (online)](../admin/manage-updates.md#BKMK_Versions)

<!--  
|Version|Availability|Information|  
|-------------|------------------|-----------------|
|[!INCLUDE[pn_crm_online_2016_update_shortest](../includes/pn-crm-online-2016-update-shortest.md)]|December 2015|[What's new in CRM Online 2016](https://technet.microsoft.com/library/dn531078.aspx)|  
|[!INCLUDE[pn_crm_8_2_0_online_subsequent](../includes/pn-crm-8-2-0-online-subsequent.md)]|November 2016|[What's new for administrators and customizers in Dynamics 365 2016 and Dynamics 365](https://docs.microsoft.com/dynamics365/get-started/whats-new/index) |     
|March Dynamics 365 (online)|March 2016|[What's new in March for Dynamics 365 (online)](https://technet.microsoft.com/library/dn531078.aspx#What's new in March for Dynamics 365 (online))
|[!INCLUDE [pn-crm-9-0-0-online](../includes/pn-crm-9-0-0-online.md)]|July 2017|[Get ready for the next release](https://docs.microsoft.com/en-us/dynamics365/get-started/whats-new/customer-engagement/new-in-july-2017-update)
-->  

<a name="BKMK_howtoknow"></a> 
  
## How will I know my organization is ready to update?  
 [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] system administrators will be informed of updates to [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] in multiple ways.  
  
### Check your instances in the [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)] Administration Center  
  
1.  Sign in to [https://portal.office.com](https://portal.office.com).  
  
2.  In the [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] admin center, click **Admin** > **Dynamics 365**.  
  
 ![Dynamics 365 option in the Admin center drop-down list](../admin/media/click-admin-centers-dynamics-365.png "Dynamics 365 option in the Admin center drop-down list")  
  
3.  On the Instances page, click **Updates**, and then review the update status for your [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] instances.  
  
     Note the following:  
  
    -   Instances that are eligible to update will see **Update is Available**.  
  
    -   Clicking **Schedule your update** lets the admin select a target release and then do the scheduling.  
  
 ![Manage Dynamics 365 Online instances](../admin/media/customer-driven-update-notice-1.png "Manage Dynamics 365 Online instances")  
  
### A notification appears in your [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] web application  
  
1.  Sign in to your [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] instance.  
  
2.  If an update is available, admins will see a yellow [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] message bar notifying them of an available update.  
  
 ![Dynamics 365 Online update notice in banner bar](../admin/media/customer-driven-update-notice-2.png "Dynamics 365 Online update notice in banner bar")  
  
### Update notification emails are sent to admins  
 [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)] system administrators will receive an email from the [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] Team. You can use the links in the email to learn more about your update or reschedule it.  
  
<a name="BKMK_decipherupdate"></a>   
## Deciphering the update information  
 The “Manage your [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)] updates” page is your source for useful information and actions to take regarding your update.  
  
 ![Deciphering update details](../admin/media/deciphering-update-details.png "Deciphering update details")  
  
> [!NOTE]
>  If you are eligible to update to multiple versions of [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)], you’ll see an option **Change target version**. Large companies with extensive and complex customizations to their [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] may choose to upgrade to a later release instead of the first available. So you get the most up-to-date features and fixes, we highly recommend you upgrade to the latest version when available.  
  
<a name="BKMK_ApproveUpdate"></a>   
## Approve an update  
 You must be a [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] system administrator to approve updates.  
  
1.  Sign in to [https://portal.office.com](https://portal.office.com).  
  
2.  In the [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] admin center, click **Admin** > **Dynamics 365**, and then on the Instances page click **Updates**.  
  
3.  Choose the instance to approve.  
  
4.  Click **Approve Update** to approve and proceed with the update.  
  
> [!NOTE]
>  Once you approve an update, you can still reschedule it as long as the update has not started.  
  
<a name="BKMK_ReschedUpdate"></a>   
## Reschedule an update  
 You must be a [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] system administrator to reschedule updates.  
  
1.  Sign in to [https://portal.office.com](https://portal.office.com).  
  
2.  In the [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] admin center, click **Admin** > **Dynamics 365**, and then on the Instances page click **Updates**.  
  
3.  Choose the instance update to reschedule, and then click **Reschedule update**.  
  
 ![Click Reschedule to reschedule an update in Dynamics 365](../admin/media/cdu-notice.png "Click Reschedule to reschedule an update in Dynamics 365")  
  
4.  If you are eligible to update to multiple versions of [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)], you’ll see a page to select a target version. Select a version, and then click **Next**.  
  
    > [!NOTE]
    >  Large companies with extensive and complex customizations to their [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] may choose to upgrade to a later release instead of the first available. So you get the most up-to-date features and fixes, we highly recommend you upgrade to the latest version when available. Keep in mind, if you are two versions behind the current version you will have a mandatory update. See [Update policy](../admin/manage-updates.md#BKMK_Policy) for more information.  
  
5.  Select new preferred and alternate dates and times for the update, and then click **Next**.  
  
 ![Select new preferred or alternate dates and times](../admin/media/customer-driven-update-notice-5a.png "Select new preferred or alternate dates and times")  
  
6.  Review the new dates and times, and then click **Approve Update**.  
  
 ![Approve the new schedule dates and times in Dynamics 365](../admin/media/customer-driven-update-notice-5b.png "Approve the new schedule dates and times in Dynamics 365")  
  
7.  The Status column will indicate your update is approved.  
  
<a name="BKMK_UpdateStatus"></a>   
## Update status  
 To better track and manage your [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] updates, we added more granular update status to the Updates page.  At the date and time of your update, the status for your instance will show **Updating instance**.  
  
 ![Update Now status](../admin/media/update-now-status.png "Update Now status")  
  
 There are **four** stages of an update:  
  
|Status|Description|  
|------------|-----------------|  
|Queued (Not Started)|The update is queued and will start at the scheduled time.|  
|Backup|The [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] instance is being backed up.  A copy of the instance is backed up before the update for recovery purposes.|  
|Restore|The [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] instance is being restored.|  
|Database Upgrade|The [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] instance is being updated.|  
  
<a name="BKMK_SendEmailNotifications"></a>   
## Send email notifications to multiple recipients  
 By default, [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)] admins will receive update notifications. You can add others to receive update notifications.  
  
1.  Sign in to [https://portal.office.com](https://portal.office.com).  
  
2.  In the [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] admin center, click **Admin** > **Dynamics 365**, and then click **Instances**.  
  
3.  Choose an instance that has notifications you want to change, and then click **Notifications**.  
  
 ![Notifications button in Dynamics 365](../admin/media/customer-driven-update-notifications.png "Notifications button in Dynamics 365")  
  
4.  Enter the email addresses of people to receive update notifications for the selected instance, and then click **Save**.  
  
 ![Send Email Notifications in Dynamics 365](../admin/media/customer-driven-updatesendemailnotifications.PNG "Send Email Notifications in Dynamics 365")  
  
<a name="BKMK_AfterUpdate"></a>   
## What happens after an update is approved?  
 When your update has started, you’ll see **Update in progress** under **Status**. The **Reschedule** option will no longer be available.  
  
 ![Reschedule Dynamics 365 Online update in progress](../admin/media/customer-driven-update-notice-5d.png "Reschedule Dynamics 365 Online update in progress")  
  
 When your update is done, you’ll see **Updated successfully**.  
  
 ![Successful reschedule of Dynamics 365 (online) update](../admin/media/customer-driven-update-notice-5e.png "Successful reschedule of Dynamics 365 (online) update")  
  
<a name="BKMK_PrepareforUpdate"></a>   
## Prepare your [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)] organization for the update  
 [!INCLUDE[pn_crm_online_2016_update](../includes/pn-crm-online-2016-update.md)] contains a number of exciting changes. To take advantage of new features, you need to ensure any customizations are compatible with this update.  
  
### Prepare your users  
 To prepare your users for the changes to [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)], visit [Get ready for the next release](https://docs.microsoft.com/dynamics365/get-started/whats-new/customer-engagement/new-in-july-2017-update), where you will find videos, walkthroughs, and other information that you can use to familiarize yourself with the new experience.  
  
<a name="BKMK_Checklist"></a>   
## Checklist for the [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] update  
 Most of the update process is handled by [!INCLUDE[cc_Microsoft](../includes/cc-microsoft.md)]. However, there are a few things that you must do to prepare.  
  
1. **Know when your update is scheduled.**  
  
     You will be informed of a pending update in multiple ways. See [How will I know my organization is ready to update?](../admin/manage-updates.md#BKMK_howtoknow) in this topic.  
  
2. **Involve your [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] partner.**  
  
     If you have a [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] partner of record, we strongly recommend that you contact them for guidance and assistance. If you do not have a partner, you may consult the [!INCLUDE[sdk_Dynamics_Marketplace](../includes/sdk-dynamics-marketplace.md)] to identify a partner. Please note that there may be charges from partners for their services.  
  
3. **Watch for communications from [!INCLUDE[cc_Microsoft](../includes/cc-microsoft.md)].**  
  
     We will send you several communications about this subject to keep you informed about the update. In addition, we send email communications to users who have the System Administrator role in [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)]. Please make sure the email accounts associated with those user accounts are valid and being monitored. Communications will come from crmoln@microsoft.com, or for partners, you will also receive communications from the [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] Partner Team: crmteam@microsoft.com.  
  
4. **Verify your customizations are compatible.**  
  
     You should take the time before your update to verify that customizations are compatible using the [CRM Custom Code Validation Tool](http://go.microsoft.com/fwlink/p/?LinkID=511979). You should do this early enough that you have time to fix any identified issues. Additionally, Microsoft will run a number of automated tests, and if any of those tests fail in your instance, we will email the administrator a list of potential issues we have identified.  
  
5. **Create a non-production (Sandbox) instance in which you can test your customizations.**  
  
     Ideally, you should test your customizations prior to update. This will also give you the opportunity to verify compatibility of any third-party customizations. If you identify any potential issues, please work with the solution provider to correct any issues that arise. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Manage Dynamics 365 (online) Sandbox instances](../admin/manage-sandbox-instances.md)  
  
6. **Notify your users prior to the update of [!INCLUDE[pn_dyn_365](../includes/pn-dyn-365.md)].**  
  
     It is a best practice to notify your users that the system will be unavailable during the update. To get more resources to prepare users for the update, please visit [Onboard your organization and users](onboard-your-organization-and-users-to-dynamics-365-online.md).
  
7. **Watch for Update Completion or Reschedule emails from Microsoft.**  
  
 Once your organization is updated, you’ll receive a notification from [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] indicating that your organization is ready to use.  
  
<a name="BKMK_Aftertheupdate"></a>   
## After the update  
 Consider the following areas to attend to after your update.  
  
### Update Dynamics 365 (online) 2015 components  
 You can find more details about updating additional components, such as [!INCLUDE[pn_microsoft_dynamics_crm_for_outlook](../includes/pn-microsoft-dynamics-crm-for-outlook.md)], in [Administering Dynamics 365](../admin/admin-guide.md).  
  
<a name="BKMK_CommSchedule"></a>   
## Schedule for update communications  
  
|When|Recipient|In-product alert|Email|Admin Center|  
|----------|---------------|-----------------------|-----------|------------------|  
|Update scheduled|All Admins|Yes|Yes|Yes|  
|90 days before update|All Admins|No|Yes|Yes|  
|30 days before update|All Admins|No|Yes|Yes|  
|15 days before update|All Admins|No|Yes|Yes|  
|7 days before update|All Admins|Yes|Yes|Yes|  
|Schedule confirmed by Admin|All Admins|No|Yes|Yes|  
|Update in progress|All Admins and Users|No|No|Yes|  
|Update successful|All Admins and Users|No|Yes|Yes|  
|Fallback to secondary update|All Admins|No|Yes|Yes|  
|Update rescheduled|All Admins|No|Yes|Yes|  
  
> [!NOTE]
>  “All Admins” includes [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] system administrators and [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] Global administrators.  
  
<a name="BKMK_ServiceRequestManage"></a>   
## Request service  
 Having a problem with your [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] service? You can create a service request to get the issue resolved.  
  
### Create a [!INCLUDE[pn_crm_online_shortest](../includes/pn-crm-online-shortest.md)] service request  
  
1.  Sign in to the [Office 365 admin center](https://portal.office.com).  
  
2.  In the left-side menu, click **Support** > **Overview**.  
  
3.  Under **Create a service request**, click **Dynamics 365 Online**. You may need to expand the list by choosing **More**.  
  
4.  Fill in the information and submit your request.  
  
 ![Office 365 admin center service request](../admin/media/o365-admin-center-request-service.PNG "Office 365 admin center service request")  
  
### See also  
 [Policies and Communications for Dynamics 365 (online)](../admin/policies-communications.md)    
 [Manage email notifications](../admin/manage-email-notifications.md)