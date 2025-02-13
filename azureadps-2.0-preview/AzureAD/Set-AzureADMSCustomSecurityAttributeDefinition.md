---
external help file: Microsoft.Open.MS.GraphBeta.PowerShell.dll-Help.xml
Module Name: AzureADPreview
online version:
schema: 2.0.0
---

# Set-AzureADMSCustomSecurityAttributeDefinition

## SYNOPSIS
Update an existing Azure Active Directory CustomSecurityAttributeDefinition.

## SYNTAX

```
Set-AzureADMSCustomSecurityAttributeDefinition -Id <String> [-Description <String>] [-Status <String>]
 [-UsePreDefinedValuesOnly <Boolean>] [<CommonParameters>]
```

## DESCRIPTION
Updates an Azure Active Directory CustomSecurityAttributeDefinition object identified by id.

## EXAMPLES

### Example 1
```powershell
Set-AzureADMSCustomSecurityAttributeDefinition -Id "TestSet_TestAttribute" -Description "New Test Description"
```

Patch single definition

### Example 2
```powershell
Set-AzureADMSCustomSecurityAttributeDefinition -Id Storage_Project2 -Status "Deprecated" -UsePreDefinedValuesOnly $false
```

Patch single definition

## PARAMETERS

### -Description
Description name for the customSecurityAttributeDefinition.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The unique identifier of a CustomSecurityAttributeDefinition in Azure Active Directory.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Status
String determines whether attribute is currently active or has been deprecated.Acceptable values will be 'Available' and 'Deprecated'.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UsePreDefinedValuesOnly
Determines whether the attribute is free form or restricted to allowed list of values only.

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS
