---
# required metadata

title: Features not implemented in on-premises deployments
description: This topic lists features that have not been implemented in on-premises deployments.
author: sericks007
manager: AnnBe
ms.date: 06/16/2017
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-applications
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer, IT Pro
# ms.devlang: 
# ms.reviewer: sericks007
ms.search.scope: Operations, Platform, UnifiedOperations
# ms.tgt_pltfrm: 
ms.custom: 21881
ms.search.region: Global
# ms.search.industry: 
ms.author: sericks
ms.search.validFrom: 2017-06-30
ms.dyn365.ops.version: Platform update 8
---

# Features not implemented in on-premises deployments

[!include[banner](../includes/banner.md)]

The following features have not been implemented in on-premises deployments of Dynamics 365 for Finance and Operations, Enterprise edition. These features have not been implemented, but aren't deprecated.

| **Feature**                                                      | **Description**                                                                                                                                                                          |
|------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Task recorder                                                    | Task recorder libraries in Lifecycle Services (LCS) are not supported. Task recordings can be loaded from or saved to the local file system.                                                                  |
| **Support** pane                                                         | The **Support** pane (**Help & Support** > **Support**)  is not yet available.                                                                                                                                                   |
| PowerBI.com integration                                          | PowerBI.com integration is not yet available for on-premises deployments. For example, the ability to pin a tile or a report from your PowerBI.com subscription to a workspace is not available. |
| Microsoft Office integration                                             | SharePoint on-premises support is not available yet. SharePoint online is supported.<br>Skype for Business on-premises support is not available yet. Skype for Business online is supported.  |
| Analytical workspaces                                            | Analytical workspaces are not yet available for on-premises deployments.                                                                                                                  |
| Private preview of Generic Tax Engine (GTE)                      | The private preview of Generic Tax Engine (GTE) functions relies on LCS access and LCS GTE preview project. Therefore, it is not available for on-premises deployments.                      |
| Electronic reporting (ER) integration with LCS                   | The ER integration with LCS is not supported. ER configurations can't be downloaded directly from LCS to Finance and Operations.                                   |
| ER integration with SharePoint            | Integration with SharePoint is not supported. SharePoint server can't be configured as a destination for electronic documents generated by using ER.                           |
| Dynamics 365 for Finance and Operations - Warehousing mobile app | The app is temporarily unavailable.                                                                                                         |
| Ability to export entities to your own database (BYOD)                      | This feature is currently not implemented.                                                                                                                                                |
| Author Power BI reports using OData                              | Authoring Power BI reports with OData using Power BI desktop or Excel PowerQuery tools is not supported.                                                                                  |
|Retail| No Retail features are available for use in on-premises deployments at this time.|
|Purchase requisitions: Punch-out from external catalogs |It is not possible to check out a shopping cart from an external catalog to a purchase requisition. |
|Trace Parser and PerfTimer |These tools are not working or have limited functionality for this release. These features will be implemented in a future release. |
|SSRS scale out  |Currently SQL Server Reporting Services (SSRS) does not support scaling out. This feature will be added in an upcoming release. |
|Telemetry  |Currently no telemetry is transferred into the cloud. In a future update we will start transferring telemetry data into the cloud. |
|Mobile apps     |At this time, mobile apps are not supported. Mobile app support will be added in an upcoming release. |