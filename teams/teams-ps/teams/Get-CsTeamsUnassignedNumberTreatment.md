---
external help file: Microsoft.Open.Teams.CommonLibrary.dll-Help.xml
Module Name: MicrosoftTeams
online version: https://docs.microsoft.com/powershell/module/teams/get-csteamsunassignednumbertreatment
applicable: Microsoft Teams
author: jenstrier
ms.author: jenstr
ms.reviewer: 
manager:
schema: 2.0.0
---

# Get-CsTeamsUnassignedNumberTreatment

## SYNOPSIS
Displays a specific or all treatments for how calls to an unassigned number range should be routed.

  
## SYNTAX

```powershell
Get-CsTeamsUnassignedNumberTreatment [-LocalStore] [[-Identity] <String>] [-Filter <String>] [<CommonParameters>]

```

## DESCRIPTION
This cmdlet displays a specific or all treatments for how calls to an unassigned number range should be routed.

## EXAMPLES

### Example 1
```powershell
Get-CsTeamsUnassignedNumberTreatment -Identity MainAA
```
This example displays the treatment MainAA.

### Example 2
```powershell
Get-CsTeamsUnassignedNumberTreatment
```
This example displays all configured treatments.

### Example 3
```powershell
Get-CsTeamsUnassignedNumberTreatment -Filter Ann*
```
This example displays all configured treatments with an Identity starting with Ann.



## PARAMETERS

### -Filter
Enables you to limit the returned data by filtering on the Identity attribute.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Applicable: Microsoft Teams

Required: False
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```
### -Identity
The Id of the specific treatment to show.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LocalStore
This parameter is reserved for internal Microsoft use.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.Object

## NOTES
The cmdlet is available in Teams PS module 2.5.1 or later.


## RELATED LINKS
[Remove-CsTeamsUnassignedNumberTreatment](Remove-CsTeamsUnassignedNumberTreatment.md)

[New-CsTeamsUnassignedNumberTreatment](New-CsTeamsUnassignedNumberTreatment.md)

[Set-CsTeamsUnassignedNumberTreatment](Set-CsTeamsUnassignedNumberTreatment.md)