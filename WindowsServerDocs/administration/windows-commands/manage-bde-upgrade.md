---
title: manage-bde upgrade
description: Reference topic for **** - 

ms.prod: windows-server


ms.technology: manage-windows-commands

ms.topic: article
ms.assetid: 23bfa824-6ff0-44cc-9b8b-b199a769fb8d
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# manage-bde: upgrade



Upgrades the BitLocker version.

## Syntax

```
manage-bde -upgrade [<Drive>] [-computername <Name>] [{-?|/?}] [{-help|-h}]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|\<Drive>|Represents a drive letter followed by a colon.|
|-computername|Specifies that Manage-bde.exe will be used to modify BitLocker protection on a different computer. You can also use **-cn** as an abbreviated version of this command.|
|\<Name>|Represents the name of the computer on which to modify BitLocker protection. Accepted values include the computer's NetBIOS name and the computer's IP address.|
|-? or /?|Displays brief Help at the command prompt.|
|-help or -h|Displays complete Help at the command prompt.|

## Examples

To illustrates using the **-upgrade** command to upgrade BitLocker encryption on drive C.
```
manage-bde –upgrade C:
```

## Additional References

-   - [Command-Line Syntax Key](command-line-syntax-key.md)
-   [Manage-bde](manage-bde.md)
-   [Upgrading a BitLocker-Protected Computer from Windows Vista to Windows 7](https://technet.microsoft.com/library/ee424325(v=ws.10).aspx)