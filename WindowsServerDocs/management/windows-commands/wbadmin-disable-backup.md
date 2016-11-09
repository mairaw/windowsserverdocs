---
title: wbadmin disable backup
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 5176cbd9-0696-4b3f-9c35-272dd84f7898
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# wbadmin disable backup

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Stops running the existing scheduled daily backups.
To disable a scheduled daily backup, you must be a member of the **Administrators** group, or you must have been delegated the appropriate permissions. In addition, you must run **wbadmin** from an elevated command prompt. (To open an elevated command prompt right-click **Command prompt** and then click **Run as administrator**.)
## Syntax
```
wbadmin disable backup
[-quiet]
```
## Parameters
|Parameter|Description|
|-------|--------|
|-quiet|Runs the subcommand with no prompts to the user.|
#### additional references
-   [Command-Line Syntax Key](command-line-syntax-key.md)
-   [wbadmin](wbadmin.md)