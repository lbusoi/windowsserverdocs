---
title: STEP 3: Install and Configure CLIENT2
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: 
  - techgroup-networking
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: f009fdd1-94e6-4ccb-8c6e-609a5394db53
author: coreyp
---
# STEP 3: Install and Configure CLIENT2
CLIENT2 is a [!INCLUDE[firstref_client_7](includes/firstref_client_7_md.md)] computer that is used to demonstrate the backwards compatibility of Remote Access running on [!INCLUDE[win8_server_1](includes/win8_server_1_md.md)] servers.  
  
1.  [To install the operating system on CLIENT2](assetId:///6cbee1b5-f6f6-443f-8fa9-31cc5c05a0ee#installOS)—Install [!INCLUDE[firstref_client_7ent](includes/firstref_client_7ent_md.md)] or [!INCLUDE[firstref_client_7ult](includes/firstref_client_7ult_md.md)] on CLIENT2.  
  
2.  [To join CLIENT2 to the CORP domain](assetId:///6cbee1b5-f6f6-443f-8fa9-31cc5c05a0ee#Join)—Join CLIENT2 to the corp.contoso.com domain.  
  
## <a name="installOS"></a>To install the operating system on CLIENT2  
  
1.  Start the installation of [!INCLUDE[nextref_client_7](includes/nextref_client_7_md.md)].  
  
2.  When you are prompted for a user name, type **User1**. When you are prompted for a computer name, type **CLIENT2**.  
  
3.  When you are prompted for a password, type a strong password twice.  
  
4.  When you are prompted for protection settings, click **Use recommended settings**.  
  
5.  When you are prompted for your computer's current location, click **Work network**.  
  
6.  Connect CLIENT2 to a network that has Internet access and run Windows Update to install the latest updates for [!INCLUDE[nextref_client_7](includes/nextref_client_7_md.md)], and then disconnect from the Internet.  
  
7.  Connect CLIENT2 to the Corpnet subnet.  
  
## User account control  
When you configure the [!INCLUDE[nextref_client_7](includes/nextref_client_7_md.md)] operating system, you are required to click **Continue** on the **User Account Control** \(UAC\) dialog box for some tasks. Several of the configuration tasks require UAC approval. When you are prompted, always click **Continue** to authorize these changes.  
  
## <a name="Join"></a>To join CLIENT2 to the CORP domain  
  
1.  Click **Start**, right\-click **Computer**, and then click **Properties**.  
  
2.  On the **System** page, in the **Computer name, domain, and workgroup settings** area, click **Change settings**.  
  
3.  On the **System Properties** dialog box, on the **Computer Name** tab, click **Change**.  
  
4.  On the **Computer Name\/Domain Changes** dialog box, click **Domain**, type **corp.contoso.com**, and then click **OK**.  
  
5.  When you are prompted for a user name and password, type the user name and password for the User1 domain account, and then click **OK**.  
  
6.  When you see a dialog box that welcomes you to the corp.contoso.com domain, click **OK**.  
  
7.  When you see a dialog box that prompts you to restart the computer, click **OK**.  
  
8.  On the **System Properties** dialog box, click **Close**, and when you see a dialog that prompts you to restart the computer, click **Restart Now**.  
  
9. After the computer restarts, log on as CORP\\User1.  
  
