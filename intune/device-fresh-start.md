---
# required metadata

title: Reset Windows 10 devices with Intune | Microsoft Docs
titleSuffix: "Intune Azure preview"
description: "Intune Azure preview: Learn how to use Fresh Start to reset Windows 10 PCs running Intune."
keywords:
author: robstackmsft
ms.author: robstack
manager: angrobe
ms.date: 04/27/2017
ms.topic: get-started-article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 5aa5cfa3-c483-4099-b40f-578ff8dca425

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: ilwu
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure

---

# Use Fresh Start to reset Windows 10 devices with Intune


[!INCLUDE[azure_preview](./includes/azure_preview.md)]

The **Fresh Start** device action removes any apps that were installed on a Windows 10 PC running the Creators Update, then automatically updates the PC to the latest version of Windows.
This can be used to help remove pre-installed (OEM) apps that are often delivered with a new PC. You can configure if user data is retained when this device action is issued. In this case, apps and settings are removed, but the contents of the users Home folder are retained.

1. Sign into the Azure portal.
2. Choose **More Services** > **Monitoring + Management** > **Intune**.
3. On the **Intune** blade, choose **Devices**.
4. On the **Devices and groups** blade, choose **All devices**.
5. From the list of devices you manage, choose a Windows 10 desktop device, and then choose the **Fresh Start** device remote action.

To see the status of the action you just took, on the **Devices and groups** blade, choose **Device Actions**.
